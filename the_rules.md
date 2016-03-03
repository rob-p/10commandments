## 10 Commandments of Bioinformatics
In random order

1. Thou shalt not publish a paper that use "in-house (Language X) scripts, available upon request"
2. Thou shalt not use massively outdated versions of actively maintained software
3. thou shalt not use hard-coded paths or filenames.. ever
4. tho shalt not write redundant software (e.g., another short read aligner)
5. thou shalt log everything, including paths to executables, versions, environmental variables, the lot.
6. thou shalt have test
7. though shalt always resolve all input paths and filenames to absolute paths before doing anything else
8. thou shalt not put weird characters in filenames or paths, including spaces
9. thou shalt not fail silently
10. though shalt not create empty files if you fail (including files with just column headins in)
11. Tho shalt use `--help` and not `-help`
12. thou shalt have documentation, including a 'setting started' section
13. thou shalt RTFM first.
14. thou shalt generate neatly organised output directory heirarchies
15. thou shalt not invent new file formats
16. thou shalt not frivolously implement a parser
17. thou shall build checkpoints into long running software?
18. tho shal not write 129869 temprary files (Trinity)
