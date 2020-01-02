# Curriculum Vitae

[![Build Status](https://travis-ci.org/woodjme/curriculumvitae.svg?branch=master)](https://travis-ci.org/woodjme/curriculumvitae)

[View Curriculum Vitae](https://cv.jamiewood.io/cv.pdf)

## Getting Started

### Building

* `docker build -t "latex" .`
* `docker run --rm -it -v $(pwd):/data latex xelatex cv.tex`
* OR `docker run --rm -it -v $(pwd):/data woodjme/tex xelatex cv.tex`
* `open cv.pdf`

## Acknowledgments

* [posquit0](https://github.com/posquit0/Awesome-CV)
