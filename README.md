**This syllabus is effective as of Thursday, February 08, 2018 at 08:30
PM**

# ANLY502 <br/> Massive Data Fundamentals <br/> Georgetown University <br/> Spring 2018

## Course Information

  - **Instructors:** Marck Vaisman (mv559 at georgetown.edu), Irina
    Vayndiner (iv95 at georgetown.edu)
  - **Classroom:** Car Barn 203
  - **Time:** Monday 6:30-9:00pm (except 1/10 which meets on a
    Wednesday)
  - **TA’s:**
      - Tiankai Guo (tg550 at georgetown.edu). Office hours: Wed
        9:30-11:30am at Car Barn 171
      - Jiahao Xu (jx94 at georgetown.edu). Office hours: Thurs
        4:00-6:00pm at Car Barn 171

## Course Description

Data is everywhere\! Many times, it’s just too big to work with
traditional tools. This is a hands-on, practical workshop style course
about using cloud computing resources to do analysis and manipulation of
datasets that are too large to fit on a single machine and/or analyzed
with traditional tools. The course will focus on Spark, MapReduce, the
Hadoop Ecosystem and other tools.

You will understand how to acquire and/or ingest the data, and then
massage, clean, transform, analyze, and model it within the context of
big data analytics. You will be able to think more programmatically and
logically about your big data needs, tools and issues.

## Credit Hours

This is a 3 credit graduate course. You will spend approximately 3 hours
per week in class. It is expected that you will spend approximately 2-3
hours of outside classroom activities (required readings, homework
problems, completion of labs, quizzes, etc.) for each hour of class
time. You will spend 36 hours in instructional time, and approximately
100 hours in out-of-classroom time.

## Course Objectives

  - Operate big data tools and cloud infrastructure, including Spark,
    MapReduce, Hadoop and other tools in the big data ecosystem
  - Recognize and use ancillary tools that support big data processing,
    including git and the Linux command line
  - Setup and manage big data infrastructure and tools in the cloud on
    Amazon Web Services
  - Identify resources and documentation to remain current with big data
    tools and developments
  - Execute a big data analytics exercise from start to finish: ingest,
    wrangle, clean, analyze and store
  - Be aware of the responsibilities that are associated with performing
    analysis of large datasets

