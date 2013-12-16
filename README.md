d3po
====

d3po is a project designed to allow an astronomer, with no special data visualization skills, to make an interactive, publication-quality figure that has staged builds and linked brushing through scatter plots. Right now we are in search of alpha testers, who have figures that could be made interactive and who are willing to get their hands a little dirty (No javascript skills needed). Full 1.0 version expected in January 2014.

Installing your own d3po server
-------------------------------

    git clone git@github.com:adrn/d3po.git
    cd d3po
    virtualenv --no-site-packages venv
    source venv/bin/activate
    pip install -r pip-requirements.txt
    python run.py