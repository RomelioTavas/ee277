# Machine Exercise 1
```
Romelio P. Tavas Jr.
2011-11218
```
## Prerequisites
### Install Python 3.7
```bash
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt install python3.7
```
### Create a virtualenv
```
$ sudo apt install virtualenv
$ virtualenv venv -p /usr/bin/python3.7
$ source venv/bin/activate
```

## Running the code

### Make sure you are still in the virtualenv
```
$ git clone https://github.com/RomelioTavas/ee277.git
$ cd ee277/me-1
```

### Install dependencies
```
$ pip install -r requirements.txt
```

### Run jupyter server
```
$ jupyter notebook
```


- Then a browser window will open automatically and show the jupyter interface.
- Click on ee277-me-1.ipynb to view notebook
If the browser window does not automatically show,
Please navigate to: http://localhost:8888/notebooks/ee277-me-1.ipynb using your browser

- Run each cell with Shift + Enter

