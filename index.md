## Assignment index

[Assignment 1](https://parulprogramminghub.github.io/assignments/assignment1)


### Getting started

Create .py file for each questions, you don't need to push screenshots of the output, We have setup continuous integration system which will test your code by own, you need to add .travis.yml file in order to get this service to your repo.
Add following config in that file.

```markdown

language: python
python:
    - "2.7"
before_install:
    - pip install pytest pytest-cov
script:
    - py.test

```
