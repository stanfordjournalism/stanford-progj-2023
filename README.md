# Stanford ~ Programming in Journalism

Sundry notes and code bits for Stanford's Programming in Journalism class (COMM 177P/277P).

## Important links

* [Syllabus][]
* [Assignments](assignments/README.md) and [Grading](assignments/grading.md)
* [Bookshelf](docs/bookshelf.md) - recommended books, tutorials, cheatsheets, etc.
* [Code solutions](https://github.com/zstumgoren/stanford-progj-2023-solutions) - A private repo containing solutions to class exercises.
* [DataKit][] - overview and details on install and usage
* [Getting Help](docs/getting_help.md) - Resources and strategies for finding help.
* [Glossary](docs/glossary.md) - technical terms used in class
* [Python](docs/python/README.md) - overview, tutorials, etc.
* [Technical setup](docs/tech_setup.md) and [FAQ](docs/tech_faq.md) - recommended and required software (all free)
* [Workflow advice](docs/workflow_advice.md) - working on the command line, etc.

[Syllabus]: https://canvas.stanford.edu/courses/166386/assignments/syllabus

## Class notes

### Week 1

#### Day 1 - Course Intro

* Course overview - syllabus, [grading](assignments/grading.md), etc.
* Discuss the [history](docs/history.md) of code and data analysis in journalism
* Preview of [automation with Bash](exercises/bash_preview.md)
* [How to Succeed in this Course](docs/how_to_succeed.md)

#### Day 2 - The Owl, Problem Solving, and the Unix Workbench

* [Final project][] overview and past examples
* [The Owl, Problem Solving, and the Unix Workbench](docs/owl_probs_unix.md)
* [Bash intro](https://tinyurl.com/bash-intro)
* [Bash drill](exercises/bash_drill.md)
* [Tech setup](tech_setup.md) through the Python section (stop before `Configure` step)
* **[Assignment 0](assignments/bash_intro.md)** - Unix practice and failed banks script

### Week 2

#### Day 3 - MLK Day

No class.

#### Day 4 - Python Intro

* Review [Assignment 0 (failed banks)](assignments/bash_intro.md) if everyone submitted...
* [Bash drill](exercises/bash_drill.md) - Yep. Again. This time using the "Blind-folded" and "Plain English" [variations](exercises/bash_drill.md#variations-on-the-drill).
* [Python Intro and resources](docs/python) links to misc docs/tutorials on this GitHub repo
* [Python overview and coding contexts](docs/python/overview.md)
* [Python Syntax Crash Course](docs/python/python_syntax_crash_course.md)
* [Software installs](docs/tech_setup.md) -- everyone must have Python installed and GitHub configured by end of class.
* **[Assignment 1](assignments/python_intro.md)** - Python reading/practice and code challenge
* **[Assignment 2](assignments/python_lists_dicts.md)** - Python lists/dicts and DataKit overview


### Week 3

#### Day 5 - Python Intro

* [Bash drill](exercises/bash_drill.md) - Yep. Again. This time using the "Blind-folded" and "Plain English" [variations](exercises/bash_drill.md#variations-on-the-drill).
* Questions about [Assignment 1](assignments/python_intro.md)? It covered a lot of important fundamentals:
  - Python interactive shell
  - Expressions
  - Basic data types
  - Variables
  - Flow control (conditions and blocks, if/else/elif etc.)
* Questions on [Assignment 2](assignments/python_lists_dicts.md) on Python lists/dicts?
* [Dictionaries crash course](docs/python/dict_basics.md)
* [Reading and writing text files](docs/python/file_io.md) - How to read text files
* **[Assignment 3](assignments/libraries_and_fdic_py.md)** - Practical Python skills and Failed Banks in Python

#### Day 6 - Python Intro Part Deux

* [Reading and writing text files](docs/python/file_io.md) - Review how to write text files
* Libraries - Overview and practice practical skills
  * Learn how to use [code libraries](/docs/python/libraries.md) included with Python or offered by third parties
  * Learn how to [download remote files](/docs/python/remote_files.md)
  * Learn how to [work with CSVs](/docs/python/csv.md)
* Complete [configuration steps](docs/tech_setup.md#configure) for ssh and DataKit
* Election data [code challenge](exercises/elex_challenge.md)
* **[Assignment 3](assignments/libraries_and_fdic_py.md)** - Practical Python skills and Failed Banks in Python


[Final Project]: projects/sf_data_analysis.md
[FDA Recalls project]: projects/fda_recall_entities.md

[DataKit]: docs/datakit.md
