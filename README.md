A set of simple IPython scripts that
  1. unify two existing GoT character datasets with demographic and relationship information (specifically, parentage information) into SQLite DB format. 
  2. Produce graphviz-based family tree visualizations of the aforementioned DB.
 
This repo was created with the express intent of introducing myself to some of the basics of SQLite3, alongside granting myself a little bit of experience using IPython and command-line scripts to produce a simple but tangible result.  Not currently generalizable to other family-tree style tasks, but could be adapted to be so (e.g. to produce family forests for particular clan datasets, small villages, etc.).  Very much a work in progress.

Use anything to your hearts content, but please note that I've utilized the work of three individuals, whose work is credited below:
  1. dataraw/characters.json: Credited to [Jeffrey Lancaster](jeffrey.lancaster@gmail.com) who compiled a [large array](https://github.com/jeffreylancaster/game-of-thrones)
of publically available GoT datasets and produced far superior GoT visualizations.
  2. character-predictions.csv: Credited to the team at [A Song Ice and Data](https://got.show/), and located [here](https://data.world/data-society/game-of-thrones).  Provides several simple demographic data related to the characters, and perhaps more interestingly a predicted survival score for living characters in ASOIAF.
  3. familytreemaker.py: Adrien Verge produced the [original family tree](https://github.com/adrienverge/familytreemaker) plotting script, which I've altered only very slightly to skirt by some UTF-8 issues that pop up on some platforms.

Note that I've modified the raw data very slightly to accomodate (generally satellite) characters that appear in one dataset but not the other.
If anyone has knowledge of more recent or complete publicly available data on either the GoT show (probably not) or ASOIAF (possibly), please let me know.

If you want to use these scripts on your own, please note that you'll need to install the appropriate [graphviz package](https://www.graphviz.org/download/)
