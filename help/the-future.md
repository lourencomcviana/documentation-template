# The Future

Things we want to do for making this project better

## Scaffolding

I want to be abble to point an existing repository and auto-scaffold this documentation format

- Legacy **readme** should be reased, but the user may chose to preserve it, if he choses:
  - move **readme** to the `help/legacy` folder
  - in rules section, it should be referenced as legacy documentation, example

    ``` markdown
    - [version x.y.z README.md](./help/legacy/README.md): Old readme
    ```

- in case **keep a changelog** is not being folowed
  - if exists, move **changelog** to help/legacy
  - reference the old changelog in **Changes** section marking it as legacy, example:
  
    ``` markdown
    refer to [CHANGELOG](./CHANGELOG.md) for a list of changes and versioning

    for versions bellow x.y.z, please refer to [CHANGELOG](./help/legacy/CHANGELOG.md)
    ```

- In case semantic version is not being folowed
  - A new major version shall be created marking the start where semantic versioning will be followed. It must be correcly specified in [CHANGELOG](./CHANGELOG.md) before the version creation

### Tolling

- The tool used to generate said scaffolding should work with a terminal first and maybe an website later
- It should have its own documentation following the principles discussed here
- It will ask the user a set of questions to generate the base template
- more questions can be asked for a more complete scaffolding

## Divide Tecnical issues from business issues

tecnical issues are for developers, not for business, they should link each other but they dosent need to exists in the same location.
