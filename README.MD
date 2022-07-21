# Teletron Extensions

This repository contains all available extensions downloadable for [teletron](https://www.teletron.me).

## Contributing

To contribute an extension, create a Pull Request. No need to update the `index.json`, it will be automatically
updated by a github workflow when the PR is accepted.

The requirements that need to be adhered to are (where {name} is the name you choose for your extension.):

1. Choose a unique extension-{name} name and place the files in the folder.
2. Place the extension `package.json` in the root of the folder, make sure that an `teletron` attribute is present with the required attributes.
3. Place a README.MD file in the root of the folder, its contents will be included in the search index.
4. The extension itself must be compressed in a filename `{name}.tar.gz`, this will installed to your Teletron environment.
