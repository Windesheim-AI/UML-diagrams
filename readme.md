# UML Diagrams Repository

This repository contains UML (Unified Modeling Language) diagrams created using PlantUML. 
PlantUML is a text-based diagramming tool that allows you to create various types of 
UML diagrams from simple textual descriptions.

## PlantUML

### What is PlantUML?

PlantUML is an open-source tool for creating UML diagrams from plain text descriptions. 
It supports various types of UML diagrams, including class diagrams, sequence diagrams, 
activity diagrams, and more. With PlantUML, you can quickly and easily create professional-looking 
diagrams using a simple text-based syntax.

### How to Use PlantUML

1. **Write UML Diagrams**: Create or edit UML diagrams using PlantUML's simple text-based syntax. PlantUML supports a variety of UML diagram types, and you can find detailed syntax documentation in the [PlantUML documentation](https://plantuml.com/). This site is very messy, but it has a lot of information. You can also find examples of PlantUML diagrams in this repository. Or Google it 😊.

2. **File Extensions**: the file extension for PlantUML diagram files is `.puml`. For example, `my-diagram.puml`.
   
3. **Commit Your Diagrams**: Commit your PlantUML diagram files (e.g., `my-diagram.puml`) to this repository. You can use Git to manage your version history.

4. **Automated SVG Generation**: A GitHub Actions workflow is set up in this repository to automatically convert your PlantUML diagrams to SVG format whenever you push changes to `.puml` files. The generated SVG files will be placed in the `render` directory.

## PlantUML Extensions

### VSCode Extension

Within VSCode, you can use the [PlantUML extension](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) to preview your PlantUML diagrams. 
This extension also provides syntax highlighting for PlantUML files.

### JetBrains Extension

Within JetBrains IDEs (e.g., IntelliJ, PyCharm, etc.), you can use the [PlantUML integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration) 
plugin to preview your PlantUML diagrams. This plugin also provides syntax highlighting for PlantUML 
files.
