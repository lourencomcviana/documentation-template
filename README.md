# Documentation Template

Briefly describe what the project is and what it does.

The introduction **may** have one image that represents the project

## Changes

refer to [CHANGELOG](./CHANGELOG.md) for a list of changes and versioning

## Rules

Here wer have a **list of links** that explains in detail what the project is and does. In an more human format. Some help links are here too

links for documents containing images for the architetural structure of this project
must be references and not polute the main document

- [why this project](./help/business-rules/why-this-project.md): explanation about things in this project
- [How to make a changelog](https://keepachangelog.com/en/1.0.0/): important to track changes
- [How to version my project](https://semver.org/): important to identify and maintain evolutions clearly  
- [what is markdown?](https://www.markdownguide.org/getting-started/)
- [project documentation](https://github.com/lourencomcviana/documentation-template): a set of instructions explaining how to maintain the documentation for this project

## Dependencies

a list of dependencies needed to run the project

### Minimun

this list contain the minimal itens for runing the project in some way, for example, the minimum to run tests or with mocks.

- markdown reader: this project needs an application that can interpret markdown
- [setting up an envrionment](./help/markdown-envrionment.md): a set of instructions that will help you with your envrionment

### Recomended

- [vscode](https://code.visualstudio.com/): a good tool to edit and view markdown
  - [markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one): a plugin that put some rules for writing markdown
  - [markdown lint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint): a plugin that put some rules for writing markdow

## Execution

This is the most important session for a developer. As a new developer in a project, i want to be abble to run it easely and without doubts.

### with minimum specs

explain here the limitatins of minimun spec for your project

- using windows
- open file explorer
- right click on the README.md and
- select open with
- choose notepad

### with recomeded specs

remember you can link other markdowns if the execution steps are to long or need grafical representation (images)

- open vscode
- click in file
- select open folder
- choose the folder where this project is contained

## publishing

How to publish this project in each envirionment

### GitHub

on a terminal run:

``` bash
git add .
git commit -m "your commit message"
git push
```

## References

A table of projects that this project needs to funcion in this or other envrionments.
Integrations are a necessity in this day and age.

You may organize the subtopics of this session, naming should be something 

### Web Environment

Remember, table descriptions should be very short, in the Scope field you can use a legend, for example:

``` markdown
- **INFRA**: infrastructure projects are projects meant to create the needed infrastructure for this project to run
- **API**: one api that this project must consume
- **TEMPLATE**: just an example
```

Project should be, in fact, an id for that project, a person should be abble to use this name to search for it in repositories, or running environment for example

|           project            | Description | Scope |
| ---------------------------- | ----------- | ----- |
| [documentation-template](https://github.com/lourencomcviana/documentation-template/blob/main/README.md) | make it possible to create documentation projects | **EXAMPLE** |

## Other references

a list of any other needed references, can contain references to others internal documentation or anything realy. Just don't bload it with text, just list of links. remember to explain why this exception in the documentation

- [the future](./help/the-future.md)
