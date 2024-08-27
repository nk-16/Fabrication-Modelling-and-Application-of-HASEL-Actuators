# Fabrication-Modelling-and-Application-of-HASEL actuators

* **What is a HASEL actuator ?**

<img src="https://github.com/nk-16/Fabrication-Modelling-and-Application-of-HASEL-Actuators/blob/main/Screenshot%202024-07-14%20021546.png" alt="Image 1" width="250"/>
<img src="https://github.com/nk-16/Fabrication-Modelling-and-Application-of-HASEL-Actuators/blob/main/Screenshot%202024-07-14%20021727.png" alt="Image 2" width="250"/>
  
HASEL stands for Hydraulically Amplified Self-healing Electrostatic actuator. These actuators utilize a combination of electrostatic and hydraulic forces to generate movement, mimicking the behaviour of natural muscles. HASEL actuators are characterized by their ability to produce significant strain and force, self-heal when damaged, and adapt to various applications. HASEL actuators are composed of a dielectric shell filled with a liquid and surrounded by electrodes. When a high voltage is applied, the electrodes generate an electrostatic force, deforming the liquid and causing the actuator to change shape. This deformation mimics the contraction and expansion of biological muscles, allowing the actuator to move. The combination of hydraulic and electrostatic forces enables HASEL actuators to achieve high actuation strains and forces, making them suitable for various soft robotic applications.

This work was part of my internship at the Robotics Materials Department of Max Planck Institute of Intelligent Systems, Stuttgart, under the supervision of Prof. Christoph Keplinger and Mr. Toshihiko Fukushima, which I did through the DAAD WISE Scholarship. My activities encompassed three main topics: 1. fabrication of the soft electrohydraulic actuators, 2. analytical study of the electrical-mechanical interfacing of the actuator, and 3. development of a robotic application of the actuator.

* **Fabrication of HASEL actuator**

<img src="https://github.com/nk-16/Fabrication-Modelling-and-Application-of-HASEL-Actuators/blob/main/WhatsApp%20Image%202024-06-04%20at%207.34.38%20PM.jpeg" alt="Image 1" width="250"/>
<img src="https://github.com/nk-16/Fabrication-Modelling-and-Application-of-HASEL-Actuators/blob/main/WhatsApp%20Image%202024-06-07%20at%203.11.32%20PM.jpeg" alt="Image 2" width="250"/>

The fabrication of HASEL actuators involved a series of carefully planned steps, each designed to ensure the production of high-quality actuators suitable for research and application. The process began with heat
sealing of films using a heat extruder head mounted on a CNC machine to seal films together for the actuators. These heat-sealed films were then used in a screen-printing process to apply conductive layers in
carbon ink. Then, dielectric liquid like silicon oil fills these films through tiny pores using syringes. These pores are then heat-sealed using soldering iron. I fabricated over 50 actuators.

* **Modelling of (HASEL + leg) system**

<img src="https://github.com/nk-16/Fabrication-Modelling-and-Application-of-HASEL-Actuators/blob/main/Screenshot%202024-08-27%20160632.png" alt="Image 1" width="250"/>

A critical aspect of the work was developing a model to describe the relationship between the electrical input and the resulting mechanical behaviour of the HASEL actuators. This model was based on the Lagrangian
equation of motion, which provided a framework for understanding the dynamics of the actuator's movement. This included accounting for factors such as the actuator's geometry, material properties, and the characteristics of the liquid inside the dielectric shell.

* **Bioinspired design of Dragonfly wing mechanism**

<img src="https://github.com/nk-16/Fabrication-Modelling-and-Application-of-HASEL-Actuators/blob/main/Diagrammatic-cross-section-of-insect-flight-muscles-I-Thorax-mechanisms-of-direct.png" alt="Image 1" width="250"/>
<img src="https://github.com/nk-16/Fabrication-Modelling-and-Application-of-HASEL-Actuators/blob/main/QN4A9881.JPG" alt="Image 2" width="250"/>

The final stage of the project involved applying the fabricated and modelled HASEL actuators to a specific robotic application. The chosen application was the development of a bio-inspired mechanism designed to
mimic the movement of a dragonfly wing. This application was selected due to the complexity and precision required to replicate the wing's movement, making it an ideal test case for the HASEL actuators. The design process began with a review of biological literature to understand the mechanics of dragonfly wing movement. This information was then used to create a CAD model of the wing structure, prototyped using 3D printing. The fabricated wing structure was integrated with the HASEL actuators, allowing it to achieve high-speed reciprocating motion. The system was tested at various frequencies and voltages, with the results showing that the wing's movement closely matched the specifications of an actual dragonfly wing, particularly at a frequency of 20 Hz. An actual dragonfly wing usually has a 20 to 40 Hz frequency and 20-40 mm wing stroke, so at 20 Hz, 6kV, step input, the developed wing matches the specifications of an actual dragonfly wing.


