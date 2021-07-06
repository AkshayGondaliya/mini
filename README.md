create env
```bash 
conda create -n mini python=3.7 -y
```
activate env
```bash 
connda activate mini
```
created a requirements.txt

install the requirements
```bash
pip install -r requirements.txt
```
download the data 

```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add.
```
```bash
git commit -m "first commit"
```
```bash
git remote add origin https://github.com/AkshayGondaliya/mini.git
```
```bash
git branch -M main
```
```bash
git push origin main
```
tox command-
```bash
tox
```
for rebuilding
```bash
tox -r
```
pytest command
```bash
pytest -v
```
setup commands -
```bash
pip install -e .
```
build your own package commands-
```bash
python setup.py sdist bdist_wheel
```