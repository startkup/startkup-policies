TKUAIIC-Policies
================

git repository for use with [TKUAIIC].
This repository is maintained for use on the Tamkang University Artificial
Innovative Intelligence Club policies, but should also be fully opened to anyone
to make law/policy data being a part of the regular open data from TKUAIIC.


File Structure
-----

Files should be in a `/<category>-<id>_<version: YYYY-MM-DD>_<language code: zh-hant|en>.<file format: md>`
structure in this repository.


Usage
-----

Checkout this git repository into `/tkuaiic/policies` using `git clone <URL>` or add the
repository as a git submodule using `git submodule add <URL> vendor` followed
by `git submodule update --init`.


Adding or updating git submodules
----------------------------

0. Read the [documentation] on the process for adding new submodules.
1. In some cases, the submodules might include not needed files (e.g. test files,
   project files, etc). If you cannot exclude them from submodules's archive
   (e.g. by `export-ignore`ing unwanted files in submodules's `.gitattributes`
   file), you can skip checking them in by listing them in `.gitignore` file.
2. Add and commit changes as a git patch.
3. Review and merge changes.

If in doubt, seek advice from regular commiters to this repository.


List of TKUAIIC policies
-----

- 1\. General 總則
    - 1-1. [淡江大學AI創智社社團組織章程]


[TKUAIIC]: https://github.com/tkuaiic/tkuaiic
[documentation]: https://www.mediawiki.org/wiki/Manual:External_libraries
[淡江大學AI創智社社團組織章程]: 1-1_2022-06-07_zh-hant.md