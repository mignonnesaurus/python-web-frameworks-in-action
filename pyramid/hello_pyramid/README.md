#Hello Pyramid

## Steps

1. `python3 -m venv myvenv`
2. `source myvenv/bin/activate`
3. `pip install -r requirements.txt`
4. `pcreate -s starter hello_pyramid`
5. `cd hello_pyramid`
6. `pip install -e .`
7. `pip install -e ".[testing]"`
8. `py.test -q`
9. `pserve development.ini`
10. `deactivate`


## Reference
* http://docs.pylonsproject.org/projects/pyramid/en/latest/narr/install.html#installing-chapter
* http://docs.pylonsproject.org/projects/pyramid/en/latest/narr/project.html#creating-a-project