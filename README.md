## PhyTDOA-Net

Physics-Guided Self-Supervised TDOA Error Correction Network

*Overview*

PhyTDOA-Net is a lightweight edge-oriented neural correction framework designed to improve the robustness of traditional TDOA localization systems under challenging wireless environments, **mainly designed for FM radio broadcasting**.

Unlike end-to-end neural localization approaches, PhyTDOA-Net does not replace conventional positioning algorithms. Instead, it learns propagation-induced timing errors and provides adaptive corrections before classical TDOA solving.




*Motivation*

Traditional TDOA localization systems provide accurate positioning under ideal propagation conditions.

However, real-world environments introduce:

* Non-Line-of-Sight (NLOS) propagation
* Multipath effects
* Dynamic obstruction
* Frequency-dependent delay distortion

These effects can introduce significant timing bias, causing:

* Large positioning deviation
* Unstable localization
* Outlier solutions

PhyTDOA-Net aims to mitigate these issues by learning propagation error patterns while preserving physical localization principles.


*Key Features*

Physics-guided Learning

The model incorporates physical consistency constraints instead of relying purely on data-driven fitting.

Benefits:

* Better generalization
* Reduced dependency on labeled data
* Compatibility with traditional localization algorithms


*Self-supervised Error Correction*

The network learns timing correction from measurement consistency without requiring large-scale manually labeled localization datasets.


*NLOS Robustness*

Designed for challenging propagation conditions:

* Urban environments
* Indoor/outdoor mixed scenarios
* Dynamic wireless channels


*Edge-Oriented Design*

The model is optimized for resource-constrained devices:

* Lightweight architecture
* Low inference complexity
* MCU deployment potential

Target platforms:

* ESP32-class devices
* ARM Cortex-M microcontrollers
* Edge gateways

*Application Scenarios*

Potential applications include:

* Earthquake early warning sensor networks
* Wireless emergency communication systems
* Distributed IoT localization
* Edge intelligence positioning systems
* Industrial monitoring networks


*Current Status*

Research Prototype

*Current stage*

* Simulation validation
* NLOS robustness evaluation
* Generalization testing
* Edge deployment feasibility analysis

*Future work*

* Hardware deployment
* Real-world channel measurements
* Further model compression
