# Git Practice

## Link to the article: 
[Serban, A., Poll, E. & Visser, J. A Standard Driven Software Architecture for Fully Autonomous Vehicles. J Automot Softw Eng 1, 20–33 (2020).](https://link.springer.com/article/10.2991/jase.d.200212.001)

## Why I found it interesting: 
The article’s most significant contribution to software engineering methodology lies in shifting the autonomous driving software architecture from a model based on "post-hoc summarization" to one of "standards-driven, requirements-led" engineering design. Rather than basing the design on a specific vehicle or competition experience, the authors start with the SAE J3016 standard to derive functional requirements and map them to functional components—thereby ensuring traceability between requirements and components—while also incorporating the NIST RCS reference architecture from the robotics field. Regarding functional decomposition, the article emphasizes atomization, treating features such as lane keeping and automatic parking as "composable functions" that support incremental development and distributed outsourcing. Furthermore, data management and system safety management are treated as independent cross-cutting concerns to avoid coupling with real-time control logic; the article also candidly acknowledges gaps in ISO 26262 regarding safety reasoning, thereby leaving room for the future evolution of standards.

