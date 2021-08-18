# Writing Clean Code

- ### Use meaningful code

  - Be descriptive and imply type;
  - Use verbs for functions and nouns for variables;
  - Don't use abreviations;
  - Be consistent but clearly differentiate.

- ### Use whitespace properly

  - Two whitespace from functions;
  - Two whitespace from imports;
  - Limit lines for 79 charactes (PEP8).

</br>

# Writing Modular Code 

- ### DRY (Don't repeat yourself) - refactor;
- ### Abstract out logic to improve readability;
- ### Minimize the number of entities (functions, classes, modules, etc) - optimize;
- ### Functions should do one thing;
- ### Try to use fewer than three arguments per function.

</br>

# Documentation
- ### Project documentation should be writing in README.md;
- ### Inline comments should be used when code is difficult to understand (business rules);
- ### Docstrings should be used to document functions and methods.

</br>

# Auto PEP-8 & Linting
- ### `pylint script_name.py` will provide updates to make to code;
- ### `autopep8 --in-place --aggressive --aggressive script_name.py` will attempt to automatically clean up the code.