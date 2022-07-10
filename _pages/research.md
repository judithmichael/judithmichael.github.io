---
layout: page
permalink: /research/
title: Research
description: 
nav: true
order: 4
---

My research focus are (conceptual) models in a variety of domains and applications. 
We develop domain-specific languages (DSLs) and methods for 
domains such as Ambient Assisted Living, Controlling and Finances, Energy, Health, 
Manufacturing, Internet of Things (IoT), or Smart Homes. 
The models created with such languages can be used to develop information systems, 
assistive systems and services and digital twins
in an agile model-based way using generators for code synthesis.
This website presents selected research topics and related publications.
The full list of publications is available on the [publications](../publications) page.

<p align="center">
   <img src="{{ '/assets/img/balken_ass.png' | relative_url }}" width = "100%" alt="" title="Assistive System">
</p>

### Assistive Systems
Assistive systems provide situational support for human behaviour based on information from previously stored and
real-time monitored structural context and behaviour data at the time a person
needs or asks for it [HMR+19].
They provide critical functionality, or ensure safety in potentially dangerous work environments. 
Research is needed, as most of them are restricted to certain use cases which allows for less reusability.
We investigate needed context information [MS17],
modeling languages used during runtime and to support the engineering [MM13],
[MRV20],
[MRZ21],
and how to automate the engineering of assistive systems.
Investigated domains are, e.g., financial management [MRZ21], smart homes, or production [Mic22]. 

#### Selected Publications:

