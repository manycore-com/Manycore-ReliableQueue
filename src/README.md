














# Building distribution
requires: 
python3 -m pip install --upgrade build

...which installs tomli, pep517, build

python -m build

...which outputs files to dist/ (in .gitignore)

