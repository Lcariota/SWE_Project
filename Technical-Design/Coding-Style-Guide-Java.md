# Java Coding Style Guide

Welcome to the Java Coding Style Guide! This document serves as a comprehensive set of guidelines and conventions for writing clean, readable, and maintainable Java code. Adhering to these standards not only enhances individual and team productivity but also contributes to the overall quality of our software.

The primary purpose of this coding style guide is to establish a consistent coding style across our projects. Consistency is crucial for better collaboration among team members, as it minimizes confusion and improves the overall readability of the codebase. By following these guidelines, we aim to create code that is easy to understand, maintain, and extend.

## Table of Contents
  + [Naming Conventions](#naming-conventions)
  + [Indentation and Formatting](#indentation-and-formatting)
  + [Comments](#comments)
  + [Organization](#organization)
  + [Source Control Management](#source-control-management)

## Naming Conventions
  + **1.1 CamelCase**
      + Java class, field, method, and variable names follow the CamelCase convention, where words are concatenated, and the initial letter of each word is capitalized.
      + For variable names the first letter should remain lowercase.
          + Variable names should provide insight into their purpose. Opting for well-chosen names that hint at the variable's meaning contributes to effective program documentation. Avoid vague names like "var" or "num" and opt for more specific and descriptive names.
              + EX: String studentGrades
      + There's an exception for constants, which are written in all caps with underscores, and they are often declared as static and final.
          + private final int MAX = 50;
  + **1.2 Class and Interface Names**
      + Class and interface names should begin with a capital letter and follow CamelCase conventions.
          + public class TestPalindrome
  + **1.3 Method Names**
      + Method names begin with a lowercase letter.
          + public void setHeight( int h )
  + **1.5 Package Names**
    + Package names are written in all lowercase and typically consist of nouns.

## Indentation and Formatting
  + **2.1 Line Length**
    + Avoid lines longer than 80 characters for better readability
    + When an expression will not fit on a single line, break it according to these general principles:
        + Break after operator
        + Align the new line with the beginning of the original expression
    + Line wrapping for if statements should generally use the 8-space rule
  + **2.2 Use of Braces**
    + Braces are used with if, else, for, do, and while statements
        + Optional if statement is only one line
    + Empty blocks may be closed immediately after being opened
        + void doNothing() {}
  + **2.3 Block Indentation**
    + Each time a new block is made, the indent increases by two spaces. When the block ends, the indent returns to the previous indent level. The indent level applies to both code and comments throughout the block.
  + **2.4 One Statement per Line**
    + One declaration per line
        + DONT DO THIS int level, size; 
    + Each statement is followed by a line break
    + Break up blocks of code as organizational and visually appealing as deemed
  + **2.5 Whitespace**
    + A single blank line may also appear anywhere it improves readability, for example between statements to organize the code into suitable subsections.
    + Also between consecutive members or initializers of a class: fields, constructors, methods, nested classes.

## Comments
  + **3.1 When to Use**
     + Comments should not duplicate the code but rather dispel confusion and further explain the piece of code if confusing.
         + Programs can have 3 styles of comments: block, single-line, trailing
  + **3.2 Block Comments**
     + Block comments should be used at the beginning of each file and before each method.
        + Block comments can start with /*
            + /*
            + * Here is a block comment.
            + */
  + **3.3 Single Line Comments**
    + Short comments can appear on a single line indented to the level of the code that follows.
        + // This is an if statement
        + if ( x == y) {}
  + **3.4 Trailing Comments**
      + Very short comments can appear on the same line as the code they describe but should be shifted far enough to separate them from the statements.
          + int grade = 90;       // initializes a grade

## Organization 
  + **4.1 Field and Class variable declarations**
      + Place all field and class (static) variables at the beginning of a class, before all the methods.
  + **4.2 Method Length**
      + Keep methods between 20-50 lines
          + If over 50 put some functionality into another method
      + A long method body should generally be broken into a sequence of logical units, each performing some subtask.
          + Each of these logical units needs a comment that describes what the unit does.
          + // Do b
          + implementation of "Do b"
   
            
          + // Do c
          + implementation of "Do c"
   
            
          + // Do d
          + implementation of "Do d

  + **4.3 Declare Local Variables Close to Use**
      + Declare a variable as close to its first use as possible.
  + **4.4 Public/Private Access Modifiers**
      + public: Public items can be used anywhere.
      + private: Private items can be referred to only in code within the class.
          + Should be declared private if we don't want users to access them
              + private boolean administrator
      + protected: Protected components can be referenced within the class, within subclasses, and within any class defined in the same package.

## Source Control Management
  + **5.1 Repository Organization Using Git**
      + Single Repository: Each project should have a dedicated Git repository.
      + Logical Structure: Organize the repository logically, with separate directories for source code, documentation, and resources.
  + **5.2 Branching Strategy**
      + **GitFlow**: Adopt the GitFlow branching strategy for development, testing, and release branches.
          + main: Represents the production-ready code.
          + develop: Integration branch for ongoing development.
          + feature/: Prefix for feature branches.
          + bugfix/: Prefix for bug-fix branches.
          + release/: Prefix for release branches.
          + hotfix/: Prefix for hotfix branches.
  + **5.3 Collaboration**
      + Pull Before Push: Always pull changes from the remote repository before pushing to avoid conflicts.
      + Code Review: Enforce a code review process for all pull requests.
      + Continuous Integration (CI): Integrate CI tools to automatically build and test code on each push.
  + **5.4 Documentation**
      + README.md: Include a well-documented README.md file providing an overview, setup instructions, and any other relevant information.
    
            




