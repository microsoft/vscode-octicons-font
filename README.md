# vscode-octicons-font

### Intro
This tool was created to convert [GitHub Octicons](https://github.com/primer/octicons/tree/master/lib/octicons_node) into  an icon font using the [icon-font-generator](https://github.com/Workshape/icon-font-generator). This also adds a few custom icons from previous versions under `src > icons`. The mappings of the unicode characters are store under `src/template/mapping.json` as well as the default styles under `src/template/styles.hbs`.

### Install

```
npm install
```

### Build

```
npm run build
```

Output will be exported to a `dist` folder.

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
