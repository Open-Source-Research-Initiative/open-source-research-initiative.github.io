# OSRI website publishing

The [organization website](https://open-source-research-initiative.github.io/) is built from the [OSRI hub](https://github.com/Open-Source-Research-Initiative/osri). The hub holds the guides, research catalogs, records, and Prism site source.

The publishing workflow reads the hub's current `main`, checks the generated pages, and deploys GitHub Pages. It runs hourly and when this repository changes. To refresh immediately, run **Publish OSRI website** from the Actions tab.

Edit the source in `osri`; generated pages are not committed here. Build instructions are in [site/README.md](https://github.com/Open-Source-Research-Initiative/osri/blob/main/site/README.md).

Original guides use CC BY 4.0. Original code and configuration use MIT. Fonts and Prism artwork retain the terms recorded in the hub's identity kit.
