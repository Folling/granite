# Overview
granite is a data persistence library with a focus on application development.
granite part of a larger application development framework called [alloy](https://github.com/Folling/alloy).

This document is a WIP and will be expanded upon as the project progresses.

This library has existed in multiple forms before. Two C++ versions and one previous rust version. 
You can find these projects (in ascending order of the creation date):
- [Original C++ version](https://memleak.eu/Folling/graphite)
- [Original Rust version](https://memleak.eu/Folling/graphite-rs)
- [Second C++ iteration](https://memleak.eu/Folling/graphite-CPP-v2)

# Features
- [ ] SQLite storage
- [ ] K/V storage
- [ ] Binary serialisation
- [ ] JSON serialisation
- [ ] XML serialisation

It will probably be developed as the slowest of the many different parts of alloy. This is because 
I personally only need SQLite and binary serialisation.

# Contributing
alloy is open source and is supposed to benefit from the inclusion of other people. 
However I do reserve the rights to deny any feature requests or pull requests but am always open to discussion and having my mind changed. 
If you're uncertain whether or not a certain pull request would be appreciated and don't want to waste effort without knowing whether it's worth it, feel free to open an issue and ask. 
All code should be formatted using the same guideline. For this please use rustfmt. In the future a customised rustfmt stylisation might be used.
File and directory names are are to be formatted using snake_case. Excluded from this rule are files that have a certain convention such as .gitignore, LICENCE.txt and markdown files.

# Support
I have a fulltime job and can only afford so much time for alloy. If you would like to change that in the future consider donating to the project (note: Donating link will follow, alloy isn't worth donating yet). I also appreciate feedback (next to constructive criticism) so feel free to email me at coding@folling.de. 
