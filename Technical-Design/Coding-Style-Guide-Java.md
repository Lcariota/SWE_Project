# Java Coding Style Guide

**Introduction**

This guide outlines the recommended coding conventions for Java development. Following these guidelines will promote clarity, organization, and collaboration within the development team.

**Table of Contents**
  + Naming Conventions
  + Indentation and Formatting
  + Documentation
  + Formatting 
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
            




