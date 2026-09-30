# cs-ne 
# CoreSense Navigation Essential

The **CoreSense Navigation Essential (CS-NE)** is a reference architectural design pattern designed to endow autonomous mobile robots with robust, flexible, and self-aware navigation capabilities. Drawing
profound inspiration from the [EasyNavigation (EasyNav)](https://github.com/EasyNavigation) framework, CS-NE is fundamentally representation-agnostic, lightweight, and highly modular. It leverages EasyNav's philosophy of decoupling navigation logic from the underlying map structures (natively supporting 2D costmaps, 3D Octomaps, NavMaps, and hybrid combinations) and elevates it by embedding it into the CoreSense cognitive architecture.

Within CS-NE, standard navigation components (localizers, planners, and controllers) are encapsulated as *Cognitive Modules* (CogMods). These modules communicate via *Modelets* (semantic knowledge fragments) and
are governed by a dual-level Epistemic Control Loop: a base perception-action pipeline for active mission execution, and a metalevel pipeline dedicated to continuous self-awareness, metacognition, and dynamic adaptation.

See CoreSense Architecture definition (D2.2) for more details concerning **essentials**.

## Acknowledgement

<img src="https://github.com/user-attachments/assets/b11da974-9201-4f79-902e-c9c20e8aa7a4" alt="Funded by the European Union" width="240"/>

This work has received funding from the European Union's Horizon Europe research and innovation programme under grant agreement No 101070254 ([CORESENSE](https://coresense.eu)). Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Commission. Neither the European Union nor the granting authority can be held responsible for them.
