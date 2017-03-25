# Welcome to MkDocs

For full documentation visit [mkdocs.org](http://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

!!! warning

    You should never edit files in your gh-pages branch by hand if you're using
    the `gh-deploy` command because you will lose your work.

[GitHub]: https://github.com/
[GitHub Pages]: https://pages.github.com/
[ghp-import]: https://github.com/davisp/ghp-import

## Read the Docs

[Read the Docs][rtd] offers free documentation hosting. You can import your docs
using any major version control system, including Mercurial, Git, Subversion,
and Bazaar. Read the Docs supports MkDocs out-of-the-box. Follow the
[instructions] on their site to arrange the files in your repository properly,
create an account and point it at your publicly hosted repository. If properly
configured, your documentation will update each time you push commits to your
public repository.

!!! note

    To benefit from all of the [features] offered by Read the Docs, you will need
    to use the [Read the Docs theme][theme] which ships with MkDocs. The various
    themes which may be referenced in Read the Docs' documentation are Sphinx
    specific themes and will not work with MkDocs.

[rtd]: https://readthedocs.org/
[instructions]: https://read-the-docs.readthedocs.io/en/latest/getting_started.html#in-markdown
[features]: http://read-the-docs.readthedocs.io/en/latest/features.html
[theme]: /user-guide/styling-your-docs.md
