# Quering with PRQL

This is a book-style website built by Quarto and Docusaurus.

To build, we need quarto cli, node.js, R, Python, and a lot of packages!
Please check the [devcontainer.json](.devcontainer/devcontainer.json) file.
(In addition, please install the development version of the R duckdb and prqlr packages from R-universe!)

Build by

```sh
quarto render --cache-refresh
```

And deploy by

```sh
npm run deploy
```

## License

Licensed under the MIT License.
