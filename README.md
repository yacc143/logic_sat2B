Get all solutions for a CNF via limboole
========================================

You need two external files to use this:

* the limboole executable for your platform from http://fmv.jku.at/limboole/index.html
* the formulas.zip file from Moodle.

Installation
~~~~~~~~~~~~

Standard python rules, e.g. pip install .


Usage
~~~~~

solve_limboole -f formulas.zip -l limboolename 9899999 "Max Mustermann"

Should produce solutions_9899999.txt

If limboole is available on the path with the *standard* name for your platform, 
you do not need to specify it via an option. 