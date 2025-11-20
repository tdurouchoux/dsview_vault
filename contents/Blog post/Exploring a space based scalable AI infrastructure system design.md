---
already_read: true
link: https://research.google/blog/exploring-a-space-based-scalable-ai-infrastructure-system-design/
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- Development_tool
type: Content
upload_date: '2025-11-20'
---

https://research.google/blog/exploring-a-space-based-scalable-ai-infrastructure-system-design/
## Summary

Project Suncatcher is a research initiative by Google to explore the feasibility of a space-based, scalable AI infrastructure system design. The project aims to equip solar-powered satellite constellations with Tensor Processing Units (TPUs) and free-space optical links to scale machine learning compute in space. The ultimate goal is to leverage the Sun's abundant energy to power AI computations, reducing the need for terrestrial resources.

Key challenges and solutions include:

1. **Inter-satellite Links**: Achieving data center-scale communication between satellites using multi-channel dense wavelength-division multiplexing (DWDM) transceivers and spatial multiplexing. A bench-scale demonstrator has already achieved 1.6 Tbps total transmission.

2. **Satellite Formation Control**: Maintaining stable, tightly-clustered satellite formations using numerical and analytic physics models to account for Earth's gravitational effects and atmospheric drag.

3. **Radiation Tolerance**: Testing TPUs in a proton beam to assess their radiation tolerance. Results showed promising resilience to total ionizing dose (TID) and single event effects (SEEs).

4. **Economic Feasibility**: Analyzing historical and projected launch pricing data to determine the cost-effectiveness of space-based data centers. Prices are expected to fall to less than $200/kg by the mid-2030s, making space-based data centers comparable to terrestrial ones in terms of energy costs.

Future directions involve a learning mission with Planet to launch prototype satellites by early 2027, testing models and TPU hardware in space, and validating optical inter-satellite links for distributed ML tasks. The project acknowledges significant engineering challenges but believes that the core concepts are feasible and could lead to gigawatt-scale constellations in the future.
## Links

- [High Bandwidth Memory](https://en.wikipedia.org/wiki/High_Bandwidth_Memory) : High Bandwidth Memory (HBM) is a high-performance RAM interface used in AI accelerators.
- [Spatial Multiplexing](https://en.wikipedia.org/wiki/Spatial_multiplexing) : Spatial multiplexing is a technique used in communication systems to transmit multiple data streams simultaneously.
- [Dense Wavelength-Division Multiplexing](https://en.wikipedia.org/wiki/Wavelength-division_multiplexing#Dense_WDM) : Dense Wavelength-Division Multiplexing (DWDM) is a technology used to transmit data over optical fibers using multiple wavelengths of light.
- [Free-space Optical Communication](https://en.wikipedia.org/wiki/Free-space_optical_communication) : Free-space optical communication is a technology that uses light to transmit data through the air, without the need for optical fibers.
- [Planet Labs](https://www.planet.com/) : Planet Labs is a company that operates a large constellation of satellites to provide global, daily imagery of the Earth.

## Topics

![[topics/Concept/Project Suncatcher]]

![[topics/Concept/Free space optical links]]

![[topics/Concept/Dense Wavelength Division Multiplexing DWDM]]

![[topics/Concept/Hill Clohessy Wiltshire equations]]

![[topics/Concept/Total Ionizing Dose TID]]

![[topics/Concept/Single Event Effects SEEs]]