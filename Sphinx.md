Sphinx documentation 

[![logo](_static/sphinx-logo.svg)](#)

Sphinx
======

### Navigation

*   [Documentation](#) »
*   Welcome

 document.getElementById('searchbox').style.display = "block"

### On this page

*   [Welcome](#)
    *   [Get started](#get-started)
    *   [User Guides](#user-guides)
    *   [Community guide](#community-guide)
    *   [Reference guide](#reference-guide)

### Site navigation

Get started

*   [Getting Started](usage/quickstart.html)
*   [Installing Sphinx](usage/installation.html)
*   [Tutorial: Build your first project](tutorial/index.html)

User Guides

*   [Using Sphinx](usage/index.html)
*   [Writing Sphinx Extensions](development/index.html)
*   [LaTeX customization](latex.html)
*   [Sphinx Extensions API](extdev/index.html)

Community

*   [Get support](support.html)
*   [Contribute to Sphinx](internals/index.html)
*   [Sphinx FAQ](faq.html)
*   [Sphinx authors](authors.html)

Reference

*   [Command-Line Tools](man/index.html)
*   [Configuration](usage/configuration.html)
*   [Extensions](usage/extensions/index.html)
*   [reStructuredText](usage/restructuredtext/index.html)
*   [Glossary](glossary.html)
*   [Changelog](changes.html)
*   [Projects using Sphinx](examples.html)

Welcome[¶](#welcome "Link to this heading")
===========================================

> Sphinx makes it easy to create intelligent and beautiful documentation.

Here are some of Sphinx’s major features:

*   **Output formats:** HTML (including Windows HTML Help), LaTeX (for printable PDF versions), ePub, Texinfo, manual pages, plain text
    
*   **Extensive cross-references:** semantic markup and automatic links for functions, classes, citations, glossary terms and similar pieces of information
    
*   **Hierarchical structure:** easy definition of a document tree, with automatic links to siblings, parents and children
    
*   **Automatic indices:** general index as well as a language-specific module indices
    
*   **Code handling:** automatic highlighting using the [Pygments](https://pygments.org/) highlighter
    
*   **Extensions:** automatic testing of code snippets, inclusion of docstrings from Python modules (API docs) via [built-in extensions](usage/extensions/index.html#builtin-extensions), and much more functionality via [third-party extensions](usage/extensions/index.html#third-party-extensions).
    
*   **Themes:** modify the look and feel of outputs via [creating themes](development/theming.html), and reuse many [third-party themes](usage/theming.html#third-party-themes).
    
*   **Contributed extensions:** dozens of extensions [contributed by users](usage/extensions/index.html#third-party-extensions); most of them installable from PyPI.
    

Sphinx uses the [reStructuredText](https://docutils.sourceforge.io/rst.html) markup language by default, and can read [MyST markdown](usage/markdown.html#markdown) via third-party extensions. Both of these are powerful and straightforward to use, and have functionality for complex documentation and publishing workflows. They both build upon [Docutils](https://docutils.sourceforge.io/) to parse and write documents.

See below for how to navigate Sphinx’s documentation.

See also

The [Sphinx documentation Table of Contents](contents.html) has a full list of this site’s pages.

Get started[¶](#get-started "Link to this heading")
---------------------------------------------------

These sections cover the basics of getting started with Sphinx, including creating and building your own documentation from scratch.

Get started

*   [Getting Started](usage/quickstart.html)
    *   [Setting up the documentation sources](usage/quickstart.html#setting-up-the-documentation-sources)
    *   [Defining document structure](usage/quickstart.html#defining-document-structure)
    *   [Adding content](usage/quickstart.html#adding-content)
    *   [Running the build](usage/quickstart.html#running-the-build)
    *   [Documenting objects](usage/quickstart.html#documenting-objects)
    *   [Basic configuration](usage/quickstart.html#basic-configuration)
    *   [Autodoc](usage/quickstart.html#autodoc)
    *   [Intersphinx](usage/quickstart.html#intersphinx)
    *   [More topics to be covered](usage/quickstart.html#more-topics-to-be-covered)
*   [Installing Sphinx](usage/installation.html)
    *   [Overview](usage/installation.html#overview)
    *   [Linux](usage/installation.html#linux)
    *   [macOS](usage/installation.html#macos)
    *   [Windows](usage/installation.html#windows)
    *   [Installation from PyPI](usage/installation.html#installation-from-pypi)
    *   [Docker](usage/installation.html#docker)
    *   [Installation from source](usage/installation.html#installation-from-source)
*   [Tutorial: Build your first project](tutorial/index.html)
    *   [Getting started](tutorial/getting-started.html)
    *   [First steps to document your project using Sphinx](tutorial/first-steps.html)
    *   [More Sphinx customization](tutorial/more-sphinx-customization.html)
    *   [Narrative documentation in Sphinx](tutorial/narrative-documentation.html)
    *   [Describing code in Sphinx](tutorial/describing-code.html)
    *   [Automatic documentation generation from code](tutorial/automatic-doc-generation.html)
    *   [Appendix: Deploying a Sphinx project online](tutorial/deploying.html)
    *   [Where to go from here](tutorial/end.html)

User Guides[¶](#user-guides "Link to this heading")
---------------------------------------------------

These sections cover various topics in using and extending Sphinx for various use-cases. They are a comprehensive guide to using Sphinx in many contexts and assume more knowledge of Sphinx. If you are new to Sphinx, we recommend starting with [Get started](#get-started).

User Guides

*   [Using Sphinx](usage/index.html)
    *   [reStructuredText](usage/restructuredtext/index.html)
    *   [Markdown](usage/markdown.html)
    *   [Cross-referencing syntax](usage/referencing.html)
    *   [Configuration](usage/configuration.html)
    *   [Builders](usage/builders/index.html)
    *   [Domains](usage/domains/index.html)
    *   [Extensions](usage/extensions/index.html)
    *   [HTML Theming](usage/theming.html)
    *   [Internationalization](usage/advanced/intl.html)
    *   [Sphinx Web Support](usage/advanced/websupport/index.html)
*   [Writing Sphinx Extensions](development/index.html)
    *   [Developing extensions overview](development/overview.html)
    *   [Extension tutorials](development/tutorials/index.html)
    *   [Configuring builders](development/builders.html)
    *   [Templating](development/templating.html)
    *   [HTML theme development](development/theming.html)
*   [LaTeX customization](latex.html)
    *   [The `latex_elements` configuration setting](latex.html#the-latex-elements-configuration-setting)
    *   [The `sphinxsetup` configuration setting](latex.html#the-sphinxsetup-configuration-setting)
    *   [Additional CSS-like `'sphinxsetup'` keys](latex.html#additional-css-like-sphinxsetup-keys)
    *   [LaTeX macros and environments](latex.html#latex-macros-and-environments)
*   [Sphinx Extensions API](extdev/index.html)
    *   [Important objects](extdev/index.html#important-objects)
    *   [Build Phases](extdev/index.html#build-phases)
    *   [Extension metadata](extdev/index.html#extension-metadata)
    *   [APIs used for writing extensions](extdev/index.html#apis-used-for-writing-extensions)

Community guide[¶](#community-guide "Link to this heading")
-----------------------------------------------------------

Sphinx is community supported and welcomes contributions from anybody. The sections below should help you get started joining the Sphinx community as well as contributing.

See the [Sphinx contributors’ guide](internals/contributing.html) if you would like to contribute to the project.

Community

*   [Get support](support.html)
*   [Contribute to Sphinx](internals/index.html)
    *   [Contributing to Sphinx](internals/contributing.html)
    *   [Sphinx’s release process](internals/release-process.html)
    *   [Organization of the Sphinx project](internals/organization.html)
    *   [Sphinx Code of Conduct](internals/code-of-conduct.html)
*   [Sphinx FAQ](faq.html)
    *   [How do I…](faq.html#how-do-i)
    *   [Using Sphinx with…](faq.html#using-sphinx-with)
    *   [Sphinx vs. Docutils](faq.html#sphinx-vs-docutils)
    *   [Epub info](faq.html#epub-info)
    *   [Texinfo info](faq.html#texinfo-info)
*   [Sphinx authors](authors.html)
    *   [Maintainers](authors.html#maintainers)
    *   [Contributors](authors.html#contributors)
    *   [Former maintainers](authors.html#former-maintainers)

Reference guide[¶](#reference-guide "Link to this heading")
-----------------------------------------------------------

Reference documentation is more complete and programmatic in nature, it is a collection of information that can be quickly referenced. If you would like usecase-driven documentation, see [Get started](#get-started) or [User Guides](#user-guides).

Reference

*   [Command-Line Tools](man/index.html)
    *   [Core Applications](man/index.html#core-applications)
    *   [Additional Applications](man/index.html#additional-applications)
*   [Configuration](usage/configuration.html)
    *   [Project information](usage/configuration.html#project-information)
    *   [General configuration](usage/configuration.html#general-configuration)
    *   [Options for internationalization](usage/configuration.html#options-for-internationalization)
    *   [Options for Math](usage/configuration.html#options-for-math)
    *   [Options for HTML output](usage/configuration.html#options-for-html-output)
    *   [Options for Single HTML output](usage/configuration.html#options-for-single-html-output)
    *   [Options for HTML help output](usage/configuration.html#options-for-html-help-output)
    *   [Options for Apple Help output](usage/configuration.html#options-for-apple-help-output)
    *   [Options for epub output](usage/configuration.html#options-for-epub-output)
    *   [Options for LaTeX output](usage/configuration.html#options-for-latex-output)
    *   [Options for text output](usage/configuration.html#options-for-text-output)
    *   [Options for manual page output](usage/configuration.html#options-for-manual-page-output)
    *   [Options for Texinfo output](usage/configuration.html#options-for-texinfo-output)
    *   [Options for QtHelp output](usage/configuration.html#options-for-qthelp-output)
    *   [Options for the linkcheck builder](usage/configuration.html#options-for-the-linkcheck-builder)
    *   [Options for the XML builder](usage/configuration.html#options-for-the-xml-builder)
    *   [Options for the C domain](usage/configuration.html#options-for-the-c-domain)
    *   [Options for the C++ domain](usage/configuration.html#cpp-config)
    *   [Options for the Python domain](usage/configuration.html#options-for-the-python-domain)
    *   [Options for the Javascript domain](usage/configuration.html#options-for-the-javascript-domain)
    *   [Example of configuration file](usage/configuration.html#example-of-configuration-file)
*   [Extensions](usage/extensions/index.html)
    *   [Built-in extensions](usage/extensions/index.html#built-in-extensions)
    *   [Third-party extensions](usage/extensions/index.html#third-party-extensions)
*   [reStructuredText](usage/restructuredtext/index.html)
    *   [reStructuredText Primer](usage/restructuredtext/basics.html)
    *   [Roles](usage/restructuredtext/roles.html)
    *   [Directives](usage/restructuredtext/directives.html)
    *   [Field Lists](usage/restructuredtext/field-lists.html)
*   [Glossary](glossary.html)
*   [Changelog](changes.html)
*   [Projects using Sphinx](examples.html)
    *   [Documentation using the alabaster theme](examples.html#documentation-using-the-alabaster-theme)
    *   [Documentation using the classic theme](examples.html#documentation-using-the-classic-theme)
    *   [Documentation using the sphinxdoc theme](examples.html#documentation-using-the-sphinxdoc-theme)
    *   [Documentation using the nature theme](examples.html#documentation-using-the-nature-theme)
    *   [Documentation using another builtin theme](examples.html#documentation-using-another-builtin-theme)
    *   [Documentation using sphinx\_rtd\_theme](examples.html#documentation-using-sphinx-rtd-theme)
    *   [Documentation using sphinx\_bootstrap\_theme](examples.html#documentation-using-sphinx-bootstrap-theme)
    *   [Documentation using pydata\_sphinx\_theme](examples.html#documentation-using-pydata-sphinx-theme)
    *   [Documentation using a custom theme or integrated in a website](examples.html#documentation-using-a-custom-theme-or-integrated-in-a-website)
    *   [Homepages and other non-documentation sites](examples.html#homepages-and-other-non-documentation-sites)
    *   [Books produced using Sphinx](examples.html#books-produced-using-sphinx)
    *   [Theses produced using Sphinx](examples.html#theses-produced-using-sphinx)
    *   [Projects integrating Sphinx functionality](examples.html#projects-integrating-sphinx-functionality)

© Copyright 2007-2024, the Sphinx developers. Created using [Sphinx](https://www.sphinx-doc.org/) 7.3.0.