- [Mic22] J. Michael: [A Vision Towards Generated Assistive Systems for Supporting Human Interactions in Production](https://dx.doi.org/10.18420/modellierung2022ws-019).
In: Modellierung 2022 Satellite Events, pp. 150–153, Gesellschaft für Informatik e.V., Bonn, 2022.

- [MRZ21] J. Michael, B. Rumpe, L.T. Zimmermann: [Goal Modeling and MDSE for Behavior Assistance](http://www.se-rwth.de/publications/Goal-Modeling-and-MDSE-for-Behavior-Assistance.pdf).  
  In: Int. Conf. on Model Driven Engineering Languages and Systems Companion (MODELS-C), 
  pages 370-379, 2021.

- [MRV20] J. Michael, B. Rumpe, S. Varga. 
[Human Behavior, Goals and Model-Driven Software Engineering for Assistive Systems.](http://www.se-rwth.de/publications/Human-Behavior-Goals-and-Model-Driven-Software-Engineering-for-Assistive-Systems.pdf) 
In: Agnes Koschmider, Judith Michael, Bernhard Thalheim, editors, 
Enterprise Modeling and Information Systems Architectures (EMSIA 2020), 2628, pages 11-18, 
June, 2020, CEUR Workshop Proceedings.

- [SM20] C. Steinberger, J. Michael: [Using Semantic Markup to Boost Context Awareness for Assistive Systems.](https://www.se-rwth.de/publications/Using-Semantic-Markup-to-Boost-Context-Awareness-for-Assistive-Systems.pdf)
  In: F. Chen, R. I. García-Betances, L. Chen, M. F. Cabrera-Umpiérrez, C. Nugent, editors,
  Smart Assisted Living: Toward An Open Smart-Home Infrastructure, pp. 227-246, Springer, 2020.

- [MS17] J. Michael, C. Steinberger. [Context Modeling for Active Assistance.](http://ceur-ws.org/Vol-1979/paper-22.pdf)
  In: Cristina Cabanillas, Sergio España, Siamak Farshidi, editors, Proc. of the ER Forum 2017 and the ER 2017
  Demo Track co-located with the 36th Int. Conference on Conceptual Modelling (ER 2017), pages 221-234, 2017.

- [MM13] J. Michael, H. C. Mayr. [Conceptual Modeling for Ambient Assistance.](http://www.se-rwth.de/publications/Conceptual-Modeling-for-Ambient-Assistance.pdf)
In: Conceptual Modeling - ER 2013, LNCS 8217, pages 403-413, 2013, Springer.

<p align="center">
   <img src="{{ '/assets/img/balken_dtds.png' | relative_url }}" width = "100%" alt="" title="Digital Twins">
</p>

### Digital Twins & Digital Shadows
In our understanding, a digital twin consists of a set of models of the system, 
a set of digital shadows [BBD+21], and provides a set of services to use the data and models 
purposefully with respects to the original system [DMR+20].


#### Selected Publications
- [BMR+22] D. Bano, J. Michael, B. Rumpe, S. Varga, M. Weske:
  [Process-Aware Digital Twin Cockpit Synthesis from Event Logs](https://www.se-rwth.de/publications/Process-Aware-Digital-Twin-Cockpit-Synthesis-from-Event-Logs.pdf).
  In: Journal of Computer Languages (COLA), Volume 70, Elsevier, 2022.

- [DHM+22] M. Dalibor, M. Heithoff, J. Michael, L. Netz, J. Pfeiffer, B. Rumpe, S. Varga, A. Wortmann:
  [Generating Customized Low-Code Development Platforms for Digital Twins](https://www.se-rwth.de/publications/Generating-Customized-Low-Code-Development-Platforms-for-Digital-Twins.pdf).
  In: Journal of Computer Languages (COLA), Volume 70, Elsevier, 2022.

- [MPRW22] J. Michael, J. Pfeiffer, B. Rumpe, A. Wortmann:
  [Integration Challenges for Digital Twin Systems-of-Systems](https://www.se-rwth.de/publications/Integration-Challenges-for-Digital-Twin-Systems-of-Systems.pdf).
  In: 10th IEEE/ACM International Workshop on Software Engineering for Systems-of-Systems and Software Ecosystems, pp. 9-12, IEEE, May 2022.

- [BHK+21] T. Brockhoff, M. Heithoff, I. Koren, J. Michael, J. Pfeiffer, B. Rumpe, M.S. Uysal,
  W. M. P. van der Aalst, A. Wortmann: 
  [Process Prediction with Digital Twins](http://www.se-rwth.de/publications/Process-Prediction-with-Digital-Twins.pdf). Models@runtime’21 (MODELS’21).

- [BBD+21] F. Becker, P. Bibow, M. Dalibor, A. Gannouni, V. Hahn, C. Hopmann, M. Jarke, I. Koren, M. Kröger,
  J. Lipp, J. Maibaum, J. Michael, B. Rumpe, P. Sapel, N. Schäfer, G. J. Schmitz, G. Schuh, and A. Wortmann:
  [A conceptual model for digital shadows in industry and its application.](https://link.springer.com/chapter/10.1007/978-3-030-89022-3_22) 
  In: Conceptual Modeling. 
  ER 2021, LNCS 13011, pages 271-281, October, 2021, Springer. 

- [DMR+20] M. Dalibor, J. Michael, B. Rumpe, S. Varga, A. Wortmann: 
[Towards a Model-Driven Architecture for Interactive Digital Twin Cockpits.](https://www.se-rwth.de/publications/Towards-a-Model-Driven-Architecture-for-Interactive-Digital-Twin-Cockpits.pdf)
In: Conceptual Modeling, pp. 377-387, Springer, Oct. 2020.

- [KMR+20] J. C. Kirchhof, J. Michael, B. Rumpe, S. Varga, A. Wortmann. 
[Model-driven Digital Twin Construction: Synthesizing the Integration of Cyber-Physical Systems with Their 
Information Systems.](http://www.se-rwth.de/publications/Model-driven-Digital-Twin-Construction-Synthesizing-the-Integration-of-Cyber-Physical-Systems-with-Their-Information-Systems.pdf)
In: Proceedings of the 23rd ACM/IEEE International Conference on Model Driven Engineering 
Languages and Systems, pages 90-101, October, 2020, ACM.

<p align="center">
   <img src="{{ '/assets/img/balken_mbseis.png' | relative_url }}" width = "100%" alt="" title="MBSE of Information Systems">
</p>

### Model-Based Software Engineering of Information Systems
Using a small set of models, it is possible to generate large parts of information systems. 
With MontiGem, the generator framework for information systems [GMN+20], we have created a tool to support such a process in an 
agile, model-driven way. 

#### Selected Publications

- [DGM+21] I. Drave, A. Gerasimov, J. Michael, L. Netz, B. Rumpe, S. Varga:
  [A Methodology for Retrofitting Generative Aspects in Existing Applications](http://www.jot.fm/issues/issue_2021_02/article7.pdf).
  In: Journal of Object Technology, Volume 20, no. 2 , pages 1-24, November, 2021,
  AITO - Association Internationale pour les Technologies Objets. 

- [GMNR21] A. Gerasimov, J. Michael, L. Netz, B. Rumpe. 
[Agile Generator-Based GUI Modeling for Information Systems.](http://www.se-rwth.de/publications/Agile-Generator-Based-GUI-Modeling-for-Information-Systems.pdf) 
In: Ajantha Dahanayake, Oscar Pastor, Bernhard Thalheim, editors, Modelling to Program (M2P), 
pages 113-126, March, 2021, Springer.

- [GMN+20] A. Gerasimov, J. Michael, L. Netz, B. Rumpe, S. Varga.:
[Continuous Transition from Model-Driven Prototype to Full-Size Real-World Enterprise Information Systems.](http://www.se-rwth.de/publications/Continuous-Transition-from-Model-Driven-Prototype-to-Full-Size-Real-World-Enterprise-Information-Systems.pdf)
In: Bonnie Anderson, Jason Thatcher, Rayman Meservy, editors, 
25th Americas Conference on Information Systems (AMCIS 2020), AIS Electronic Library (AISeL), 
pages 1-10, August, 2020, Association for Information Systems (AIS).

<p align="center">
   <img src="{{ '/assets/img/balken_law.png' | relative_url }}" width = "100%" alt="" title="Modeling Law">
</p>

### Modeling Law
Domain-specific languages provide means to formulate law and contracts. 
This allows to verify plans according to contracts [DHH+20],
and to generate related IT systems from law [RMK+21].


#### Selected Publications

- [RMK+21] B. Rumpe, J. Michael, O. Kautz, R. Krebs, S. Gandenberger, J. Standt, U. Weber. 
[Digitalisierung der Gesetzgebung zur Steigerung der digitalen Souveränität des Staates.](http://www.se-rwth.de/publications/Digitalisierung-der-Gesetzgebung-zur-Steigerung-der-digitalen-Souveraenitaet-des-Staates.pdf) 
Berichte des NEGZ, Nationales E-Government Kompetenzzentrum e. V., June, 2021.

- [DHH+20] I. Drave, T. Henrich, K. Hölldobler, O. Kautz, J. Michael, B. Rumpe. 
[Modellierung, Verifikation und Synthese von validen Planungszuständen für Fernsehausstrahlungen.](http://www.se-rwth.de/publications/Modellierung-Verifikation-und-Synthese-von-validen-Planungszustaenden-fuer-Fernsehausstrahlungen.pdf) 
In: Dominik Bork, Dimitris Karagiannis, Heinrich C. Mayr, editors, Modellierung 2020, pages 173-188, 
February, 2020, Gesellschaft für Informatik e.V.

<p align="center">
   <img src="{{ '/assets/img/balken_privacy.png' | relative_url }}" width = "100%" alt="" title="Privacy">
</p>

### Privacy
Due to the General Data Protection Regulation (GDPR) organizations are obliged
to consider privacy throughout the complete development process.
In our work, we have created privacy preserving information systems and demonstrated it on an IoT manufacturing use
case [MKM+19],
we have created an approach for differential privacy for event logs
[MKB+19]
and we have shown how MDSE can be used to create privacy-preserving IoT systems
[MNRV19].

#### Selected Publications

- [MNRV19] J. Michael, L. Netz, B. Rumpe, S. Varga.
  [Towards Privacy-Preserving IoT Systems Using Model Driven Engineering.](https://www.se-rwth.de/publications/Towards-Privacy-Preserving-IoT-Systems-Using-Model-Driven-Engineering.pdf)
  In: Nicolas Ferry, Antonio Cicchetti, Federico Ciccozzi, Arnor Solberg, Manuel Wimmer, Andreas Wortmann, editors,
  MDE4IoT & ModComp 2019, Model-Driven Engineering for the Internet of Things (MDE4IoT) &
  Interplay of Model-Driven and Component-Based Software Engineering (ModComp), pages 15-22, Sep, 2019, CEUR-WS.org.

- [MKB+19] F. Mannhardt, A. Koschmider, N. Baracaldo, M. Weidlich, J. Michael.
  [Privacy-Preserving Process Mining: Differential Privacy for Event Logs.](https://www.se-rwth.de/publications/Privacy-Preserving-Process-Mining.pdf)
  Business & Information Systems Engineering (BISE), 61, pages 595-614, 2019.

- [MKM+19] J. Michael, A. Koschmider, F. Mannhardt, N. Baracaldo, B. Rumpe.
  [User-Centered and Privacy-Driven Process Mining System Design for IoT.](https://www.se-rwth.de/publications/User-Centered-and-Privacy-Driven-Process-Mining-System-Design-for-IoT.pdf)
  Chapter in Information Systems Engineering in Responsible Information Systems, Springer,
  ISBN 978-3-030-21296-4, LNBIP 350, pages 194-206, 2019.