# easyEXPRESS

This Visual Studio Code extension provides support for the [EXPRESS (ISO 10303-11)](https://www.iso.org/standard/38047.html) information modeling language.

## On this page

- [Development status](#development-status)
- [What is easyEXPRESS?](#what-is-easyexpress)
- [Current status](#current-status)
  - [Group qualifiers](#group-qualifiers)
  - [Attribute qualifiers](#attribute-qualifiers)
  - [Constructed data types resolution](#constructed-data-types-resolution)
  - [Interface specifications](#interface-specifications)
- [Code snippets](#code-snippets)
- [How to contribute?](#how-to-contribute)
- [Contact information](#contact-information)

## Development status

easyEXPRESS is currently in early stages and under active development. Expect bugs and missing features that we encourage you to document and report:

- For any problem or bug, please [create an issue](https://github.com/usnistgov/easyexpress-public/issues).
- If a similar issue has already been filed, please leave a :thumbsup:/:thumbsdown: to help us prioritze them.
- For any other kind of feedback, please [start a new discussion](https://github.com/usnistgov/easyexpress-public/discussions).

Note to STEP developers: long form and concatenated files are not supported at the moment.

## What is easyEXPRESS?

easyEXPRESS is a [Visual Studio Code](https://code.visualstudio.com/) extension that aims at providing advanced editing capabilities to [EXPRESS](https://www.iso.org/standard/38047.html) developers and help them efficiently write valid EXPRESS information models.

Advanced editing capabilities in development include:

- Syntax highlighting and validation
- [Intellisense](https://code.visualstudio.com/docs/editor/intellisense): write code faster with auto-completion
- [Code navigation](https://code.visualstudio.com/docs/editor/editingevolved): navigate your code with features such as [Go to Definition](https://code.visualstudio.com/Docs/editor/editingevolved#_go-to-definition)
- [Code refactoring](https://code.visualstudio.com/docs/editor/refactoring): refactor your code with featurs such as [Rename Symbol](https://code.visualstudio.com/docs/editor/refactoring#_rename-symbol)
- [Code snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets): write code faster with shortcuts to commonly used code patterns

## Current status


Legend:

| Mark | Description |
| --- | --- |
| 👍 | Implemented|
| 🔥 | Coming soon / in beta |
| 🏃 | Currently under development|
| 📅 | Planned |


### Group qualifiers
- [ ] 🔥 Full type graph 
- [ ] 🏃 SELECT type
- [ ] 🏃 Index qualifier
- [ ] 📆 Function call

### Attribute qualifiers
- [ ] 🔥 Direct attribute
- [ ] 🔥 From type graph
- [ ] 🏃 Index qualifier
- [ ] 📆 Function call

### Constructed data types resolution
- [x] 👍 Enumerations
- [ ] 🏃 Select data types

### Interface specifications
- [ ] 🔥 Use interface specification
- [ ] 🔥 Reference interface specification

## Code snippets

easyEXPRESS ships with the following EXPRESS [code snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets):

- `sch` to create a new schema
- `ent` to create a new entity
- `attr` to create a new attribute
- `sel2` to create a new select with 2 types
- `sel3` to create a new select with 3 types
- `fun` to create a new function
- `type` to create a new type

## How to contribute?

The best way to contribute for now is to properly document and report bugs and feature requests using the [issues](https://github.com/usnistgov/easyexpress-public/issues) and [discussions](https://github.com/usnistgov/easyexpress-public/discussions).

## Contact information

For comments or questions, you can reach out directly to:

- Sylvere Krima - sylvere.krima@nist.gov
- Allison Barnard Feeney - allison.barnardfeeney@nist.gov
- Rosemary Astheimer - rosemary.astheimer@nist.gov
