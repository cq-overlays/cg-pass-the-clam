# `cq-pass-the-clam`
> graphics and dashboard controls for InkTV's "Pass the Clam".

> ![Preview](preview.png)

## usage
1. Find the version you're looking for on the releases page, and download `cq-pass-the-clam.zip`.
1. Unzip the file and drag the folder into the `bundles/` subdirectory of your NodeCG installation.
    - If you need a remote server, read: [How to set up a remote NodeCG instance for free](https://gist.github.com/LeptoFlare/70cd494e4562b7473fdb89029a4d6a87)

## local setup
1. Clone the repository into the `bundles/` subdirectory of your NodeCG installation.
1. `npm run watch` will build the bundle for NodeCG and watch for changes.
1. To build graphics for production:
    1. `npm run build --mode graphics`
    1. `npm run build --mode dashboard`
    1. Delete everything except for the `graphics/`, `dashboard/` directory and `package.json`.

---

*empathy included • [**@cysabi**](https://github.com/cysabi) • [cysabi.github.io](https://cysabi.github.io)*