## Prerequisites

  - Experience with the command line and terminal shell in Linux/OSX to
    navigate file system, manipulate files and directories (create,
    move, delete, etc). Understand file permissions.
  - Understand programming concepts (flow control, input/output,
    variable assignment.)
  - Experience with R, Python, SQL or other programming language for
    reading files, manipulating and analyzing data. **Note:** We will
    use Python as the primary interface to Apache Spark, through
    [PySpark](https://spark.apache.org/docs/0.9.0/python-programming-guide.html)
  - Experience with remote computing via ssh
  - Understand shell executables
  - Experience with version control tools such as git

# Course Materials

We have chosen several reference books for this course that cover
different parts of the material. We will assign readings for each class
from these books. These books are all available on [Safari Books
Online](https://www.safaribooksonline.com/), and you should be able to
access these resources. Our understanding is that as a Georgetown
student, you have access to these resources. Visit the [Georgetown
Library e-book information
page](https://guides.library.georgetown.edu/ebooks) for additional
information and click on “Safari Books Online”.

We may also provide supplemental materials to complement the books.
Articles, links, etc. will be posted on Canvas.

## Books (for assigned readings)

  - Benjamin Bengfort, Jenny Kim (2016). *Data Analytics with Hadoop: An
    Introduction for Data Scientists* O’Reilly Media. ISBN:
    9781491913703.
  - Ofer Mendelevitch, Casey Stella, Douglas Eadline (2016). *Practical
    Data Science with Hadoop and Spark: Designing and Building Effective
    Analytics at Scale*. Addison-Wesley Professional. ISBN:
    9780134024141.
  - Matei Zaharia, Bill Chambers (2017). *Spark: The Definitive Guide
    (Early Release)*. O’Reilly Media. ISBN: 9781491912157.

## Additional Recommended Books

  - Tomasz Drabas, Denny Lee (2017). *Learning Pyspark*. Packt
    Publishing. ISBN: 9781786463708.
  - Krishna Sankar (2016). *Fast Data Processing with Spark 2 - Third
    Edition*. Packt Publishing. ISBN: 9781784392574.

# Learning Activities and Evaluation

This is a hands-on, practical, workshop style course, that provides
opportunities to use the tools and techniques discussed in class.
Although this is not a programming course per se, there is programming
involved.

## Lectures and In-Class Labs

Every class session will have a lecture portion and many sessions will
have an in-class lab portion. The lab exercises are not graded and are
designed to get you familiar with the tools discussed in class. In these
labs, we will work through simple examples. The completion of lab
exercises is part of your in-class participation portion of the grade.

## Quizzes

There will be a total of 6 online quizzes about the topics/ideas
discussed in class and from the readings. The purpose of the quizzes is
to reinforce your knowledge about the tools and platform and also to
help you remember the nomenclature and terms used in class. The quizzes
will be online through [Canvas](http://canvas.georgetown.edu) and you
can take them at your convenience within the established time window.

## Assignments

You will be given problem sets as homework assignments. The goal of
these problem sets is to use the big data tools to answer some questions
about large datasets. The problem sets will build on the labs and will
be much more elaborate. Deliverables from the problem sets will usually
include code written for your programs and the output produced.

We will be using [GitHub Classroom](https://classroom.github.com/) for
problem sets and assignment submissions. When an assignment is created,
we will email you a link that will clone the assignment and create a
private repository for you. You will perform your work within the
repository and then push back to GitHub for submission. If you do not
have a [GitHub](http://www.github.com) account, please create one.

## Grading

  - Problem Sets: 60% (6 problem sets, 10% each)
  - Quizzes: 30% (6 online quizzes, 5% each)
  - Participation: 10% (in-class discussion, completion of in-class
    labs, active participation in online forums)

# Course Calendar

This calendar is subject to change. We will make make any changes known
in
advance.

| Date   | Session | Title                              | Topics                                                                                                       | Lab                                                                                                            | Reading                                                 | Assignment               | Quiz |
| :----- | ------: | :--------------------------------- | :----------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------ | :----------------------- | :--- |
| Jan 10 |       1 | Welcome to Massive Data Analytics  | Course Overview, What is Big Data, Distributed Computing, Cloud Computing, High Performance Computing        |                                                                                                                |                                                         |                          |      |
| Jan 22 |       2 | The Infrastructure of the Cloud    | Overview of major Cloud Computing providers (AWS and Azure), IAAS, PAAS and SAAS, Other Cloud providers      | Setup your environment, create SSH keys, start and connect to an instance in the cloud                         |                                                         |                          |      |
| Jan 29 |       3 | Database Systems                   | Overview of scalable database systems, Massively Parallel Processing databases, Neteeza, Greenplum, RedShift | TBD                                                                                                            |                                                         | A1 released - due Feb 11 |      |
| Feb 05 |       4 | Introduction to Hadoop & MapReduce | Hadoop, Distributed filesystems, MapReduce programming model                                                 | Start and connect to a cluster, Run built-in Hadoop examples on cluster, Examine the different user interfaces | Data Analytics with Hadoop (Bengfort, Kim) Chapter 2    |                          | Q1   |
| Feb 12 |       5 | Hadoop Streaming                   | Hadoop Streaming                                                                                             | Run the “Hello World” of Hadoop, the word count using Hadoop Streaming                                         | Data Analytics with Hadoop (Bengfort, Kim) Chapter 3    | A2 released - due Feb 25 | Q2   |
| Feb 26 |       6 | Higher Level APIs                  | Pig and Hive                                                                                                 | Store a dataset in a Hive table, Run and example Pig job                                                       | Data Analytics with Hadoop (Bengfort, Kim) Chapters 6,8 | A3 released - due Mar 11 | Q3   |
| Mar 12 |       7 | Introduction to Spark              | What is Spark, Resilient Distributed Datasets, PySpark                                                       | Start a PySpark session, Create RDDs, Operate on RDDs                                                          |                                                         | A4 released - due Mar 25 |      |
| Mar 19 |       8 | SparkSQL                           | SQL Review, Intro to SparkSQL                                                                                | Perform operations on Spark dataframes using SparkSQL                                                          |                                                         |                          | Q4   |
| Mar 26 |       9 | Machine Learning on Big Data       | SparkML, Issues with ML algorithms on large datasets                                                         | Build a model                                                                                                  |                                                         | A5 released - due Apr 15 |      |
| Apr 09 |      10 | Working with Streaming Datasets    | Spark Streaming                                                                                              | TBD                                                                                                            |                                                         |                          | Q5   |
| Apr 16 |      11 | NoSQL                              | NoSQL                                                                                                        | Store data in a NoSQL data store                                                                               |                                                         | A6 released - due Apr 22 |      |
| Apr 23 |      12 | Working with Graph Datasets        | GraphX API for Spark                                                                                         | Analyze a large graph                                                                                          |                                                         |                          | Q6   |
| Apr 30 |      13 | Other tools of interest            | Apache Drill, other topics TBD                                                                               |                                                                                                                |                                                         |                          |      |

**Class will not meet on Jan 15 (MLK Holiday), Feb 19 (President’s Day),
Mar 05 (Spring Break), Apr 02 (Easter Break).**

The topics for the last 4 sessions are placeholders, and it is very
likely we will cover these topics. However, we have some room for
flexibility depending on other topics of interest to the class. We may
also have a guest lecturer from time to time.

# Policies & Expectations

  - **Attendance:** Given the technical nature of this course, and the
    breadth of topics discussed, it is expected that you attend every
    class session. Please contact us in advance if you are not able to
    attend class.
  - **E-mail:** We will try to respond to email within 24 to 36 hours.
    Please use email for personal discussions and not for course
    questions.
  - **Online Discussion Boards:** Please use the discussion board on
    Canvas for questions about the course, homework assignments,
    technical issues, etc. Individual questions submitted by email do
    not scale, and the likelihood of many students having the same
    question is high. Using the forums is a great resource for everyone.
  - **Name Tents:** You will be given a name tent. Please use it every
    class session and place it in front of you so we can get to know
    your name quicker.

# Open Door Policy

Please approach or get in touch with us if something is not working for
you regarding the class, methods, etc. Our pledge to you is to provide
the best learning experience possible.

# Academic Integrity

You must perform all of your own work on problem sets. You may
collaborate with other students, though all submitted work must be your
own. Please refer to the [Georgetown University Honor
Council](https://honorcouncil.georgetown.edu/system/policies) site for
additional information.
