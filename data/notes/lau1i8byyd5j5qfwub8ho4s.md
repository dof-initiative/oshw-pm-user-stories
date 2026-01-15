
## notes

- references should only be able to reference elements within the scope of the element that owns the reference (i.e., elements are unaware of parent or sibling elements; relationships between siblings are defined in a parent element)
- views reference elements
  - views are always siblings to elements
  - therefore, a view must be provided element(s) as input
  - elements that views are provided as input are provided via an interface into said view
- references are a 1-to-1 or 1-to-many relationship
- e.g., I might want to import my Universal Controller into another project but be able to mention that you need to plug something into a particular port on the Raspberry Pi. Would like there to be a way to reference it like parts.universal-controller.parts.raspberry-pi.description (in legacy DOF)
- references may be implemented as a qualified names (i.e., relative file path names or fully qualified domain names)
