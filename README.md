# jbook
Jupyter book for CC22.3

```bash

jupyter-book --help
Usage: jupyter-book [OPTIONS] COMMAND [ARGS]...

  Build and manage books with Jupyter.

Options:
  --version   Show the version and exit.
  -h, --help  Show this message and exit.

Commands:
  build   Convert your book's or page's content to HTML or a PDF.
  clean   Empty the _build directory except jupyter_cache.
  config  Inspect your _config.yml file.
  create  Create a Jupyter Book template that you can customize.
  myst    Manipulate MyST markdown files.
  toc     Command-line for sphinx-external-toc.

```

## The book building process

Building a Jupyter Book broadly consists of these steps:

Create your book’s content. You structure your book with a collection of folders, files, and configuration. See [Anatomy of a Jupyter Book](https://jupyterbook.org/en/stable/start/create.html#anatomy-of-a-book)

Build your book. Using Jupyter Book’s command-line interface you can convert your pages into either an HTML or a PDF book. See [Build your book](https://jupyterbook.org/en/stable/start/build.html).

Publish your book online. Once your book is built, you can share it with others. Most common is to build HTML, and host it as a public website. See [Publish your book online](https://jupyterbook.org/en/stable/start/publish.html).