# icmmcm #

`icmmcm.cls` is a LaTeX document class for formatting submissions
for the annual
[Mathematical Contest in Modelling (MCM) and Interdisciplinary Contest in Modeling (ICM)](http://www.comap.com/undergraduate/contests/mcm/)
run by the
[Consortium for Mathematics and Its Applications (COMAP)](http://www.comap.com/).

The contest has
[strict requirements on the formatting of reports](http://www.comap.com/undergraduate/contests/mcm/instructions.php)
and this class is meant to address those aspects of the contests'
rules.


## How to Use the `icmmcm` Document Class ##

After downloading the code (by cloning the repository or
downloading a ZIP or `tar.gz` archive from
[the releases page](https://github.com/hmcmathematics/icmmcm/releases),
copy `blank-template.tex` to give it a better name (maybe your
team's control number) and edit that file.

Specify the following information:

* Your report's title with the LaTeX `\title` command
* The contest you're participating in with the `\contest` command (should be either `MCM` or `ICM`)
* The letter indicating the problem you're addressing with
`\question` (in 2016, there are three questions for each contest,
with *A*, *B*, and *C* being MCM problems and *D*, *E*, and *F*
ICM problems).
* Your team's *Control Number* with the `\team` command.

**Make sure you don't include any identifying information in your
  report (e.g., your or your teammates' names, your advisors'
  names, your school or other organization, your location).**

*Read the [contest instructions](http://www.comap.com/undergraduate/contests/mcm/instructions.php) carefully!*


## Contributing! ##

We welcome suggestions and contributions, as well as bug reports.
Please use
[the project's GitHub issue tracker](https://github.com/hmcmathematics/icmmcm/issues)
to file requests, and fork and submit pull requests to address
issues you find.

We appreciate your help in supporting MCM and ICM participants!
