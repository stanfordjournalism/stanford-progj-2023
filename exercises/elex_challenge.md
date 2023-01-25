# Basic data analysis pipeline challenge

## Overview

Below is a code challenge designed to help you practice a variety of skills:

- [Download remote data](/docs/python/remote_files.md)
- [Write data to a text file](docs/python/file_io.md) to local disk
- [Read and write CSV files](/docs/python/csv.md)
- [Generate summary data](docs/python/dict_basics.md) using `dicts`

> Yes, you *could* use the `pandas` library to arguably simplify these tasks, but the point is to get some reps using these more basic Python tools and workflows.

## The Challenge

Write code to :

- Download this [fake election data][] using this [election CSV link][]
- Save the code to a local file called `election_data`
- Read the data using the `csv` library
- Use dictionaries to tally the following stats:
 - Total votes by candidate
 - Total votes by party
- Use the `csv` module to write two new spreadsheets:
 - `candidate_totals.csv` - contains `name` and `vote_total` fields
 - `party_totals.csv` - contains `party` and `vote_total` fields

[fake election data]: https://docs.google.com/spreadsheets/d/1Xw5ZBj1c_9rlayZU6mDq356YvLmLLYIvA_f2OHgVAjs/edit?usp=sharing
[election CSV link]: https://docs.google.com/spreadsheets/d/e/2PACX-1vTUtWkuAE8V95MwC1xbDYAIO8NR4Cd1hoANJ7g38CWMjmhe_IwLePygi-DR3DIK3-gAsak-kxWkwze8/pub?gid=0&single=true&output=csv
