myst-docutils 2.0.0
===================

pip install myst-docutils Copy PIP instructions

[Latest version](/project/myst-docutils/)

Released: Jun 13, 2023

An extended \[CommonMark\](https://spec.commonmark.org/) compliant parser,

### Navigation

*   [Project description](#description)
*   [Release history](#history)
*   [Download files](#files)

### Project links

*   [Documentation](https://myst-parser.readthedocs.io)
*   [Homepage](https://github.com/executablebooks/MyST-Parser)

### Statistics

GitHub statistics:

*   **Stars:**
*   **Forks:**
*   **Open issues:**
*   **Open PRs:**

View statistics for this project via [Libraries.io](https://libraries.io/pypi/myst-docutils "External link"), or by using [our public dataset on Google BigQuery](https://packaging.python.org/guides/analyzing-pypi-package-downloads/)

### Meta

**License:** MIT License

**Author:** [Chris Sewell](mailto:chrisj_sewell@hotmail.com)

Tags markdown, lexer, parser, development, docutils, sphinx

**Requires:** Python >=3.8

### Maintainers

 [![Avatar for cjsewell from gravatar.com](https://pypi-camo.freetls.fastly.net/9564ca70d4f0bc5f3fba79f8b0dcbe2cbd64cefa/68747470733a2f2f7365637572652e67726176617461722e636f6d2f6176617461722f33363330333837303162666463396263326330313030326436333462303365373f73697a653d3530 "Avatar for cjsewell from gravatar.com")cjsewell](/user/cjsewell/)

### Classifiers

*   **Development Status**
    *   [4 - Beta](/search/?c=Development+Status+%3A%3A+4+-+Beta)
*   **Framework**
    *   [Sphinx :: Extension](/search/?c=Framework+%3A%3A+Sphinx+%3A%3A+Extension)
*   **Intended Audience**
    *   [Developers](/search/?c=Intended+Audience+%3A%3A+Developers)
*   **License**
    *   [OSI Approved :: MIT License](/search/?c=License+%3A%3A+OSI+Approved+%3A%3A+MIT+License)
*   **Programming Language**
    *   [Python :: 3](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3)
    *   [Python :: 3 :: Only](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3+%3A%3A+Only)
    *   [Python :: 3.8](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3.8)
    *   [Python :: 3.9](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3.9)
    *   [Python :: 3.10](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3.10)
    *   [Python :: 3.11](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3.11)
    *   [Python :: Implementation :: CPython](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+CPython)
    *   [Python :: Implementation :: PyPy](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+PyPy)
*   **Topic**
    *   [Software Development :: Libraries :: Python Modules](/search/?c=Topic+%3A%3A+Software+Development+%3A%3A+Libraries+%3A%3A+Python+Modules)
    *   [Text Processing :: Markup](/search/?c=Topic+%3A%3A+Text+Processing+%3A%3A+Markup)

*   [Project description](#description)
*   [Project details](#data)
*   [Release history](#history)
*   [Download files](#files)

Project description
-------------------

MyST-Parser
===========

Note: myst-docutils is identical to myst-parser, but without installation requirements on sphinx

[![Github-CI](https://pypi-camo.freetls.fastly.net/43d327b922d63be56e794e3a2395f81b10bd2294/68747470733a2f2f6769746875622e636f6d2f65786563757461626c65626f6f6b732f4d7953542d5061727365722f776f726b666c6f77732f636f6e74696e756f75732d696e746567726174696f6e2f62616467652e7376673f6272616e63683d6d6173746572)](https://github.com/executablebooks/MyST-Parser) [![Coverage Status](https://pypi-camo.freetls.fastly.net/78bc2e245d3b96503459cdec7d413824e94baee4/68747470733a2f2f636f6465636f762e696f2f67682f65786563757461626c65626f6f6b732f4d7953542d5061727365722f6272616e63682f6d61737465722f67726170682f62616467652e737667)](https://codecov.io/gh/executablebooks/MyST-Parser) [![Documentation Status](https://pypi-camo.freetls.fastly.net/6e366c54033427aa71f74a1f33a45ecec9f3532c/68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f6d7973742d7061727365722f62616467652f3f76657273696f6e3d6c6174657374)](https://myst-parser.readthedocs.io/en/latest/?badge=latest) [![Code style: black](https://pypi-camo.freetls.fastly.net/fbfdc7754183ecf079bc71ddeabaf88f6cbc5c00/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f64652532307374796c652d626c61636b2d3030303030302e737667)](https://github.com/ambv/black) [![PyPI](https://pypi-camo.freetls.fastly.net/301f113ed56fdb5ced167ce0a40dc55efc2c6b87/68747470733a2f2f696d672e736869656c64732e696f2f707970692f762f6d7973742d646f637574696c732e737667)](https://pypi.org/project/myst-docutils) [![Conda](https://pypi-camo.freetls.fastly.net/68e2e917b62d34f021bd5820058c1367850f2e0d/68747470733a2f2f616e61636f6e64612e6f72672f636f6e64612d666f7267652f6d7973742d646f637574696c732f6261646765732f76657273696f6e2e737667)](https://anaconda.org/conda-forge/myst-docutils) [![PyPI - Downloads](https://pypi-camo.freetls.fastly.net/b7edc0898d52e231dd67d8f3bba0455e21feb1b0/68747470733a2f2f696d672e736869656c64732e696f2f707970692f64772f6d7973742d646f637574696c733f6c6162656c3d70797069253230696e7374616c6c73)](https://pypistats.org/packages/myst-docutils)

**MyST is a rich and extensible flavor of Markdown meant for technical documentation and publishing**.

MyST is a flavor of markdown that is designed for simplicity, flexibility, and extensibility. This repository serves as the reference implementation of MyST Markdown, as well as a collection of tools to support working with MyST in Python and Sphinx. It contains an extended [CommonMark](https://commonmark.org)\-compliant parser using [`markdown-it-py`](https://markdown-it-py.readthedocs.io/), as well as a [Sphinx](https://www.sphinx-doc.org) extension that allows you to write MyST Markdown in Sphinx.

[**See the MyST Parser documentation for more information**](https://myst-parser.readthedocs.io/en/latest/).

Installation
------------

To install the MyST parser, run the following in a [Conda environment](https://docs.conda.io) (recommended):

conda install \-c conda-forge myst-docutils

or

pip install myst-docutils

Or for package development:

git clone https://github.com/executablebooks/MyST-Parser
cd MyST-Parser
git checkout master
pip install \-e .\[code\_style,testing,rtd\]

To use the MyST parser in Sphinx, simply add: `extensions = ["myst_parser"]` to your `conf.py`.

Contributing
------------

We welcome all contributions! See the [Contributing Guide](https://myst-parser.readthedocs.io/en/latest/develop/index.html) for more details.

Project details
---------------

### Project links

*   [Documentation](https://myst-parser.readthedocs.io)
*   [Homepage](https://github.com/executablebooks/MyST-Parser)

### Statistics

GitHub statistics:

*   **Stars:**
*   **Forks:**
*   **Open issues:**
*   **Open PRs:**

View statistics for this project via [Libraries.io](https://libraries.io/pypi/myst-docutils "External link"), or by using [our public dataset on Google BigQuery](https://packaging.python.org/guides/analyzing-pypi-package-downloads/)

### Meta

**License:** MIT License

**Author:** [Chris Sewell](mailto:chrisj_sewell@hotmail.com)

Tags markdown, lexer, parser, development, docutils, sphinx

**Requires:** Python >=3.8

### Maintainers

 [![Avatar for cjsewell from gravatar.com](https://pypi-camo.freetls.fastly.net/9564ca70d4f0bc5f3fba79f8b0dcbe2cbd64cefa/68747470733a2f2f7365637572652e67726176617461722e636f6d2f6176617461722f33363330333837303162666463396263326330313030326436333462303365373f73697a653d3530 "Avatar for cjsewell from gravatar.com")cjsewell](/user/cjsewell/)

### Classifiers

*   **Development Status**
    *   [4 - Beta](/search/?c=Development+Status+%3A%3A+4+-+Beta)
*   **Framework**
    *   [Sphinx :: Extension](/search/?c=Framework+%3A%3A+Sphinx+%3A%3A+Extension)
*   **Intended Audience**
    *   [Developers](/search/?c=Intended+Audience+%3A%3A+Developers)
*   **License**
    *   [OSI Approved :: MIT License](/search/?c=License+%3A%3A+OSI+Approved+%3A%3A+MIT+License)
*   **Programming Language**
    *   [Python :: 3](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3)
    *   [Python :: 3 :: Only](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3+%3A%3A+Only)
    *   [Python :: 3.8](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3.8)
    *   [Python :: 3.9](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3.9)
    *   [Python :: 3.10](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3.10)
    *   [Python :: 3.11](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3.11)
    *   [Python :: Implementation :: CPython](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+CPython)
    *   [Python :: Implementation :: PyPy](/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+Implementation+%3A%3A+PyPy)
*   **Topic**
    *   [Software Development :: Libraries :: Python Modules](/search/?c=Topic+%3A%3A+Software+Development+%3A%3A+Libraries+%3A%3A+Python+Modules)
    *   [Text Processing :: Markup](/search/?c=Topic+%3A%3A+Text+Processing+%3A%3A+Markup)

  

Release history [Release notifications](/help/#project-release-notifications) | [RSS feed](/rss/project/myst-docutils/releases.xml)
-----------------------------------------------------------------------------------------------------------------------------------

This version

![](https://pypi.org/static/images/blue-cube.572a5bfb.svg)

[

2.0.0

Jun 13, 2023

](/project/myst-docutils/2.0.0/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

1.0.0

Mar 7, 2023

](/project/myst-docutils/1.0.0/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.19.2

Mar 7, 2023

](/project/myst-docutils/0.19.2/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.19.1

Mar 2, 2023

](/project/myst-docutils/0.19.1/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.19.0

Mar 1, 2023

](/project/myst-docutils/0.19.0/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.18.1

Sep 27, 2022

](/project/myst-docutils/0.18.1/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.18.0

Jun 7, 2022

](/project/myst-docutils/0.18.0/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.17.2

Apr 17, 2022

](/project/myst-docutils/0.17.2/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.17.1

Apr 15, 2022

](/project/myst-docutils/0.17.1/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.17.0

Feb 11, 2022

](/project/myst-docutils/0.17.0/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.16.1

Dec 16, 2021

](/project/myst-docutils/0.16.1/)

![](https://pypi.org/static/images/white-cube.2351a86c.svg)

[

0.16.0

Dec 11, 2021

](/project/myst-docutils/0.16.0/)

Download files
--------------

Download the file for your platform. If you're not sure which to choose, learn more about [installing packages](https://packaging.python.org/tutorials/installing-packages/ "External link").

### Source Distribution

[myst\_docutils-2.0.0.tar.gz](https://files.pythonhosted.org/packages/a2/5a/3a27ba0130d98ee647010c48c5cc59f2668a9b89454861f8244c859decc7/myst_docutils-2.0.0.tar.gz) (85.9 kB [view hashes](#copy-hash-modal-d0ff79ef-2b98-4244-a322-63e2b578cfe9))

Uploaded Jun 13, 2023 `Source`

### Built Distribution

[myst\_docutils-2.0.0-py3-none-any.whl](https://files.pythonhosted.org/packages/61/5b/c5053590496e181b2ae1076f139177408ce8e8a5a07384b829ca810f44c2/myst_docutils-2.0.0-py3-none-any.whl) (77.2 kB [view hashes](#copy-hash-modal-013c6a66-d1c2-4352-833d-9321844e64e7))

Uploaded Jun 13, 2023 `Python 3`

[Close](#modal-close "Close")

### [Hashes](https://pip.pypa.io/en/stable/topics/secure-installs/#hash-checking-mode "External link") for myst\_docutils-2.0.0.tar.gz

Hashes for myst\_docutils-2.0.0.tar.gz

Algorithm

Hash digest

SHA256

`5a698f120f9b20d99e21dfa98d1e9b6e9f2ace37d25df11e97eb1011d3c8bbc6`

Copy

MD5

`4dc6f5f3c67fddb3e6783057c5e344dd`

Copy

BLAKE2b-256

`a25a3a27ba0130d98ee647010c48c5cc59f2668a9b89454861f8244c859decc7`

Copy

[Close](#modal-close)

[Close](#modal-close "Close")

### [Hashes](https://pip.pypa.io/en/stable/topics/secure-installs/#hash-checking-mode "External link") for myst\_docutils-2.0.0-py3-none-any.whl

Hashes for myst\_docutils-2.0.0-py3-none-any.whl

Algorithm

Hash digest

SHA256

`2e37a292f671033c847ae2e4fa1d34a2622fb0c9acc7667357b98cd86fb5e132`

Copy

MD5

`338b5441976223fac821eacfcafd012a`

Copy

BLAKE2b-256

`615bc5053590496e181b2ae1076f139177408ce8e8a5a07384b829ca810f44c2`

Copy

[Close](#modal-close)

![](/static/images/white-cube.2351a86c.svg)

Help
----

*   [Installing packages](https://packaging.python.org/tutorials/installing-packages/ "External link")
*   [Uploading packages](https://packaging.python.org/tutorials/packaging-projects/ "External link")
*   [User guide](https://packaging.python.org/ "External link")
*   [Project name retention](https://www.python.org/dev/peps/pep-0541/ "External link")
*   [FAQs](/help/)

About PyPI
----------

*   [PyPI Blog](https://blog.pypi.org "External link")
*   [Infrastructure dashboard](https://dtdg.co/pypi "External link")
*   [Statistics](/stats/)
*   [Logos & trademarks](/trademarks/)
*   [Our sponsors](/sponsors/)

Contributing to PyPI
--------------------

*   [Bugs and feedback](/help/#feedback)
*   [Contribute on GitHub](https://github.com/pypi/warehouse "External link")
*   [Translate PyPI](https://hosted.weblate.org/projects/pypa/warehouse/ "External link")
*   [Sponsor PyPI](/sponsors/)
*   [Development credits](https://github.com/pypi/warehouse/graphs/contributors "External link")

Using PyPI
----------

*   [Code of conduct](https://github.com/pypa/.github/blob/main/CODE_OF_CONDUCT.md "External link")
*   [Report security issue](/security/)
*   [Privacy policy](https://www.python.org/privacy/ "External link")
*   [Terms of use](/policy/terms-of-use/)
*   [Acceptable Use Policy](/policy/acceptable-use-policy/)

* * *

Status: [all systems operational](https://status.python.org/ "External link")

Developed and maintained by the Python community, for the Python community.  
[Donate today!](https://donate.pypi.org)

"PyPI", "Python Package Index", and the blocks logos are registered [trademarks](/trademarks/) of the [Python Software Foundation](https://www.python.org/psf-landing).  

© 2024 [Python Software Foundation](https://www.python.org/psf-landing/ "External link")  
[Site map](/sitemap/)

Switch to desktop version

*   English
*   español
*   français
*   日本語
*   português (Brasil)
*   українська
*   Ελληνικά
*   Deutsch
*   中文 (简体)
*   中文 (繁體)
*   русский
*   עברית
*   esperanto

Supported by

 [![AWS](https://pypi-camo.freetls.fastly.net/ed7074cadad1a06f56bc520ad9bd3e00d0704c5b/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f6177732d77686974652d6c6f676f2d7443615473387a432e706e67) AWS Cloud computing and Security Sponsor](https://aws.amazon.com/)[![Datadog](https://pypi-camo.freetls.fastly.net/8855f7c063a3bdb5b0ce8d91bfc50cf851cc5c51/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f64617461646f672d77686974652d6c6f676f2d6668644c4e666c6f2e706e67) Datadog Monitoring ](https://www.datadoghq.com/)[![Fastly](https://pypi-camo.freetls.fastly.net/df6fe8829cbff2d7f668d98571df1fd011f36192/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f666173746c792d77686974652d6c6f676f2d65684d3077735f6f2e706e67) Fastly CDN ](https://www.fastly.com/)[![Google](https://pypi-camo.freetls.fastly.net/420cc8cf360bac879e24c923b2f50ba7d1314fb0/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f676f6f676c652d77686974652d6c6f676f2d616734424e3774332e706e67) Google Download Analytics ](https://careers.google.com/)[![Microsoft](https://pypi-camo.freetls.fastly.net/524d1ce72f7772294ca4c1fe05d21dec8fa3f8ea/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f6d6963726f736f66742d77686974652d6c6f676f2d5a443172685444462e706e67) Microsoft PSF Sponsor ](https://www.python.org/psf/sponsors/#microsoft)[![Pingdom](https://pypi-camo.freetls.fastly.net/d01053c02f3a626b73ffcb06b96367fdbbf9e230/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f70696e67646f6d2d77686974652d6c6f676f2d67355831547546362e706e67) Pingdom Monitoring ](https://www.pingdom.com/)[![Sentry](https://pypi-camo.freetls.fastly.net/67af7117035e2345bacb5a82e9aa8b5b3e70701d/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f73656e7472792d77686974652d6c6f676f2d4a2d6b64742d706e2e706e67) Sentry Error logging ](https://getsentry.com/for/python)[![StatusPage](https://pypi-camo.freetls.fastly.net/b611884ff90435a0575dbab7d9b0d3e60f136466/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f737461747573706167652d77686974652d6c6f676f2d5467476c6a4a2d502e706e67) StatusPage Status page](https://statuspage.io)
