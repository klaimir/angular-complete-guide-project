# Project notes

This document describes relevants notes for Recipes and Shop list project and its implementation.


# Section 3: Course Project - The Basics

## Project Introduction

## Planning the App

### Funcionality
- Recipe Book
- Shooping List 

### Components
- Root
- Header
- Shooping List:
  - Shopping List.
  - Shopping List Edit.
- Recipe Book:
  - Recipe List.
  - Recipe Item.
  - Recipe Detail.

### Models
- Shooping List:
  - Ingredient.
- Recipe Book:
  - Recipe.

## Installing Bootstrap Correctly

In the next lecture, we set up the course project. For that, we'll install the Bootstrap CSS Framework.

In this course, we use version 3 of the framework, install it via npm install --save bootstrap@3  => The @3  is important!

Additionally, when using a project created with Angular CLI 6+ (check via ng v ), you'll have an angular.json  file instead of an .angular-cli.json file. In that file, you still need to add Bootstrap to the styles[]  array as shown in the next video, but the path should be node_modules/bootstrap/dist/css/bootstrap.min.css , NOT ../node_modules/bootstrap/dist/css/bootstrap.min.css . The leading ../  must not be included.

Also see this lecture - I do show the complete setup process there: https://www.udemy.com/the-complete-guide-to-angular-2/learn/v4/t/lecture/6655614/

If you're facing any problems, please have a look at this very thorough thread by Jost: https://www.udemy.com/course/the-complete-guide-to-angular-2/learn/lecture/17862130#questions/10444944

!IMPORTANT! For this project, we are going to use Bootstrap 4 due to this is the current stable version.

## Setting up the Application

## Creating the Components

The objective is creating a folder structure (or scafolding) for the project.

Could be useful creating manually the first component to practice. But, I definitivaly recomment the CLI.

ng g c --skipTests true (If component name is not indicated, a prompt shows an option to write the component name).

We´re going to organize folder by feature.

## Using the components

## Adding a navigation bar

We´re going to use the default bar.

## Alternative Non-Collapsable Navigation Bar

## Creating a "Recipe" Model

## Adding Content to the Recipes Components

## Outputting a List of Recipes with ngFor

You can use the interpolation operator for attributes in HTML components, but it more correct to use one-way-binding


