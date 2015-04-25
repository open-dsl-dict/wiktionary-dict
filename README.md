This project collects bilingual Wiktionary dictionaries in DSL-format, based on the work of Wiktionary [User:Matthias_Buchmeier](http://en.wiktionary.org/wiki/User:Matthias_Buchmeier).

The scripts used to convert these dictionaries can be found [here](https://github.com/dohliam/dsl-tools/tree/master/wikt2dsl), and the original source files and other information can be found on the [project homepage](https://en.wiktionary.org/wiki/User:Matthias_Buchmeier) on Wiktionary.

This collection is part of the [Open DSL Dictionary Project](https://github.com/open-dsl-dict).

# The dictionaries

The source dictionaries (in the `src` folder) are unidirectional, as are the dsl dictionaries contained in `dsl/oneway`. Bidirectional (but slightly larger) dictionaries are contained in the `dsl/twoway` directory.

With the bidirectional dictionaries, the entries are unchanged, but can be found by searching either for the headword or its translation. Unless you are worried about disk space, you probably want the bidirectional versions.

One exception might be if you only search using language A for translations in language B rather than vice versa, or if there is a high degree of overlap in the two languages (so that you get a lot of false positive hits when searching for a word in language A because an identical word exists as a translation in language B).

# Available languages

The following language pairs are available:

* English => Bulgarian (`en-bg-enwiktionary.dsl.dz`)
* English => Catalan (`en-ca-enwiktionary.dsl.dz`)
* English => Czech (`en-cs-enwiktionary.dsl.dz`)
* English => Danish (`en-da-enwiktionary.dsl.dz`)
* English => Dutch (`en-nl-enwiktionary.dsl.dz`)
* English => Finnish (`en-fi-enwiktionary.dsl.dz`)
* English => French (`en-fr-enwiktionary.dsl.dz`)
* English => German (`en-de-enwiktionary.dsl.dz`)
* English => Greek (`en-el-enwiktionary.dsl.dz`)
* English => Hebrew (`en-he-enwiktionary.dsl.dz`)
* English => Hindi (`en-hi-enwiktionary.dsl.dz`)
* English => Hungarian (`en-hu-enwiktionary.dsl.dz`)
* English => Indonesian (`en-id-enwiktionary.dsl.dz`)
* English => Italian (`en-it-enwiktionary.dsl.dz`)
* English => Japanese (`en-ja-enwiktionary.dsl.dz`)
* English => Korean (`en-ko-enwiktionary.dsl.dz`)
* English => Malay (`en-ms-enwiktionary.dsl.dz`)
* English => Mandarin (`en-cmn-enwiktionary.dsl.dz`)
* English => Norwegian (`en-no-enwiktionary.dsl.dz`)
* English => Persian (`en-fa-enwiktionary.dsl.dz`)
* English => Polish (`en-pl-enwiktionary.dsl.dz`)
* English => Portuguese (`en-pt-enwiktionary.dsl.dz`)
* English => Romanian (`en-ro-enwiktionary.dsl.dz`)
* English => Russian (`en-ru-enwiktionary.dsl.dz`)
* English => Serbo-Croatian (`en-sh-enwiktionary.dsl.dz`)
* English => Spanish (`en-es-enwiktionary.dsl.dz`)
* English => Standard Arabic (`en-arb-enwiktionary.dsl.dz`)
* English => Swedish (`en-sv-enwiktionary.dsl.dz`)
* English => Turkish (`en-tr-enwiktionary.dsl.dz`)
* English => Vietnamese (`en-vi-enwiktionary.dsl.dz`)
* Finnish => English (`fi-en-enwiktionary.dsl.dz`)
* French => English (`fr-en-enwiktionary.dsl.dz`)
* Italian => English (`it-en-enwiktionary.dsl.dz`)
* Portuguese => English (`pt-en-enwiktionary.dsl.dz`)
* Spanish => English (`es-en-enwiktionary.dsl.dz`)
* Finnish Conjugations (`fi_en_wiktionary-conj.dsl.dz`)

# License

These dictionaries are published under the Creative Commons Attribution-ShareAlike 3.0 Unported License and the GNU Free Documentation License (the same dual license under which the original files were made available).

Please see the information files accompanying each of the dictionaries for further details and attribution information.
