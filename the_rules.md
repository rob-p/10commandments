## 10 Commandments of Bioinformatics

In a suggested order of importance.

#### Developers

01. Thou shalt use an open source licence.
02. Thou shalt use version control and version number significant releases.
03. Thou shalt not write redundant software (e.g., another short read aligner).
04. Thou shalt not invent new file formats.
05. Thou shalt not frivolously re-implement software, especially parsers and anything R does already.
06. Thou shalt not fail silently.
07. Thou shalt not use hard-coded paths or filenames... ever.
08. Thou shalt not create empty files if you fail (including files with just column headers in).
09. Thou shalt log everything, including the command line called, paths to executables, versions, environmental variables, the lot.
10. Thou shalt always resolve all input paths and filenames to absolute paths before doing anything else.
11. Thou shalt have tests.
12. Thou shalt have documentation, including a 'getting started' section.
13. Thou shalt generate neatly organised output directory heirarchies.
14. Thou shalt work with gzipped input as well as unconpressed input.
15. Thou shall build checkpoints into long running software.
16. Thou shalt not write >200 temprary files (Trinity).
17. Thou shalt generate plots as vector pdfs or svgs, never bitmaps.
18. Tho shalt use `--help` and not `-help`.
19. Though shall always pad numbers with leading zeros to a standard length.

#### Users

01. Thou shalt use version control for all coding work.
02. Thou shalt not publish a paper that use "in-house (Language X) scripts, available upon request"
03. Thou shalt RTFM first.
04. Thou shalt not use massively outdated versions of actively maintained software.
05. Thou shalt not put weird characters in filenames or paths, including spaces.
06. Thou shalt verify the input before submitting a bug report.
07. After verisfying the input, thou shalt RTFM again, before submitting a bug report.

