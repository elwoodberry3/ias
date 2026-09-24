# Design System


This concept is most commonly called a component library or a design system (when implemented in code).
Depending on the specific context and how your team structures it, it can also be referred to by a few other highly related terms:
## Key Terms

* Component Library: A collection of reusable, coded user interface (UI) elements (like buttons, form inputs, navigation bars, and cards) that can be mixed and matched to build web pages.
* Design System: A comprehensive suite of standards, documentation, and reusable code components. While a component library is just the collection of pieces, a design system includes the "source of truth" rules for how they should look, behave, and be used.
* Pattern Library: A collection of user interface design patterns and layout arrangements (like a login form pattern or a search layout) that combine individual components into standard layouts.
* UI Kit: Often used to describe the designer-facing side of this relationship (e.g., a library of components in Figma), but when delivered in HTML, it acts as a frontend UI kit.

## The Methodology Behind It
If your designer built this system following a strict methodology where tiny elements build into larger structures, they are likely using Atomic Design. In this framework, elements are categorized as:

* Atoms: Basic HTML building blocks (labels, inputs, buttons).
* Molecules: Simple groups of atoms functioning together (a search bar consisting of a label, input, and button).
* Organisms: Complex UI components composed of molecules and/or atoms (a global navigation header).

Are you using a specific CSS framework like Tailwind CSS, or is this a custom HTML/CSS framework built specifically for your project? I can help you find tools or best practices to manage and document these elements.

