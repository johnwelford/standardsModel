Modelling of international standards
====================================

This is an attempt to model standards using a UML-like language - I will be starting with [PlantUML](https://plantuml.com/).

## Disclaimer
This is a hobby project, it is not a substitute for reading standards yourself and should not be relied upon to present an accurate version of any standards.

It is also not intended to infringe upon any copyrights, it merely presents an interpretation of the details contained within a select number of standards. These are presented in an attempt to elicit discussion and enhance shared understanding.

## Metamodel

![Metamodel image](http://www.plantuml.com/plantuml/proxy?cache=no&fmt=svg&src=https://raw.githubusercontent.com/johnwelford/standardsModel/main/metamodel.puml)

This is realised in the file [metamodel.puml](metamodel.puml) - ALSO USE THIS TO STORE AND APPLY STEREOTYPES?

Each standard is modelled using three types of file:
* *A single markdown document showing the model*, including all the model diagrams along with descriptive text to introduce them. This should be the only file needed to read the standard.
* *A single PlantUML file detailing the entities*, listing all the entities (/classes) defined by the standard.
* *One or more PlantUML file detailing the relationships* between entities. Making reference to the entities defined above.

## Standards
* [AS 7473:2020 Complex system integration in railways](7473.md)

## To-do
- [x] Setup project
- [ ] Propose meta-model
- [ ] Develop first standard
- [ ] Separate entities and relationships
- [ ] Setup stereotype skin params
- [ ] Use terms in descriptions (as hyperlinks/hover text?)
- [ ] Build term links into entity file (use preprocessing script to generate image as an optional include subpart?)
- [ ] Add necessity on relationships?
- [ ] Use preprocessing to enforce conformance to metamodel?
- [ ] Make comparisons between standards (as separate files? treat standards as namespaces?)
