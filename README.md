# make toturial

### basic
- The make program is intended to automate the mundance aspects of transforming source code into executable.
- Advantanges of make over script is you can specify the relationships between the elements of your program to make.Using this information, make can also optimize the build process avoiding unnecessary steps.
- Make defines a language for describing the relationships between source code,intermediate files, and executables.Features: manage alternate configurations,implement resuable libraries of spicifications.parameterize process with user-defined macros.
- Make can be considered the center of the development process by providing a roadmap of an application's components and how they fit together.
- The makefile tells make how to compile and link a program.
- A simple makefile consists of "rules" with the following shape:

    target ... : prerequistites ...

        recipe
        ...
        ...

- If a target is included as a command-line argument,that target is updated.If no command-line targets are given,then the first target in the file is used,called the default goal.
- A target is usually the name of a file or the name of an action to carry out.
- A prerequistite is a file that is used as input to create the target.
- A recipe is an action that make carries out.
- A rule explains how and when to remake certain files and can also explain how and when to carry out an action.



### rules
### variables and macro
### functions
### commands
