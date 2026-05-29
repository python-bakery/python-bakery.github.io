Hello, and welcome to the Python Bakery! This is an open-source CS1 curriculum, with all batteries included. Or at least, that's our goal.

This page is meant for instructors teaching the course.

For instructors, please read over this page to learn more about the teaching philosophy, goals, and suggestions for how to teach with this course. Thanks for giving us a shot!

The Python Bakery
=================

Our goal is to provide a CS1 curriculum for instructors who want to teach Computer Science with a modern version of Python. Although our original audience was freshmen Computer Science majors at an R1 university, we hope to develop a curriculum that can work for high school students.

**Primary Learning Goal**: The goal of the course is not to teach programming, Python, or Software Engineering. The goal of the course is to teach the fundamentals of Computer Science, _through_ programming in Python. Students are not likely to see the difference, but instructors should. The goal is to teach a kind of problem-solving that is more enduring than just what a single language provides. Of course, it's virtually impossible to do that without teaching an awful lot of programming material - we believe that is a feature, not a drawback.

**Prior Knowledge**: The curriculum does not expect students to have prior Computer Science knowledge. Indeed, we recommend you use our pretest to identify students who do not belong in this course and promote them out (we usually reserve this for students who make excellent progress on the final programming problem, on their own, but we do interview each one of them individually). Students should be able to come in having never programmed before, although our data reflects that prior experience is associated with higher final exam scores (shocker, I know).

