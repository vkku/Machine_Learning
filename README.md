## About the course

This repository is for use with the Pearson Publishing (Safari) live webinars:

* "Beginner Machine Learning with `scikit-learn`."
* "Intermediate Machine Learning with `scikit-learn`."
* "Advances Machine Learning with `scikit-learn`."

Versions of this material are used by other training provided by David Mertz
and [KDM Training](http://kdm.training).

If you have attended one of the webinars using this material, I encourage you
to complete the survey on it at: [Machine Learning with scikit-learn
survey](https://goo.gl/pghpzD).  As folks fill this out, we will fold back the
updated answers into the dataset used in the lessons themselves.

## Installing training materials

Before attending this course, please configure the environments you will need.
Within the repository, find the file `requirements.txt` to install software
using `pip`, or the file `environment.yml` to install software using `conda`.
I.e.:

```bash
$ conda env create -f environment.yml
$ conda activate Pearson-ML
(Pearson-ML) $ jupyter notebook Outline.ipynb
```

Or

```bash
$ pip install -r requirements.txt
$ jupyter notebook Outline.ipynb
```


* [Documentation of scikit-learn](https://scikit-learn.org/stable/documentation.html)
