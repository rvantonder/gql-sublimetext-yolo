# gql-sublimetext-yolo

Taken from [graphql/vscode-graphql](https://github.com/graphql/vscode-graphql/blob/master/grammars/graphql.json) converted with [this](https://marketplace.visualstudio.com/items?itemName=Togusa09.tmlanguage)

**How to generate `sublime-syntax` file**:

- Open the `.json` file in sublime
- `PackageDev: Convert (YAML, JSON, PList) to and select Convert to: Property List`
- Rename as `.tmLanguage`
- `Plugin Development: Convert Syntax to .sublime-syntax`
  - Do `view console` if this doesn't work, silent failure will show why the conversion failed in console

**Testing (Mac)**:

- Put the `tmLanguage` file in:

`Users/<you>/Library/Application Support/Sublime Text 3/Packages/GraphQL/GraphQL.tmLanguage`

- Also put the test file in there, and then open it in sublime
  - Run `cmd`+`B`
