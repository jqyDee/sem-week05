# 26seminar Limits and Colimits

## Content of the repo

The repo contains the TCS LaTeX class file for seminar reports, together with a report.tex file
as well as the howto.tex file, explaining howto write a (bachelor) thesis and giving some
general writing tipps.

It also contains the gitlab runner (in .gitlab-ci.yml), defining the compiliation pipeline.

## Howto upload your report

The runner expects that your report is called "report.tex" and the class file expects your
bibiliography to be called "biblio.bib". (Adapting the existing file "report.tex" for your report, is not a bad idea.)

You can change the former in the gitlab runner and the latter in tcsseminar.cls

Once you upload your report (together with your bibliography) by pushing to the repo, the pipeline
compiles your code automatically (check in Build → Pipelines). If the job succeeds, your submission is complete.

Your report should not exceed 10 pages (including references) and clearly must be written in LaTeX.