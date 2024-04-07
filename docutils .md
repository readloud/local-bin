## Docutils 0.21.rc1    

[Docutils](https://docutils.sourceforge.io) | [Overview](docs/index.html) | [About](docs/index.html#project-fundamentals) | [Users](docs/index.html#user) | [Reference](docs/index.html#ref) | [Developers](docs/index.html#howto)

About Docutils 0.21.rc1
=========================

| ------ | ------------- | 
| Author:| David Goodger | 
| Contact: | [goodger@python.org](mailto:goodger@python.org) |
| Date:|2024-03-27|Web site:|[https://docutils.sourceforge.io/](https://docutils.sourceforge.io/) |
| Copyright: | This document has been placed in the public domain. |

[Contents](#top)

*   [Quick-Start](#quick-start)
    
*   [Purpose](#purpose)
    
*   [Dependencies](#dependencies)
    
    *   [Recommendations](#recommendations)
        
*   [Installation](#installation)
    
    *   [GNU/Linux, BSDs, Unix, Mac OS X, etc.](#gnu-linux-bsds-unix-mac-os-x-etc)
        
    *   [Windows](#windows)
        
*   [Usage](#usage)
    
*   [Project Files & Directories](#project-files-directories)
    
*   [Development version](#development-version)
    
*   [Converting the documentation](#converting-the-documentation)
    
*   [Running the Test Suite](#running-the-test-suite)
    
*   [Getting Help](#getting-help)
    

[Quick-Start](#toc-entry-1)[](#quick-start "link to this section")
------------------------------------------------------------------

This is for those who want to get up & running quickly.

1.  Docutils requires **Python**, available from [https://www.python.org/](https://www.python.org/). See [Dependencies](#dependencies) below for details.
    
2.  Install the latest stable release from PyPi with [pip](https://pypi.org/project/pip/):
    
    pip install docutils
    
    For alternatives and details, see section [Installation](#installation) below.
    
3.  Use the [front-end scripts](docs/user/tools.html) to convert reStructuredText documents. Try for example:
    
    docutils FAQ.txt FAQ.html
    
    See [Usage](#usage) below for details.
    

[Purpose](#toc-entry-2)[](#purpose "link to this section")
----------------------------------------------------------

The purpose of the Docutils project is to provide a set of tools for processing plaintext documentation into useful formats, such as HTML, LaTeX, troff (man pages), OpenOffice, and native XML. Support for the following sources has been implemented:

*   Standalone files.
    
*   [PEPs (Python Enhancement Proposals)](https://peps.python.org/pep-0012).
    

Support for the following sources is planned or provided by [third party tools](docs/user/links.html#related-applications):

*   Inline documentation from Python modules and packages, extracted with namespace context.
    
*   Email (RFC-822 headers, quoted excerpts, signatures, MIME parts).
    
*   Wikis, with global reference lookups of "wiki links".
    
*   Compound documents, such as multiple chapter files merged into a book.
    
*   And others as discovered.
    

[Dependencies](#toc-entry-3)[](#dependencies "link to this section")
--------------------------------------------------------------------

To run the code, [Python](https://www.python.org/.) must be installed. (Python is pre-installed with most Linux distributions.)

*   Since version 0.21, Docutils requires Python 3.9 or later.
    
*   Docutils versions 0.19 to 0.20.1 require Python 3.7 or later.
    
*   Docutils versions 0.16 to 0.18 require Python 2.7 or 3.5+.
    

### [Recommendations](#toc-entry-4)[](#recommendations "link to this section")

Docutils uses the following packages for enhanced functionality, if they are installed:

*   The recommended installer is [pip](https://pypi.org/project/pip/), [setuptools](https://pypi.org/project/setuptools/) works, too.
    
*   The [Python Imaging Library](http://www.pythonware.com/products/pil/) (PIL) is used for some image manipulation operations.
    
*   The [Pygments](https://pypi.org/project/Pygments/) package provides syntax highlight of "code" directives and roles.
    
*   The [myst](https://pypi.org/project/myst-docutils/), [pycmark](https://pypi.org/project/pycmark/), or [recommonmark](https://github.com/rtfd/recommonmark) parsers can be used to parse input in "Markdown" ([CommonMark](https://spec.commonmark.org/0.30/)) format.
    

The [Docutils Link List](docs/user/links.html) records projects that users of Docutils and reStructuredText may find useful.

[Installation](#toc-entry-5)[](#installation "link to this section")
--------------------------------------------------------------------

The [Python Packaging User Guide](https://packaging.python.org/en/latest/) gives details how to [use pip for installing](https://packaging.python.org/en/latest/tutorials/installing-packages/#use-pip-for-installing).

*   The simplest way is to install the latest _stable release_ from PyPi:
    
    pip install docutils
    
*   To install a _pre-relase_, append the option \--pre.
    
*   To install a [development version](#development-version) _from source_:
    
    1.  Open a shell
        
    2.  Go to the directory containing the file setup.py.
        
    3.  Install the package with **one** of the following commands:
        
        pip install -e .  # editable install
        pip install .     # regular install
        
        or do a ["manual" install](docs/dev/repository.html#manual-install).
        
    4.  Optional steps:
        
        *   [Running the test suite](#running-the-test-suite)
            
        *   [Converting the documentation](#converting-the-documentation)
            
    
    See also the OS-specific installation instructions below and the [Docutils version repository](docs/dev/repository.html) documentation.
    
*   To install for a _specific Python version_, use this version in the setup call, e.g.
    
    python3.11 -m pip install docutils
    
    If the python executable isn't on your path, you'll have to specify the complete path, such as /usr/local/bin/python3.11.
    
    To install for different Python versions, repeat step 3 for every required version. The last installed version will be used for the docutils command line application.
    

### [GNU/Linux, BSDs, Unix, Mac OS X, etc.](#toc-entry-6)[](#gnu-linux-bsds-unix-mac-os-x-etc "link to this section")

*   Use su or sudo for a system-wide installation as root, e.g.:
    
    sudo pip install docutils
    

### [Windows](#toc-entry-7)[](#windows "link to this section")

*   The Python FAQ explains [how to run a Python program under Windows](https://docs.python.org/3/faq/windows.html#how-do-i-run-a-python-program-under-windows).
    
*   Usually, [pip](https://pypi.org/project/pip/) is automatically installed if you are using Python downloaded from [https://python.org](https://python.org). If not, see the [pip documentation](https://pip.pypa.io/en/stable/installation/).
    
*   The command window should recognise the word py as an instruction to start the interpreter, e.g.
    
    > py -m pip install docutils
    
    If this does not work, you may have to specify the full path to the Python executable.
    

[Usage](#toc-entry-8)[](#usage "link to this section")
------------------------------------------------------

Start the "docutils" command line application with:

docutils \[options\] \[<source> \[<destination>\]\]

The default action is to convert a [reStructuredText](https://docutils.sourceforge.io/rst.html) document to HTML5, for example:

docutils test.rst test.html

Read the \--help option output for details on options and arguments and [Docutils Front-End Tools](docs/user/tools.html) for the full documentation of the various tools.

For programmatic use of the docutils Python package, read the [API Reference Material](/docs/index.html#api-reference-material-for-client-developers) and the source code. Remaining questions may be answered in the [Docutils Project Documentation](/docs/index.html) or the [Docutils-users](docs/user/mailing-lists.html#docutils-users) mailing list.

Contributions are welcome!

[Project Files & Directories](#toc-entry-9)[](#project-files-directories "link to this section")
------------------------------------------------------------------------------------------------

*   README.txt: You're reading it.
    
*   COPYING.txt: Public Domain Dedication and copyright details for non-public-domain files (most are PD).
    
*   FAQ.txt: Frequently Asked Questions (with answers!).
    
*   RELEASE-NOTES.txt: Summary of the major changes in recent releases.
    
*   HISTORY.txt: A detailed change log, for the current and all previous project releases.
    
*   BUGS.txt: Known bugs, and how to report a bug.
    
*   THANKS.txt: List of contributors.
    
*   setup.py: Installation script. See "Installation" below.
    
*   docutils: The project source directory, installed as a Python package.
    
*   docs: The project documentation directory. Read docs/index.txt for an overview.
    
*   docs/user: The project user documentation directory. Contains the following documents, among others:
    
    *   docs/user/tools.txt: Docutils Front-End Tools
        
    *   docs/user/latex.txt: Docutils LaTeX Writer
        
    *   docs/user/rst/quickstart.txt: A ReStructuredText Primer
        
    *   docs/user/rst/quickref.html: Quick reStructuredText (HTML only)
        
*   docs/ref: The project reference directory. docs/ref/rst/restructuredtext.txt is the reStructuredText reference.
    
*   licenses: Directory containing copies of license files for non-public-domain files.
    
*   tools: Directory for Docutils front-end tools. See docs/user/tools.txt for documentation.
    
*   test: Unit tests. Not required to use the software, but very useful if you're planning to modify it. See [Running the Test Suite](#running-the-test-suite) below.
    

[Development version](#toc-entry-10)[](#development-version "link to this section")
-----------------------------------------------------------------------------------

While we are trying to follow a "release early & often" policy, features are added frequently. We recommend using a current snapshot or a working copy of the repository.

Repository check-out:

To keep up to date on the latest developments, use a [working copy](docs/dev/repository.html#checking-out-the-repository) of the [Docutils version repository](docs/dev/repository.html).

Snapshots:

To get a repository snapshot, go to [https://sourceforge.net/p/docutils/code/HEAD/tree/trunk/docutils/](https://sourceforge.net/p/docutils/code/HEAD/tree/trunk/docutils/) and click the download snapshot button.

Unpack in a temporary directory, **not** directly in Python's site-packages.

Continue with the [Installation](#installation) instructions below.

[Converting the documentation](#toc-entry-11)[](#converting-the-documentation "link to this section")
-----------------------------------------------------------------------------------------------------

After unpacking and installing the Docutils package, the following shell commands will generate HTML for all included documentation:

cd <archive\_directory\_path>
tools/buildhtml.py .

On Windows systems, type:

cd <archive\_directory\_path>
py tools\\buildhtml.py ..

The final directory name of the <archive\_directory\_path> is "docutils" for snapshots. For official releases, the directory may be called "docutils-X.Y.Z", where "X.Y.Z" is the release version.

Some files may generate system messages (warnings and errors). The docs/user/rst/demo.txt file (under the archive directory) contains five intentional errors. (They test the error reporting mechanism!)

[Running the Test Suite](#toc-entry-12)[](#running-the-test-suite "link to this section")
-----------------------------------------------------------------------------------------

The test suite is documented in [Docutils Testing](https://docutils.sourceforge.io/docs/dev/testing.html) (docs/dev/testing.txt).

To run the entire test suite, open a shell and use the following commands:

cd <archive\_directory\_path>/test
./alltests.py

Under Windows, type:

cd <archive\_directory\_path>\\test
python alltests.py

You should see a long line of periods, one for each test, and then a summary like this:

Ran 1744 tests in 5.859s

OK (skipped=1)
Elapsed time: 6.235 seconds

The number of tests will grow over time, and the times reported will depend on the computer running the tests. Some test are skipped, if optional dependencies ([recommendations](#recommendations)) are missing. The difference between the two times represents the time required to set up the tests (import modules, create data structures, etc.).

A copy of the test output is written to the file alltests.out.

If any of the tests fail, please [open a bug report](https://sourceforge.net/p/docutils/bugs/) or [send an email](mailto:docutils-users@lists.sourceforge.net?subject=Test%20suite%20failure) (see [Bugs](BUGS.html)). Please include all relevant output, information about your operating system, Python version, and Docutils version. To see the Docutils version, look at the test output or use

docutils --version

[Getting Help](#toc-entry-13)[](#getting-help "link to this section")
---------------------------------------------------------------------

All documentation can be reached from the [Project Documentation Overview](docs/index.html).

The SourceForge [project page](https://sourceforge.net/p/docutils) has links to the tracker, mailing lists, and code repository.

If you have further questions or need assistance with Docutils or reStructuredText, please post a message to the [Docutils-users](docs/user/mailing-lists.html#docutils-users) mailing list.

[View document source](README.txt). Generated on: 2024-03-27 00:08 UTC. Generated by [Docutils](https://docutils.sourceforge.io/) from [reStructuredText](https://docutils.sourceforge.io/rst.html) source.
