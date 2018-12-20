# Real-time People Tracking

## Getting started

## Prerequisites

### Install dependencies

Development for this project will be isolated in Python virtual environment. This allows us to experiment with different versions of dependencies.

There are many ways to install `virtual environment (virtualenv)`, see the [Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/) guide for different platforms, but here are a couple:

- For Ubuntu
```bash
$ pip install virtualenv
```

- For Mac
```bash
$ pip install --upgrade virtualenv
```

Create a Python 3.6 virtual environment for this project and activate the virtualenv:
```bash
$ virtualenv -p python3.6 rt-peopletracking
$ source ./rt-peopletracking/bin/activate
```

Next, install the dependencies for the this project:
```bash
$ pip install -r requirements.txt
```

## TODO

- [x] Problem definition
- [ ] Data collection
- [ ] Data analysis and preparation
- [ ] Choosing the model
- [ ] Training the defined model
- [ ] Evaluating the trained model
- [ ] Fine-tuning the model
- [ ] Deploy

## References

- [Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/)
