Modelling of international standards
====================================

This is an attempt to model standards using a UML-like language - I will be starting with [PlantUML](https://plantuml.com/).

## Metamodel

![Metamodel image](http://www.plantuml.com/plantuml/proxy?cache=no&fmt=svg&src=https://raw.githubusercontent.com/johnwelford/standardsModel/main/metamodel.puml)

This is realised in the file [metamodel.puml](https://github.com/johnwelford/standardsModel/blob/main/metamodel.puml) - ALSO USE THIS TO STORE AND APPLY STEREOTYPES?

Each standard is modelled using three types of file:
* *A single markdown document showing the model*, including all the model diagrams along with descriptive text to introduce them. This should be the only file needed to read the standard.
* *A single PlantUML file detailing the entities*, listing all the entities (/classes) defined by the standard.
* *One or more PlantUML file detailing the relationships* between entities. Making reference to the entities defined above.

## Standards
* [AS 7473:2020 Complex system integration in railways]()

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
