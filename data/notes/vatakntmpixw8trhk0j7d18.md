
## example projects
- led prototype board light-on wsd 20 clone stm32 - up and running
- halloween vending machine
  build earrings for rabbi
- rc2014

## notes

- diffs are useless unless you pay for a service
- openscad - jump to microelectronics
- challenge getting into digital space
- "structural diffing" - see diff tastic
- need for name-spacing; unambiguous means of referencing component instances
  - need a means of mapping dof schema to other tools (e.g., KiCad, FreeCAD)
    - this enables referencing data (s.a., part description) in DOF to enhance understanding data in other tools (e.g., what is the purpose of capacitor C2 in board layout)
    - this enables deeper referencing within instructions (e.g., where to place capacitor on a board based on board layout within assembly instructions)
  - any instance of a component in DOF needs to have a (fully qualified?) singular definitive name; this should be one-to-one and onto
    - investigate connection between structural diffing and mapping to other tools in user stories
- need context as to why a design was changed (e.g., a capacitor was swapped out or removed), or any design decision
  - this is a kind of annotation capability that should
    - annotate any element in a project (e.g., components, aspects of components, steps in instructions, any data structure)
    - include ability to leave commentary
    - be able to point to one or more element(s) that it is annotating
    - be able to point to one or more "source" element(s), s.a.,
      - a Bib reference
      - another annotation
      - an "analysis artifact"
    - be supported in m30ml
