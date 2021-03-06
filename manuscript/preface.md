# Preface 

"There is a lot to data processing that is not data science" (Provost & 
Fawcett, 2013).  **Data munging** (also called data wrangling, data jujitsu, 
data scrubbing, or data preparation) is the art of taking data from the wild 
and civilizing it so that it is integrated and well-structured for the sort of 
analysis you want to conduct.  Since big data is often about analytical re-use 
of data originally collected by someone else for some other purpose, data 
munging can take up the majority of a data scientist's time -- over 50%, in 
fact, according to a recent *NYT* article (Lohr, 2014).  It is ad hoc and 
improvisational work, though, rather than a science.

> "A good data munger excels at turning coffee into regular expressions and 
parsers, implemented in a high-level scripting language of choice... This is 
problem solving with programming, and quite different from statistics.  An 
aspiration toward excellence... is rarely rewarded, and often punished." 
(Driscoll, 2009)

If data munging is an art rather than a science, we cannot teach students to 
work with data by abstracting a set of general principles.  The hypothesis 
behind my writing this book is that, instead, the most effective approach might 
be to train our instincts by working through lots of different but similar 
problems via hands-on tutorials.  When complete, this book will include fifteen 
case studies---suitable for a 15-week university course---of increasingly 
"interesting" data munging problems.

The term **open data** denotes a movement toward greater public sharing of 
data, especially of data collected by government or government-funded 
institutions.  Recently there has been an explosion of great new data sources, 
often with well-structured and well-documented REST APIs, available from sites 
like [Data.gov](http://www.data.gov) and [Google Public 
Data](https://www.google.com/publicdata/directory).  This book's tutorials 
all use open data 
APIs that are likely to remain timely and stable for quite a while, and that 
are free of charge to access.  Learning how to retrieve data via HTTP web 
services in JSON and XML opens up a whole world of current, real-world data 
that you can use in business, research, and education.  And since we're not 
using canned data sets, you may even make unique new discoveries in real time 
as you do these exercises.

Gradually through 15 miniature data munging projects, readers will be exposed 
to Python and several of its most useful libraries for data science, including 
iPython and pandas.  If I do it right, you'll be so interested in what we're 
doing with the data, that you'll learn Python without even noticing it.  I 
don't want this to be a Python book that focuses on data preparation, but 
rather a data munging book that just happens to use Python.