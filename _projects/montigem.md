---
layout: page
title: MontiGem 
description: 
img: /assets/img/montigem.png
importance: 5
---

The MontiGem framework allows developers to generate large parts of a web application for a domain specific 
 information system based on a set of input models.
MontiGem can handle models in different Domain-Specific Languages
(DSLs) as input. The used DSLs are based on [MontiCore](https://monticore.de), a
language workbench and development tool framework for defining DSLs.
Currently, the generator handles the following set of models: 
the domain model defined as UML Class Diagram (CD) [GMN+20], 
data models (views on the data structure), 
GUI models representing the graphical interfaces [GMNR21], 
tagging models for the addition of rights and roles, 
and models defined with the Object Constraint Language (OCL) to
define restrictions on the data model and data input validation in the GUI.
The generated parts include the database, the backend, the communication between application backend and the frontend
 and graphical user interfaces. 

To support the retrofitting of existing applications, we have developed a methodology with three phases: 
problem analysis and decomposition, domain-specific language engineering, and application engineering and 
operation [DGM+21]. 
We show this methodology using a concrete example from practice, namely an information system, 
and discuss challenges with and lessons learned from the practical application. 

We are using MontiGem in a series of projects and application
domains, e.g., 
energy management systems, 
platforms to support the engineering of wind turbines, 
cockpits for self-adaptive digital twins [DMR+20] within the Cluster of Excellence [Internet of Production](../iop),
a platform to manage and control chair finances, staff, and projects within the [MaCoCo](../macoco) project,
or a platform for improving the
understandablity of privacy policies of smart watches within the [InviDas](../invidas) project.

#### Selected publications

- [DGM+21] I. Drave, A. Gerasimov, J. Michael, L. Netz, B. Rumpe, S. Varga:
  [A Methodology for Retrofitting Generative Aspects in Existing Applications](http://www.jot.fm/issues/issue_2021_02/article7.pdf).
  In: Journal of Object Technology, Volume 20, no. 2 , pages 1-24, November, 2021,
  AITO - Association Internationale pour les Technologies Objets.

- [GMNR21] A. Gerasimov, J. Michael, L. Netz, and B. Rumpe:
[Agile Generator-Based GUI Modeling for Information Systems.](http://www.se-rwth.de/publications/Agile-Generator-Based-GUI-Modeling-for-Information-Systems.pdf)
In: Ajantha Dahanayake, Oscar Pastor, Bernhard Thalheim, editors, Modelling to Program (M2P),
pages 113-126, March, 2021, Springer.

- [GMN+20] A. Gerasimov, J. Michael, L. Netz, B. Rumpe, S. Varga:
    [Continuous Transition from Model-Driven Prototype to Full-Size Real-World Enterprise Information Systems.](http://www.se-rwth.de/publications/Continuous-Transition-from-Model-Driven-Prototype-to-Full-Size-Real-World-Enterprise-Information-Systems.pdf)
    In: Bonnie Anderson, Jason Thatcher, Rayman Meservy, editors, 25th Americas Conference on Information Systems (AMCIS 2020), AIS Electronic Library (AISeL), pages 1-10, August, 2020, Association for Information Systems (AIS).

- [AMN+20a] K. Adam, J. Michael, L. Netz, B. Rumpe, S. Varga:
    [Enterprise Information Systems in Academia and Practice: Lessons learned from a MBSE Project.](http://www.se-rwth.de/publications/Enterprise-Information-Systems-in-Academia-and-Practice-Lessons-learned-from-a-MBSE-Project.pdf)
    In: 40 Years EMISA: Digital Ecosystems of the Future: Methodology, Techniques and Applications (EMISA'19), LNI P-304, pages 59-66, May, 2020, Gesellschaft für Informatik e.V..

- [DMR+20] M. Dalibor, J. Michael, B. Rumpe, S. Varga, A. Wortmann:
  [Towards a Model-Driven Architecture for Interactive Digital Twin Cockpits.](https://www.se-rwth.de/publications/Towards-a-Model-Driven-Architecture-for-Interactive-Digital-Twin-Cockpits.pdf)
  In: G. Dobbie, U. Frank, G. Kappel, S. Liddle, H. Mayr, editors, Conceptual Modeling, pp. 377-387, Springer, Oct. 2020.