The curriculum requires little math, mostly just algebra. And even that Algebra knowledge is pretty limited (there's a few questions early on that students might need help with, if they have weaker math skills).

Students do need computers and reliable access to the internet, even during classroom activities. This is not an unplugged curriculum.

**Size of Audience**: All the assignments are meant to scale to hundreds of students. The textbook is fully autograded and requires minimal oversight. The classroom activities are oriented around group submissions or autograded individual assignments. To be truly manageable, you will need teaching assistants, but a substantial portion of this Staff Course is built for teaching and managing them.

Curriculum Infrastructure
-------------------------

The first Canvas course that you get is the `Staff Course`. This course holds not only the "instructor guide" for the curriculum, but also a way to track the teaching assistants, giving them feedback, and making sure they are working reliably. Students will never see this course (and please never give them access!).

Separately, you will have one or more `Student Canvas Courses`, forked from the template `Student Staging Course`. We recommend combining as many of these as you can, to reduce bookkeeping and copy/paste errors. Your institution may have rules about this (our's sure does). However, this is where students actually go to complete assignments.

The actual textbook, quizzes, and coding assignments are secretly delivered through `BlockPy Bakery Curriculum`, which is a BlockPy course embedded in Canvas via LTI. We suggest using our platform if only for its LTI connection to Canvas (allowing automatic student registration and grade passback). Technically, there is also a second BlockPy course for the exams, but we do not provide access to external instructors to that course. There will also be separate BlockPy courses automatically created for each corresponding `Student Canvas Course`. And finally, there's also a BlockPy course for the practice problems.

There are some Poll Everywhere questions that we provide for the lectures; these are kept on the Poll Everywhere site. We share them with our instructors using the PE mechanism, but external instructors may find it easier to make their own copy.

One last critical resource that we provide is the `Bakery Google Drive` ([link](https://drive.google.com/drive/u/1/folders/0ALfjp1_QSZwfUk9PVA)). This is where we hold our lecture/practicum slides, worksheets and reference solutions, and the form templates that we suggest using. In addition to our Drive, you will almost certainly want to create your own Google Drive to house your version of the course materials.

Course Structure
----------------

The course is designed with two major threads: the in-person classroom activities (divided into instructor-led Lecture and TA-led Practicum) and the asynchronous textbook readings/quizzes/coding problems. The material in these two threads overlaps, but is actually distinct: we use the textbook to teach the fundamentals, and then classtime to explore bigger, squishier ideas (seeking help, debugging, thinking about good test cases, ethics).

What did we mean by "Batteries Included"? Well, besides the nod to [Python's philosophy](https://peps.python.org/pep-0206/), we mean that we're trying to make instructors lives easier by providing all the things that you might need to teach the course. That includes:

*   A textbook for students
    *   With illustrations and graphics
    *   With narrated videos
    *   With PDF versions
    *   With runnable code examples
    *   With metrics about how long students spend reading each lesson
    *   With documented learning objectives
    *   With CSTA Standards
*   Programming problems and quiz questions
    *   With correct reference answers
    *   With autograding code/logic
    *   With statistical measures of difficulty and discrimination from past semesters
    *   With notes about which questions are particularly difficult and how to help teach them
*   Weekly in-person assignments
    *   With one for lecture (instructor-led session) and one for lab (TA-led session)
    *   With slides
    *   With worksheet/coding activity
    *   With reference answer
    *   With grading rubric and instructions
    *   With statistical measures of difficult and discrimination from past semesters
    *   With example student answers
    *   With in-class poll questions to warm everyone up and keep things interesting
*   Multiple Projects of various sizes
    *   With autograding code
    *   With correct reference answers
    *   With the full write-up
*   Surveys to get to know your students
    *   With questions related to motivational constructs and engagement practices

We won't pretend that we have all this for the entire curriculum, _yet_. The goal is to eventually package all of this into one convenient place. We're actually pretty close to _having_ all this data, it's mostly just been a matter of formally dumping it so that you have access to it. Please bear with us!

Textbook Structure
------------------

The Bakery textbook is delivered through BlockPy, embeded as an LTI tool in Canvas. The material is divided into almost a dozen `Chapters`, with each chapter meant to approximate a single week of the course. Some weeks represent projects and/or exams, but most have the same recurring substructure:

*   Primer
*   Part A
*   Part B

The `Primer` summarizes the entire chapter briefly, to give a "sneak preview" of what they are learning. The Primer to be read before students come to lecture/practicum that week.

The other two `Parts` are the actual content, broken up into a semi-weekly cadence (otherwise students try to wait until the end of the week to get started). The major element of the parts are the `Lessons`, of which there are 2-8 (the quantity decreases as the semester moves along). Each lesson has a `Reading` (provided as text or a video) followed by a mastery `Quiz` (multiple choice, true/false, matching, fill-in-the-blank, etc.). Most lessons also have several `Coding Problems` associated with them. This material makes up the bulk of the course's actual learning content.

All of the textbook is autograded and attempts to give feedback. We discuss this more later on with the [Pedal](#pedal-semi-automated-feedback-and-autograding) system. You should definitely look through the assignments on Canvas to understand what your students are expected to do each week. You may also find it helpful to consult the flat [Bakery Textbook View](https://blockpy.cis.udel.edu/assignments/textbook/bakery_textbook) of _just_ the Readings.

### Textbook Curriculum

The diagram below captures all of the topics that we aim to cover, and roughly their order. We place the topics loosely on the spectrum from Data (Abstraction) to Algorithms.

<img alt="Overview Diagram of the Bakery curriculum topics" src="https://github.com/user-attachments/assets/ee6c30fb-ece8-4a9e-bb94-313ff83e9959" />


*   Chapter 1 (Introduction): Covers the basics of Computer Science and programming. This appears to be one of the longest chapters, but is actually one of the easiest and shortest. There is a lot of ground to cover, but the pace is very gentle.
    *   Part A: Explains what a program is and the basic input-processing-output model. Covers basics of values and types, simple math and logic, and interactive evaluation of expressions.
    *   Part B: Explains variables and assignment statements. Introduces the idea of modules and organizing code with comments and imports. The last bit is about strings and string operations (e.g., slicing). Also covers the idea of errors/exceptions.
*   Chapter 2 (Functions): Introduces the idea of functions as "the smallest atomic unit of programming". This chapter is a little harder than the previous, but students usually don't struggle too much.
    *   Part A: Starts off with how to call functions and methods, the ideas of parameters and arguments, and some common built-in Python functions. Then spends a long time explaining the syntax of functions, how `return` works, and type signatures. Testing functions is introduced almost immediately afterwards, and is used throughout the rest of the book a lot.
    *   Part B: Covers more confusing aspects of functions, like the scope rules (do not write variables out of scope) and how bodies work. Also explains docstrings, although students tend to gloss over this more than they should. The most important part (and the part that students hit their first major struggle with) is about data flow: having functions call other functions and pass data between them. The Part ends with more about external functions available in Python, and how to read their documentation (by introducing the [Designer game library](https://designer-edu.github.io/designer/)).
*   Chapter 3 (If Statements): Covers the idea of `if` statements in Python, as a way of doing branching logic.
    *   Part A: Covers the basic `if` and `else` structure, without any nesting. Spends a lot of time on syntax and tracing. Also explains the idea of truthiness in expressions (using non-Boolean expressions as conditionals).
    *   Part B: Covers nesting `if` statements and `elif` statements, in terms of syntax, semantics, and behavior. Also covers the idea of unnecessary `if` statements (when a Boolean expression could be returned directly) and Unnecessary Tests (when students test if a Boolean value is `==True`). A considerable amount of time is spent on "logical patterns", to give students more examples and mental schemas for using `if` statements. The Chapter ends with more information about Designer, this time covering events (introduced as a separate kind of execution model, not native to Python).
*   Chapter 4 (Structures): Introduces two different kinds of data structures: dataclasses and lists.
    *   Part A: Dataclasses are introduced as a "struct" type to hold heterogenous record data and to create new types. Students are shown the class definition syntax and taught about the constructor. They access attributes, and define functions that consume and produce dataclasses. There is a brief diversion lesson about Worlds in Designer, which is when you use a dataclass to make a more interesting game with multiple components.
    *   Part B: Lists are next introduced as the homogenous sequential data type. Remember, lists are not arrays! Students are taught list operations, including membership tests, slicing, and appending elements to lists. Mutability is introduced here (although students have a lot of trouble).
*   Chapter 5 (Project 1): At this point in time, we take a break to do a project (usually 3-card poker) and have the first exam. Everyone catches their breath.
*   Chapter 6 (For Loops): The first looping construct we teach is `for` loops, as a safe collection-based form of iteration. At this point, students are only going to iterate over lists of primitive values (strings, integers, floats, and Booleans).
    *   Part A: The first lesson is about the syntax, semantics, and behavior of `for` loops. We don't have them do much here, mostly they're just trying to understand the code. However, we then introduce the first set of Loop Patterns, which dominate the rest of this chapter as a tool for writing loop code. The basic patterns are Summing, Counting, Accumulating (a generalization of Summing), Mapping (making a new list based off an old list), and Filtering (using an `if` statement to optionally remove some elements). In general, students are shown how to modify a list immutably by creating a new list based off the old list.
    *   Part B: The next lesson is about the rest of the loop patterns. First is the Find pattern (returning an element in the list that matches a condition; either the first element or the last, depending on the pattern variant). Then is the Take pattern, where you return elements of a list as a new list, up until a certain condition is met (compare to slicing, which uses a specific index instead of a condition). Then there is the Minimum/Maximum pattern, which is one of the most complicated for students. However, the hardest part of the chapter is the last lesson, where students are asked to decompose complex problems into helper functions by composing the loop patterns we have taught them. Some of these questions are among the toughest in the course for students!
*   Chapter 7 (Sequences): This chapter is a bit of a grab-bag of things related to sequences.
    *   Part A: First the idea of indexes are revisted, with time spent on accessing specific elements of lists both to read AND update. This is a chance to explain the difference between value iteration (the default behavior of `for` loops), index iteration (using the `range` and `len` functions), and combining the two with `enumerate`. Students get to mutate a list a little, though we discourage this. The other lesson covers the basics of iterating through a string and the use of the `split` method.
    *   Part B: Exposes students to the idea of file systems and the basic of shell commands (though admittedly they do not do much with those). More time is spent on the other lesson, where they read data from files using the `open` function. Files are traversed either as a sequence of lines or as a single string via `read` method.
*   Chapter 8 (Nesting Data): One of the last major escalations, this takes students from list of primitive values to lists of dataclass instances. It's technically nothing they haven't seen before, but it still becomes MUCH harder.
    *   Part A: This chapter introduces the idea of nesting dataclasses inside of lists and then inside of dataclasses. The former revists all the previous Loop Patterns, albeit with more complexity. The latter is actually not too difficult for students, and is relatively short.
    *   Part B: This chapter first covers 2D lists (lists inside of lists). This requires coverage of nested iteration, which surprisingly isn't too bad for the students. The second half, though, is heavily nested data where there are multiple layers of lists and dataclasses. We use this opportunity to show UML diagrams in order to capture the relationships and scaffold their understanding.
*   Chapter 9 (Project 2): Another project (the Crypto Corgi, usually, although that only focuses on Chapter 7 material and not Chapter 8) and another exam.
*   Chapter 10 (While and Plotting): The chapters start being more grab-bag and variable here. We have mixed this content around a bit sometimes.
    *   Part A: This is usually `while` loops, since those are a critical topic. We show the syntax, semantics, and behavior, and then teach some patterns. However, we generally steer students a bit more towards `for` loops since those are a safer form of iteration. This also introduces the idea of infinite loops.
    *   Part B: A short lesson on Plotting is here, mostly built off the lists-of-dataclasses material. The only plots covered (using Matplotlib) are histograms, line plots, and scatter plots.
*   Chapter 11 (Time and Trees): This chapter might seem a little random, and it kind of is. It's "all the rest of the good CS stuff".
    *   Part A: The first lesson is about Time Complexity. We do not talk about Big Oh, but focus instead of the RAM model and case analysis. To motiviate the discussion, the next lesson goes into binary search and sorting as concrete algorithms to study.
    *   Part B: The last lesson is one of the most difficult and chonkiest, about recursion and trees. This actually even covers a bit of object-oriented programming (inheritance). The reason is that statically type checking recursive data in Python is still a huge pain. We teach students a form of Trees with an abstract base class that has a null `EMPTY` instance and then an implementing `BinaryTree` subclass for holding actual data. This works safely, and allows us to cover structural recursion (although we leave generative recursion aside).

The Role of the Classroom
-------------------------

We mentioned the divide between textbook and classroom activities. We think that the time spent in the classroom is the most valuable time you have. Your primary goal should be to develop a meaningful learning community where all of your students feel welcome and engaged with the course. They should get to know you, the staff, and their classmates. They should feel welcome to ask questions and to not know things. Community, culture, and relationships are the key to successful teaching. Never forget that!

Some of the activities we suggest are more about building up community than strictly about the core content. Many of the activities are about developing their abilities to work in groups, to dissect ethics, to prevent imposter syndrome, and otherwise develop their so-called "softer" skills (which are often more important than their coding skills, in the long run).

There are also a lot of high-level concepts that will not really land for students until they have been programming for a while: good variable naming, the power of writing good tests, how to decompose complicated functions... These are ideas that only take root when you've had to fight really terrible codebases. We cover them in lecture, but recognize that your job is to expose the students, not to build mastery.

Scaling enrollments often means that students will compete with hundreds of classmates for their instructors attention. You cannot be everywhere all the time, so you probably have teaching assistants, who may host their own lab. We call these sessions the Practicum, and encourage teaching assistants to build as much community as possible there. These smaller in-person learning experiences have potential to be more impactful thanks to their smaller, more intimate nature. We encourage you to give your teaching staff agency in these sessions and for them to get to know each of their assigned students.

In addition to the lecture and practicum (lab), we encourage you to adopt an asychronous chat platform, like Discord or Slack. If you can get students to engage there, that is also a form of community. Recognize and remember that not everyone may want to participate there, though, including students who are particularly vulnerable.

### Classroom Curriculum

So what do we actually do in the classroom? Each week is described below; the parenthetical next to the week describes what the textbook is covering.

*   Week 1 (Introduction):
    *   Lecture: We spend a lot of time on the syllabus, and then do a fun little game where they are "computers" and "programmers". The "programmers" are given a word, and have to give instructions to the "computers" to draw and guess that word. The catch is that they can only use simple primitive shapes (e.g., "a blue square below a big red circle"). This tries to cover the fundamental ideas of Abstraction and Algorithms.
    *   Practicum: We usually cancel practicum the first week because things are just too hectic and TA assignments usually aren't finished. We sometimes provide that time as a chance to help students get things set up.
*   Week 2 (Functions):
    *   Lecture: This lecture is all about seeking help. We explain good strategies for how to ask for help and provide them structure for doing so correctly. The activity has them work in groups to respond to scenarios where people need help.
    *   Practicum: This practicum is meant to reinforce the material about functions. Students are asked conceptual questions about functions and respond to them in groups. It's also a chance for TAs to introduce themselves.
*   Week 3 (If Statements):
    *   Lecture: This lecture is about Code Coverage and the value of writing good tests. They do a game called Wheats and Chaffs, where we have a bunch of broken and working programs. Students have to write test cases that pass the good programs (wheats) and break/fail on the bad programs (chaffs). This imparts the idea of "Validity" and "Thoroughness" in tests. Students struggle a lot with this game, although that is very good for them because it's a great critical thinking activity. The delivery is a BlockPy coding assignment rather than a google doc, so students submit individually but still work together in pairs.
    *   Practicum: This practicum is meant to reinforce the material about `if` statements. Students work together in groups to trace a big complicated set of function calls that involve `if` statements.
*   Week 4 (Structures):
    *   Lecture: This lecture is about making "abstractions" out of real world data. Mostly, they are making up dataclasses to represent something with complex multiple parts. You have to watch them on this, they make SO MANY mistakes from not reading the instructions.
    *   Practicum: This practicum is meant to reinforce the material about mutability. Students have to make predictions about whether different data types will be mutated during function calls. They struggle with this stuff.
*   Week 5 (Project 1/Midterm 1):
    *   Lecture: A classwide discussion about Imposter Syndrome, and the effects of underepresentation in Computer Science on society. Students complete a worksheet together, but a lot of this is about sending them a message, I think.
    *   Practicum: Students work on the project and get help from the TAs.
*   Week 6 (For Loops):
    *   Lecture: This is all about how to interpret decomposed complex functions. Students are given a large program that iterates through lists of primitive data, and must trace out its values. Honestly, we need to revisit this activity because they just don't know how to follow instructions.
    *   Practicum: This practicum is meant to reinforce the material about `for` loops. Students answer questions about lists of strings related to cards, figuring out what kind of loop patterns they would apply.
*   Week 7 (Sequences):
    *   Lecture: The lecture material is about debugging complex functions, and the power of unit testing and decomposition. The activity is the "Flower Garden", where they given two different versions of a complex function, one where the logic is decomposed and one where it is not. The code of the functions is broken in five places each, but correct unit tests are provided. Students have to debug the logic in groups (submitted individually through BlockPy).
    *   Practicum: This practicum is off the reservation by having students complete a Designer tutorial to make a little game where they click on a teleporting emoji. This is good if you want students to eventually make a Designer game, but probably not as relevant otherwise.
*   Week 8 (Nesting Data):
    *   Lecture: Students work in pairs or individually on an autograded coding assignment called the Monster Mash. This is meant to reinforce the Nested Data material of this chapter. It's important that students complete the material this week before making too serious an attempt, which is probably an issue we should revisit.
    *   Practicum: Unlike other weeks, there is no independent assignment in Practicum. Students work on the same problem that they had in lecture, the Monster Mash.
*   Week 9 (Project 2/Midterm 2):
    *   Lecture: The lecture material is about web requests via `request` and our own custom libraries (critical for setting up the final project). Students work on a long worksheet that has great material but might be a bit too long.
    *   Practicum: For CS majors, this lab is all about asking the TA questions about the Computer Science degree, signing up for classes, and stuff like that. But for all students, it's also a chance to ask for help reviewing for the exam this week and to get help on the project.
*   Week 10 (While Loops, Plotting):
    *   Lecture: The final project is introduced and students are given time to work on it during lecture.
    *   Practicum: Time to work on the project.
*   Week 11 (Recursion and Trees):
    *   Lecture: Time complexity analysis
    *   Practicum: Time to work on the project
*   Week 12:
    *   Lecture: I have been planning a lesson on Ethics in CS here for years, but have never had my stuff together in time. Fingers crossed we have something this time...
    *   Practicum: Time to work on the project.
*   Week 13 (Thanksgiving Break)
    *   Lecture and Practicum: Cancelled.
*   Week 14:
    *   Lecture: Time to work on the project.
    *   Practicum: Time to work on the project.
*   Week 15:
    *   Lecture: Final lecture! We wrap up the course and leave them with parting words of advice.
    *   Practicum: Tearful goodbyes, I assume. Also time to work on the project.

What About Cheating?
--------------------

A common question is, "if everything is open-source, won't my students cheat?"

*   Your students already probably have a lot of ways to cheat: finding answers on sites like Cheggs, hiring someone, asking ChatGPT.
*   Students who abuse shortcuts are likely to hurt themselves more than help themselves; we strongly encourage instructors to convince the students to put in the work honestly.
*   We try to put some simple barriers up for some of the more delicate materials, like the reference answers. We expect instructors to request permission to get access to those repositories.
*   We strongly encourage instructors to use automated systems that detect cheating (e.g., similarity detection, students who instantly get problems right on the first attempt without spending long writing) and penalize those students.
*   Our exams _are_ kept secret. We do not share those outside of our own offering of the course, though we do provide an [Assessment Guide](https://example.com) with instructions about how to make your exams like our's.
*   You don't have to use anything we offer; you are free to use it as a base!
*   We're trying to figure this out ourselves. It's a hard problem to solve...

Pedal: Semi-automated Feedback and Autograding
----------------------------------------------

Earlier, we referred to "autograding code/logic". This is all done through Pedal, a Python library for semi-automated feedback of student Python code. Think of Pedal as a collection of tools that can analyze student code to give feedback and evaluate correctness. This is more than just unit testing (although it does do unit testing) - there are tools for syntactical structure analysis, liveness checking, type checking, and so much more. Its feedback is meant to be focused on beginners and avoids many of the issues that conventional error messages and simple unit testing feedback introduces.

A classic example is when a unit test fails, the error shown to students will often show that the instructor code failed; some students may complain that their code is perfect, instead the instructor code is broken. However, they fail to understand that the instructor code worked perfectly, the error was in the function that students defined. Although eventually students must understand this anyway, Pedal will manipulate stack traces to make it clear that errors are in the students' code and not the instructors.

More information about Pedal can be found on its own page: [https://pedal-edu.github.io/](https://pedal-edu.github.io/)
