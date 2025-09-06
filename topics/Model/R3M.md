---
type: Model
---

R3M (Robot-Readiness Memory Model) is an embedding model adapted to suggest commonly selected objects and actions in the NOIR system. It is pretrained to generate similar embeddings for paired robot instructions and camera views, and dissimilar embeddings for mismatched pairs. By adding fully connected layers and training them on individual-user data, R3M helps the system predict the most likely object-action combination based on the camera image, enhancing the user experience by simplifying the selection process.