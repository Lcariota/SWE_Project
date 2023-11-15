# Java Coding Style Guide

**Introduction**

This guide outlines the recommended coding conventions for Java development. Following these guidelines will promote clarity, organization, and collaboration within the development team.

**Table of Contents**
  + Naming Conventions
  + Indentation and Formatting
  + Comments
  + Documentation
  + Source Control Management

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
            + num = bigNum + largeNum
                    + biggerNum; 
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
    + Each statement is followed by a line break
    + Break up blocks of code as organizational and visually appealing as deemed
  + **2.5 Whitespace**
    + A single blank line may also appear anywhere it improves readability, for example between statements to organize the code into suitable subsections.
    + Also between consecutive members or initializers of a class: fields, constructors, methods, nested classes. 
    
            




