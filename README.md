# Some Gradle utilities that I have lying around.

That is all.

## Install

The create-projects.gradle script should be placed like so:

    ~/.gradle/init.d/create-projects.gradle

This will enable the tasks createSingleProject (cSP), createMultiProject (cMP) 
and addMultiProject (aMP) in all projects.

## Usage

Using the tasks is easy:

### Creating a single project

    gradle [createSingleProject | cSP]

### Creating a multi-project project

    gradle [createMultiProject | cMP] -DcreateNames=<proj1>,<proj2>

### Adding a sub-project to an existing multi-project

    gradle [addMultiProject | aMP] -DprojName=<subproj>


