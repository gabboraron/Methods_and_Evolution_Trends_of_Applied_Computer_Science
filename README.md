# Methods and Evolution Trends of Applied Computer Science
> The study course is dedicated to discussions on modern methods of applied computer science with an emphasis on research conducted at Riga Technical University. Students are encouraged to analyse online materials, periodical publications, and current information from scientific conferences and symposia, following trends in applied computer science and evaluating their development prospects. Independent work promotes the use and development of the latest trends in applied computer science in the master thesis.

> ## grading 
> - There are multiple individual assignments in report and/or presentation format which are evaluated.
> - Independent studies include performing research within the Master Thesis with the aim to synthesize it with the information considered within the course.
> - The course final grade is calculated as a weighted average of individual assignments (see Tentative outline) and an examination.
> - More than one-month late submission and/or violation of academic integrity* decreases the assignment grade potentially down to failed.
> - During the semester, the progress will be reflected in the Grades section of the course.

## class 1 - State of art in applied computer science
<img src="https://cloudnine.com/wp-content/uploads/2020/03/2019-2020InternetMinute.png" width="60%"> <img src="http://cdn.statcdn.com/Infographic/images/normal/25443.jpeg" width="30%"> 

hot topics in IT:
- open-source
- cloud
- IoT
- AI
- ML
- VR
- cryptocurrencies
- cybersecurity

State of Software Development:
- v1.0 - 1969
- v2.0 - 2010 - *"Software is eating the world, and also eating itself"* <- the real problem is that a world running on bnuggy softwarre.
  - [Can We Really Achieve Software Quality? - Ipek Ozkaya](https://www.computer.org/csdl/magazine/so/2021/03/09407296/1sVENKRscVi)

what we learned from covid pandemic:
- Efficiency: Short-term optimization
- Resilience: Long-term optimization

What Software is Really About?
- People vs. Processes
- Science vs. Art (Engineering vs.Craftsmanship)
- Documenting vs. Understanding
- Metrics vs. Skills vs. Methods
- Good Enough vs. Right and Wrong

*"Scientific thinking evolved as a means of understanding the world."* Grady Booch

*"There is nothing more practical as a good theory."* - Boltzmann 

![we are to busy to improve](https://hakanforss.files.wordpress.com/2014/03/are-you-too-busy-to-improve2.png)



## class 4 - 
## class 5
Use the Functional features table template to:
- Refine problem domain description according to the discussion/lecturer feedback comments.
- Fill a functional features (FFs) table and design an initial TFM. (You can choose any appropriate tool for the TFM creation, e.g. Visio, draw.io, Word, etc.)
- Submit the refined description, FFs table and initial TFM before the next class.  

## class 6 - trends in model-driven software development - solution domain design and validation
- model driven enviroment (MDE)
  - model driven development (MDD) 
    - model driven architecture (MDA)

[Jon Whittle, John Hutchinson, and Mark Rouncefield. The State of Practice in Model-Driven Engineering](https://ieeexplore.ieee.org/document/6507223)

human factor is also a favour who benefits in MDE

### Psyhology of MDE
- managers
- software archiects
- code gurus
- hobbyist dev

### MDE adoption Issues
- organization factors
  - business domains
  - geenric software deveelopment
- MDE approaches Training issues
  - learning of abstraction
  - software modelling practice

### MDE in research VS industry
In practice developers rarely use MDE to generate whole systems – they apply it to develop key parts of a system.
- MDE is necessary, but not sufficient!

### Mapping Solution Domain Functional Requirements to Problem Domain Functional Features
![topological class diagram refine abstract](https://www.researchgate.net/profile/Janis-Osis-2/publication/226537727/figure/fig7/AS:858954385080324@1581802092330/The-process-of-the-development-of-the-topological-class-diagram_W640.jpg)

### Extended Tuple Functional Feature of a System
**<Id, A , R, O, PreCond, PostCond, Pr, Ex, S, Cl, Op>**,
- **Cl** is a class (type of object O) which will represent system in static model the object which will contain operation for functionality defined by this functional feature (can be fulfilled when the class diagram is synthesized)
- **Op** is an operation which will contain functionality defined by functional feature (this parameter can be fulfilled when the class diagram is synthesized)
