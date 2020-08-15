# MSDS593 Exploratory data analysis (EDA) at the University of San Francisco

This course introduces students to the key...

## Administrivia

**INSTRUCTORS.** [Yannet Interian](https://www.usfca.edu/faculty/yannet-interian) and [Terence Parr](http://parrt.cs.usfca.edu). We are professors in the [MS in data science program](https://www.usfca.edu/arts-sciences/graduate-programs/data-science); Terence was also the founding director of MSDS at USF.  Please call us Yannet and Terence or Professor.

**OFFICE HOURS**

* Yannet
* Terence is generally available on slack on-demand

**SPATIAL COORDINATES:**<br>

* All classes are remote but live online, courtesy of COVID-19.

**TEMPORAL COORDINATES.** Wed 25 August to Fri 9 October

Please note: California time is GMT-7 and all lectures will be over zoom and recorded. Recorded lectures will appear on Canvas.

Week one:

* Lectures are live but recorded for international students:
  * US timezone: Wed&Fri 2-4PM California time

* Live sessions for international students
  * Euro time zone: Thur 9-10AM California time
  * Asia time zone: Wed&Fri 7-8PM  California time

Following weeks:

* Lectures are live but recorded for international students:
  * US timezone: Tue&Thur 2-4PM California time

* Live sessions for international students
  * Euro time zone: Wed&Fri 9-10AM California time
  * Asia time zone: Tue&Thur 7-8PM  California time

**INSTRUCTION FORMAT**. Live class runs for 2 hours, 2 days/week. Instructor-student interaction during lecture is encouraged by speaking up in zoom. We'll often mix in mini-exercises / labs during class. All programming will be done in the Python 3 programming language, unless otherwise specified.

We will be interleaving lectures from Yannet on Tuesdays and Terence on Thursdays for the main lectures. Yannet will be in Tuesday evening and Wednesday morning sessions for internationals and Terence will be in Thursday evening and Friday morning sessions.

**COURSE BOOKS**. 

We will be using the following books available for free via the USF online library:

* [Storytelling with Data: A Data Visualization Guide for Business Professionals](https://learning.oreilly.com/library/view/storytelling-with-data/9781119002253/)
* [Storytelling with Data: Let’s Practice](https://learning.oreilly.com/library/view/storytelling-with-data/9781119621492/)
* [Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython ](https://learning.oreilly.com/library/view/python-for-data/9781491957653/). 

To get access, [start at USF](https://guides.usfca.edu/oreilly) and then you can jump to the various books.

**TARDINESS.** Please be on time for class and do not pop in and out of zoom as it can be distracting.


## Student evaluation

4 quizzes 40%
professionalism/attendance/labs 20%
4 (yannet) homeworks 20%
project 20%

| Artifact | Grade Weight | Due date |
|--------|--------|--------|
|professionalism/attendance/labs| 20% | |
|4 Homeworks| 20% | |
|Quiz 1| 10%| when? |
|Quiz 2| 10%|  |
|Quiz 3| 10%| |
|Quiz 4| 10%| |
|[Group Project](group-project.md)| 20%| Fri 9 October, Midnight California time|

Each project has a hard deadline and only those projects working correctly before the deadline get credit.

*I reserve the right to change projects until the day they are assigned.*

**Grading standards**. I consider an **A** grade to be above and beyond what most students have achieved. A **B** grade is an average grade for a student or what you could call "competence" in a business setting. A **C** grade means that you either did not or could not put forth the effort to achieve competence. Below **C** implies you did very little work or had great difficulty with the class compared to other students.

## Getting started

You should start out by watching video [A broad overview of python and tools used in our MSDS program](https://www.youtube.com/watch?v=d73hq8jCJ3s) on making sure you have the proper Python environment.  Make sure you have [Anaconda](https://www.anaconda.com/products/individual) installed and a very recent version. From the `Terminal` app, you should see the following (with `parrt` replaced with your user ID or name):

```
$ which python
/Users/parrt/opt/anaconda3/bin/python
$ python
Python 3.8.3 (default, Jul  2 2020, 11:26:31) 
[Clang 10.0.0 ] :: Anaconda, Inc. on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

You are to type `which python` and `python` at the `$` prompt to get those results. It indicates which version of Python you're using, which should be Anaconda-based:

```
/Users/parrt/opt/anaconda3/bin/python
```

and version 3.8 or above. Note that `/` is the path separator character and so, for example, `/Users/parrt/opt` means the `Users` directory under the root of the disk, `parrt` under that directory, and finally `opt` directory under that.

## Syllabus

We will be interleaving lectures from Yannet and Terence, but we can separate the topics into visualization, [pandas](https://pandas.pydata.org/) for data manipulation, and [matplotlib](https://matplotlib.org/) for basic plotting.

### Visualization

### Pandas

* introduction and overview of pandas; examples of the major components, what we can do
* fundamentals: key data types. df vs series. numpy relationship.  dealing with NaN for missing elements vs empty string. categorical versus numerical.
* selecting, slicing, method chaining, indexes
* sorting, removing duplicates, shuffle, sample
* dates, strings
* pattern matching during selection
* aggregation, grouping, binning, quantiles
* map function or dictionary to Series (apply?)
* merging/joining/stacking
* feather format

### Making plots with matplotlib

* bar chart, histogram
* scatter; alpha channel
* line plot
* boxplot
* bubble plot
* strip plot
* heatmap
* images (MNIST)
* display matrices
* overlaid plots for comparing variables; arrays of plots; shared axes
* drawing lines, shapes, text, annotations
* altering axes, labels; titles
* misc: legends, colorbar, linewidth, line style, colors
 
## Administrative details

**ACADEMIC HONESTY**. You must abide by the copyright laws of the United States and academic honesty policies of USF. You may not copy code from other current or previous students. All suspicious activity will be investigated and, if warranted, passed to the Dean of Sciences for action.  Copying answers or code from other students or sources during a quiz, exam, or for a project is a violation of the university’s honor code and will be treated as such. Plagiarism consists of copying material from any source and passing off that material as your own original work. Plagiarism is plagiarism: it does not matter if the source being copied is on the Internet, from a book or textbook, or from quizzes or problem sets written up by other students. Giving code or showing code to another student is also considered a violation.

The golden rule: **You must never represent another person’s work as your own.**

If you ever have questions about what constitutes plagiarism, cheating, or academic dishonesty in my course, please feel free to ask me.

*All persons with common code are likely to be considered at fault.*

### USF policies and legal declarations

*Students with Disabilities*

If you are a student with a disability or disabling condition, or if you think you may have a disability, please contact [USF Student Disability Services](https://myusf.usfca.edu/sds) (SDS) for information about accommodations.

*Behavioral Expectations*

All students are expected to behave in accordance with the [Student Conduct Code](https://myusf.usfca.edu/fogcutter/student-conduct) and other University policies.

*Academic Integrity*

USF upholds the standards of honesty and integrity from all members of the academic community. All students are expected to know and adhere to the University's [Honor Code](https://myusf.usfca.edu/academic-integrity/honor-code)

*Counseling and Psychological Services (CAPS)*

CAPS provides confidential, free [counseling](https://myusf.usfca.edu/caps) to student members of our community.

*Confidentiality, Mandatory Reporting, and Sexual Assault*

For information and resources regarding sexual misconduct or assault visit the <a href="https://myusf.usfca.edu/title-ix">Title IX</a> coordinator or USFs <a href="http://usfca.callistocampus.org">Callisto website</a>.
