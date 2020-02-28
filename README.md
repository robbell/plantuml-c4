# PlantUML templates for C4 diagrams

Builds heavily on the [PlantUML C4 templates](https://github.com/RicardoNiepel/C4-PlantUML) by Ricardo Niepel, adding styling more similar to that used by the [C4 samples](https://c4model.com/#CoreDiagrams) and [Structurizr](https://structurizr.com/).

Additional features include or will include in future:

- Additional styling options
- More flexibility with relationships

## Sample Context diagram
![Sample Context diagram](samples/sample-context.svg)

## Related

To add **PlantUML** diagram generation to your build pipeline, take a look at my [PlantUML in Docker](https://github.com/robbell/plantuml-docker) project.

## To do

- [ ] Additional functions for remaining Context entities, and all other entities at the Container and Component level
- [ ] Update current implementations to more closely resemble vanilla PlantUML syntax
- [ ] Consider usage of `together` for grouping
- [ ] Additional styling options https://plantuml.com/class-diagram#Skinparam
- [x] Relationship directions
- [ ] Layout helpers
