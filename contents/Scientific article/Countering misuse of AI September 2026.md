---
already_read: false
link: https://www.anthropic.com/threat-intelligence-report-september-2026
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- AI_regulation
type: Content
upload_date: '2026-09-27'
---

https://www.anthropic.com/threat-intelligence-report-september-2026

## Summary

Anthropic’s September 2026 report details global misuse of its Claude AI models across cyber, influence, surveillance, weapons, biological, fraud, and distillation domains, with disruptions, safeguard updates, and intelligence sharing.

**Scope and trends**
- Covers Dec 2025–Aug 2026, with Claude Haiku, Sonnet, and Opus models (no Fable/Mythos misuse except one distillation case).
- Threat actors: state-sponsored groups, criminals, spyware vendors, propaganda institutions, hacktivists.
- AI uplifts speed, scale, and depth of attacks, collapsing the skill gap between state and non-state actors.
- Autonomous AI-driven workflows now manage reconnaissance, exploitation, and data exfiltration with minimal human oversight.

**Cyber operations**
- **GTG-20006 (Russian espionage)**: Automated AI workflows for phishing, malware evasion, and data exfiltration; targeted Ukrainian/European governments, drone supply chains, and hotel WiFi DNS hijacking.
- **GTG-50014 (ShinyHunters)**: Credential harvesting at scale (1.8M APKs scanned), supply-chain attacks, and ransomware; exfiltrated >1TB from a tech provider, accessed tens of millions of airline passenger records.
- **GTG-10007 (Chinese students)**: Autonomous vulnerability research (zero-days in security appliances), exploit development, and reconnaissance against global government/military targets.
- **GTG-50020**: Compromised AI vendor sandbox to steal production API keys, then targeted 30+ AI companies in 4 days.
- **GTG-50029 (French hacktivist)**: Exploited WordPress race conditions, built doxxing platform with 12–26GB of exfiltrated data (political donors, student records).

**Influence operations**
- **GTG-04001 (Russian FIMI in CAR)**: Radio Lengo Songo (98.9 FM) amplified pro-Russia/anti-France narratives; used Claude for contracts, scripts, and forged CAR government documents.
- **GTG-54002 (LKM Company)**: 70 fake news sites, 70+ X accounts, 250+ inauthentic commenters; targeted US, Brazil, France, DRC with tailored political slants.
- **GTG-84005 (BBS Bilisim, Turkey)**: Targeted Malaysian voters using census data; managed 1,000+ fake X accounts, synthetic news outlet ("Malaysia Pulse"), and fabricated dossiers.
- **GTG-24015 (Russian state media)**: Claude integrated into editorial pipelines for Sputnik/RT; produced content for Moldova’s 2025 election, including defamatory claims about President Maia Sandu.
- **GTG-34001 (Iranian ICCO/IRGC)**: Built doctrine manuals, persona systems, and target databases; laundered state narratives as independent voices.
- **GTG-54006 (Bangladesh)**: Automated fake news in Bengali; 1,500 headlines, 300 false narratives, 1,500 image prompts; targeted rural Awami League supporters.
- **GTG-84006 (MEK/NCRI)**: Impersonated real activists, built psychographic dossiers on Iranians, and used AI-generated avatars for propaganda.
- **GTG-54004 (Kenya)**: Generated 50-tweet batches to simulate grassroots support for Energy CS Opiyo Wandayi and attack opposition.
- **GTG-84002 (UAE)**: AI persona "Deadshot" targeted Muslim Brotherhood; ghost-wrote UN testimonies, profiled MEPs/journalists, and compiled counter-dossiers on UN rapporteurs.

**Surveillance operations**
- **GTG-54009 (S2T Unlocking Cyberspace)**: Commercial platform profiled Iranian/Persian Gulf social media users; categorized by demographics, political leanings, and generated Arabic intelligence briefings.
- **GTG-14010 (PRC)**: Targeted Uyghurs in Syria; used Claude for recruitment, geolocation, and suppression campaigns against Uyghur diaspora media.
- **GTG-14020 (PRC religious affairs)**: Built dossiers on Catholic/Tibetan/Falun Gong leaders; monitored domestic and foreign platforms (WeChat, LinkedIn, X).
- **GTG-14021 (PRC public security)**: "Stability maintenance" surveillance; targeted Hong Kong pro-democracy figures, Tiananmen organizers, Uyghur advocates.
- **GTG-14022 (PRC contractor)**: Public opinion monitoring; scored content by political sensitivity, reframed foreign media as hostile.
- **GTG-34007 (Iran)**: Built surveillance case-management system ("Arman"); developed Firefox extension to harvest social media identities.
- **GTG-50027 (Mali)**: "Lakana 360" platform for ANSE; monitored 25M SIM cards, bypassed warrant requirements, and flagged VPN/encryption users.

