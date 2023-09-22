Source: https://www.cs.ubc.ca/labs/algorithms/Projects/SATzilla/

This version was adapted to remove preprocessing, as this was not model-count preserving.

Avoid using -lp and -ls, as they tend to crash.

An example exection:
./features -base -unit -sp -dia -cl -lobjois instance.cnf
