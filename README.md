# DBML syntax highlighting and code snippets
[![Version 0.1.0 Badge][version-badge]][changelog] [![MIT License Badge][license-badge]][license]

[Database Markup Language (DBML)](https://www.dbml.org/home/) syntax highlighting and code snippets for [Atom Text Editor](https://atom.io/).

This project was made based on Visual Studio Code extension - [vscode-dbml](https://github.com/mattmeyers/vscode-dbml)
## Syntax Highlighting

Syntax highlighting is enabled for files with the `.dbml` extension.

![Syntax Example](https://raw.githubusercontent.com/nguyenalter/atom-dbml/master/screenshots/dbml-syntax-example.jpg)

## Snippets

Snippets are provided for quickly creating tables, enums, and references. To use a snippet, begin typing any of the following keys.

- Definition:
  - `project`: Create a project description
  - `table`: Create a new table
  - `tableindex`: Create a new table with an auto-incrementing int id as the primary key
  - `tablegr`: Create a table group
  - `index`: Create a new index
  - `enum`: Create a new enum
  - `column`: Create a new column

- Relationship:
  - `oto`: Create a one-to-one reference
  - `otm`: Create a one-to-many reference
  - `mto`: Create a many-to-one reference
  - `mtm`: Create a many-to-many join table

- Note:
  - `projectnote`: Create a project note
  - `tablenote`: Create a table note
  - `columnnote`: Create a column note

- Other:
  - `defval`: Create a default value
## Issues

If you find an error or bug, please [create an issue](https://github.com/nguyenalter/atom-dbml/issues/new).

## Contributing

If you want to add to this project, feel free to fork the repository and submit a pull request.