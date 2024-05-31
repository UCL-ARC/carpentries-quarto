# Carpentries-filters Extension For Quarto

_TODO_: Add a short description of your extension.

## Installing

```bash
quarto add milanmlft/carpentries-quarto
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

_TODO_: Describe how to use your extension.

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

## Dependencies

We use [`lustache`](https://github.com/Olivine-Labs/lustache) to handle the _mustache_ templates used by the Carpentries Workbench. A copy of `lustache` was installed locally with [LuaRocks](https://github.com/luarocks/luarocks) within this extension, using

```shell
luarocks install --tree _extensions lustache
```