**Conventional weapons**
- **GTG-87001 (Yemen)**: Developed guidance software for rockets/missiles; live field test failed, debugged with Claude.
- **GTG-17001 (China)**: Drafted anti-torpedo fire control specs and 200+ page proposals; benchmarked against US Navy systems.
- **GTG-27005 (Russia)**: Engineered autonomous FPV drone swarm ("DronDoc/Serafim"); trained CV models on Ukrainian combat footage.
- **GTG-17002 (China)**: Built electronic warfare/air defense suppression software; targeted Taiwanese radar/Patriot sites.
- **GTG-27006 (Russia)**: Procured dual-use goods (magnetometers, PV wafers, oxygen systems) via third-country intermediaries to evade sanctions.
- **GTG-17003 (China)**: Collected intelligence on directed-energy weapons; mapped supply chains for high-power microwave systems.

**Biological misuse**
- **Case 1**: Chikungunya gain-of-function research (transmissibility/immune evasion) at a military institute; evaded regional blocks via US infrastructure.
- **Case 2**: Avian influenza mammalian-adaptation research; accessed via VPN from unsupported region; used weaker models (Sonnet 4, Haiku 4.5).
- **Case 3**: Orthopoxvirus immune-evasion grant application; drafted in ~1 hour on Opus 5 via reseller relay.
- **Case 4**: Venom peptide atlas + generative optimization pipeline; dual-use for therapeutics/incapacitating agents.
- **Case 5**: Computational redesign of toxins; obscured agent identities in progress reports; part of a national program.

**Scams and fraud**
- **GTG-15001**: 20+ dating apps with 4,700+ AI personas; 3:1 AI-to-human ratio; used stolen API keys and reseller infrastructure.

**Illicit distillation**
- **Definition**: Industrial-scale, covert extraction of model capabilities via fraudulent accounts (stolen credentials, VPNs, proxy services).
- **Actors**: Alibaba (151M exchanges), Moonshot (23M), DeepSeek (12.1M), Zhipu (3.4M), Xiaomi (400K), SenseTime, MiniMax.
- **Techniques**: Chain-of-thought extraction, cross-session replay attacks, reasoning signature exploitation, multi-model fallback.
- **Impact**: Distilled models (e.g., Qwen 3.5–3.7) gained capabilities in agentic tasks, coding, and reasoning; safeguards do not transfer.
- **Data exposure**: Sensitive user data (corporate, government, personal) relayed to Claude without consent via reseller platforms.

**Safeguards and responses**
- Banned accounts, shared IOCs with authorities/industry, and strengthened classifiers (e.g., biological safety, cyber, distillation).
- Introduced summarized reasoning, preserved thinking (Fable 5.1), and identity verification for suspicious activity.
- Collaborated with AI labs (OpenAI, Google) and platforms (Apple, Google Play) to disrupt cross-platform abuse.
- Advocated for trusted access programs for high-risk domains (e.g., biology) to balance safety and beneficial use.

## Links

- [Microsoft Blog on AI-Enabled Device Code Phishing Campaign](https://www.microsoft.com/en-us/security/blog/2026/04/06/ai-enabled-device-code-phishing-campaign-april-2026/) : This Microsoft security blog post details the 'CaptiveCrunch' campaign by Midnight Blizzard, which leverages AI to automate phishing and malware delivery, including the use of device code phishing and DNS hijacking. It aligns with the misuse cases described in the Anthropic report, particularly in cyber operations and surveillance.
- [TruffleHog GitHub Repository](https://github.com/trufflesecurity/trufflehog) : TruffleHog is an open-source tool for detecting secrets in code repositories, which is referenced in the report as being used by threat actors (e.g., ShinyHunters affiliates) to harvest credentials and API keys from public repositories. This tool is relevant to the report's discussion of credential harvesting and supply-chain attacks.
- [PentAGI Offensive Agent Framework](https://github.com/vxcontrol/pentagi) : PentAGI is an open-source offensive agent framework mentioned in the report as enabling autonomous cyber kill chains. It is used by threat actors to automate reconnaissance, exploitation, and data exfiltration, aligning with the report's emphasis on AI-driven cyber operations.
- [Brookings Institution: The Breakout Scale for Influence Operations](https://www.brookings.edu/articles/the-breakout-scale-measuring-the-impact-of-influence-operations/) : This Brookings article introduces the Breakout Scale, a framework for measuring the impact of influence operations. It is referenced in the Anthropic report to assess the reach and authenticity of influence campaigns, making it highly relevant to the report's section on influence operations.
- [Forbidden Stories: S2T Unlocking Cyberspace Investigation](https://forbiddenstories.org/osint-s2t-unlocking-cyberspace-journalists-activists/) : This investigation by Forbidden Stories details the commercial surveillance platform 'S2T Unlocking Cyberspace,' which is linked to the Anthropic report's case study on AI-enabled surveillance operations. It provides context for the report's discussion of state-aligned and commercial spyware vendors using AI for surveillance.


## Topics

![[topics/Model/Fable]]

![[topics/Model/Mythos]]

![[topics/Tool/PentAGI]]

![[topics/Concept/Illicit distillation]]

![[topics/Concept/AI supply chain]]

![[topics/Concept/Agentic Frameworks]]

![[topics/Concept/Chain of Thought CoT]]

![[topics/Model/Claude]]

![[topics/Tool/Claude Code]]

![[topics/Model/Opus]]