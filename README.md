# Introduction to Programming for Psychologists & Neuroscientists (AKA PSYC161, #34529)

* **Instructor:** Yaroslav Halchenko, [class-psyc161@onerussian.com](mailto:class-psyc161@onerussian.com)
* **Venue:** Moore Hall 453 (computer lab)
* **Need help?**
   * [Google it up](http://google.com)
   * **Office Hours:** just [email me](mailto:class-psyc161@onerussian.com) to set time convenient for both of us
   * [Email me](mailto:class-psyc161@onerussian.com)

## Course Objectives

Neuroimaging, computational neuroscience and other fields of brain
research directions are becoming more and more data driven and
employing sophisticated computational methods and paradigms, such as
distributed and cloud computing.  That is why it becomes critical for
new researchers to develop at least basic skills in programming,
software engineering, code and data management. This course intends to
provide wide in scope and introductory in depth coverage of many
important topics in programming,  software engineering and some data
structures and algorithms to streamline students current and future
research projects. It will be practice and interaction oriented in
its format: lectures will be interleaved within practice hands-on
sessions. Although some topics and home exercises will involve using
established data analysis frameworks, primary accent will be done on
getting a good grasp of good coding and software developing
practices. Thus, this course is intended to serve as a prerequisite to
possible follow-up course(s) which would concentrate on in-depth
learning of specific neuroimaging (and/or computational neuroscience)
frameworks (from stimuli delivery to advanced analysis pipelines).

# Resources

## Software

Neuroimaging could be considered a somewhat exemplar field of science
since nearly all scientific software for fMRI and EEG/MEG data
analysis was developed as a free and open source software (FOSS).
Moreover, with recent developments of stimuli delivery toolboxes
(e.g., psychtoolbox-3, PsychoPy, OpenSesame) it became possible to
provide a complete free and open toolbelt for carrying out research in
this domain.  Therefore, in this course we will use/cover available
FOSS tools (e.g., bash, git), programming languages (Python) and then
overview computation environments (Matlab/Octave, R). Those tools are
available for any major operating system (Linux, OS X, MS Windows) but
students will be encouraged to use a turnkey platform for neuroscience
-- [NeuroDebian](http://neuro.debian.net) -- where all (but Matlab)
aforementioned (and thousands of other) tools are conveniently
available.

TODO: URL to pre-crafted VM

To establish efficient hands-on sessions and code development in
Python, we will use and recommend you to use in your research/coding
practice:

- [IPython notebooks](http://ipython.org/notebook.html) . Available
  for all platforms.  Stock Debian/Ubuntu distributions:
  `ipython-notebook` package
- [PyCharm](https://www.jetbrains.com/pycharm) community edition.
  NeuroDebian (-devel) provides now pycharm-community-sloppy
  package

## Data

We might possibly use some publicly available dataset as an example
for hands-on sessions. For your project(s), you are welcome to use any
publicly available dataset.

## Format

This course is planned as a graduate level seminar course for the
Spring 2015 semester -- Apr 2nd to June 2nd -- so we will have roughly
9 weeks.  Each week we will have either one 3h (2:00-5:00pm) or two
1h:30m (3:30pm-5:00pm) classes, which would be a mix of small lectures
and practice sessions.  Practice sessions would include “pair
programming” and “code review” sessions.  Homeworks will be submitted
via Git (further instructions **TODO**).  Students will learn how to and
will be encouraged to contribute to existing free and open-source
projects.

## Literature

The two main sources for lesson materials are:

**THP**
    Downey, A. (2012). [Think Python: How to think like a computer
    scientist. Needham, MA: Green Tea Press](http://greenteapress.com/thinkpython/thinkpython.html)

**PSL**
    Haenel, V., Gouillart, E., & Varoquaux, G. (Eds.) (2011). [Python
    Scientific Lecture Notes](http://scipy-lectures.github.com/)

Both books are available online (free and open), and you can fetch PDF
directly using git-annex (`git annex get books/`)

In addition, we will make use of a number of other online resources,
including documentation and user manuals for the various libraries and
packages that you will be learning to use.

## Master plan/schedule


| Date | Times       | Content | Reading
|:---- | ----------- | ------- | -------
|Apr 2 | 2:00-5:00pm | Python Language Concepts / Git/GitHub | THP(1-12), [PSL(1.2.1-1.2.5)](http://scipy-lectures.github.io/intro/language/python_language.html), [git bootcamp materials](git-bootcamp)

[git-bootcamp]: http://nbviewer.ipython.org/github/dartmouth-pbs/reprosw/blob/master/Version%20Control.ipynb "Git bootcamp"

## Student Evaluation

Students will be evaluated on the basis of:

- Lesson exercises (50 pts) / class participation (10 pts)

  Every week there will be a set of small exercises to be submitted
  for the first class in the upcoming week

- Final project (40 pts), given 3-4 final weeks to work on.

## Final project

Students will choose a project of their liking

- It must be a new development (i.e. not something you did before this
  course), although you can choose to improve upon your prior code

- Contributions to existing scientific projects will be strongly
  encouraged

- Possible projects will be suggested and discussed in the class on
  4-5th week and possible domains would be

   - Data structures/algorithms implementation
   - Stimuli/experiment
   - Data Analysis
   - Establishing/improving quality assurance (tests, etc) of an
     existing scientific FOSS project


