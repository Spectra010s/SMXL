
SMXL – A New Programming Language / Markup Language

Version 1.0

SMXL is a new, experimental markup language designed to simplify web page creation while introducing a new way of thinking about structure and layout. Think of it as a next-generation HTML, with cleaner tags, nested “boxes,” and easy-to-read notes.


Features

Simple, intuitive syntax: (note1), (box), (text) instead of h1, div, p

Nested boxes for clear content hierarchy

SMXL → HTML conversion works in modern browsers (Chrome, Firefox, Edge)

Placeholder for future SMXL-native editors that recognize the language

Inspired by the vision of building a new coding ecosystem


Current Status

✅ SMXL parser converts .smxl files to HTML

✅ Compatible with major browsers

⚠️ Currently requires a runner or browser environment to render .smxl

⚠️ VS Code or other editors do not natively recognize SMXL yet


How to Use (Today)

1. Create a .smxl file (example: index.smxl) using any text editor.


2. Open the provided runner script in your browser to render SMXL.


3. Enjoy your structured SMXL page!



> Example index.smxl:


(smxl version="1.0")
(top)
    (title)Hello SMXL(/title)
(/top)
(body)
    (note1)Welcome to SMXL!(/note1)
    (box)
        (note2)Nested Note(/note2)
        (text)This is some text inside a box(/text)
    (/box)
(/body)
(/smxl)


Future Vision

Build a custom coding editor that:

Recognizes SMXL syntax

Supports other languages like HTML, CSS, JS, Node.js

Works on phones, laptops, and desktops


Provide a complete ecosystem for SMXL coding and running

Make SMXL more than just a language—a new world for coding



Contributing

SMXL is in early stages. We welcome collaborators to help with:

Improving the parser and runner

Adding syntax highlighting for existing editors

Building the future SMXL editor

Documentation, tutorials, and examples


If you want to join the team, reach out or submit a pull request. Let’s build this new world together 🌎✨
