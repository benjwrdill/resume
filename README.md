# resume

This repository holds the code necessary to bulid my resume using LaTeX and pandoc as programmatic typesetting tools.

# Requirements

1. LaTeX (as TeXLive or other) - full distribution (~5.5GB)
2. pandoc

# Building

The main resume document relies on a file, jobs.tex, that is not included in this repo. This file contains definitions of sensitive information, such as email and phone number. To create this file:

```
cd /path/to/repository
cp example.tex job.tex
```

You may then replace the placeholder values for email and phone nubmers with the appropriate values.

Once you have done this, you can build a pdf using:

```
pdflatex -jobname=dillben-resume-VERSION dillben-resume.tex
```
