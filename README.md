# Observations Project 

## Description
The purpose of this project is to develop a system to assess and evaluate teaching performance in undergraduate STEM courses. It can be broken into four parts: 
- Cleaning the Data
- Descriptive Statistics
- Exploratory Factor Analyses and Face Validity
- Inter-Rater Reliability

## Rating System
The 43 Likert Scale items we are considering are split between two populations: Instructors and Students. Each numerical index corresponds to the relevant column in the ratings table or row in the descriptive statisitics table. Data such as the number of students enrolled in a given course and the number of students attending an observed class are given as a percentage. Observers are denoted as 1, 2 and 3 where relevant.

Likert Scale items are coded as 1, 2, 3, 4 corresponding to the four categories in the instructor ratings (Not at all, Somewhat, Satisfactory, and Outstanding) and as 1, 2, 3, 4, 5 corresponding to the five categories in your student ratings (None, Few, Some, Many, Most).

### Instructor items:
The instructor...
- provides objectives for the class session (written, verbal, or both).

- relates the session content to learning outcomes for the course.

- uses visual aids that are clear, organized, and relevant.

- uses practical, “real-world” examples to support teaching.

- refers to the relevant portions of the textbook, reading, or other supplement.

- uses humor effectively to promote student engagement and rapport.

- answers questions well and demonstrates knowledge of the subject.

- shows clear interest or enthusiasm in teaching.

- uses student names.

- asks specific questions.

- pauses after asking a question.

- asks questions of students that result in responses from students.

- changes gears periodically from one style of teaching to another.

- engages students periodically through think/pair/share, problem solving, or other active learning exercises.

- uses guided notes.

- involves students periodically in what is to be covered during the session.

- uses more than one way to explain problems or concepts.

- is able to get students’ attention at the opening of the class session.

- provides a summary of what has been covered and accomplished at the end of the observed session.

- provides a preview of the next session or ideas of what to consider for the next class at the end of the observed session.

- could be easily heard.

- moves around in the classroom and refrains from standing/sitting in one place.

- uses analogies or metaphors to relate the concepts to students’ experience.

- emphasizes key points throughout the observed session.

- makes eye contact with students.

- uses open (not closed) body language during the observed session.

- engages in behaviors that develop rapport and trust with the students.

- relates the material/concepts to personal or societal concerns.

- is available before class.

- is available after class.

### Student items:
Students...
- maintain attention toward the instructor (for example – eye contact).

- remain awake and alert during the observed session.

- are using their cell phones or other electronic devices in activities unrelated to class.

- are over one minute late to class.

- pack up early at the end of class.

- are reading the newspaper or doing other non-electronic activities unrelated to class.

- interact with the instructor before class.

- interact with the instructor after class.

- initiate questions.

- respond to questions posed by the instructor.

- ask follow up questions.

- participate in class when asked to do so by the instructor.

- are taking notes.

## Current Limitations and Ideas for Improvements:¶

- The desired entries of the tables in the observation forms must begin with an `'X'`. An improvement would be to consider any text entry as a valid indicator of nonzero data.

- All other entries should be left blank. The program will convert blank entries to `0`'s.

- Only supports windows

- `win32.Dispatch("Word.Application")` will apparently open up any observation.docx inputted under some circumstances, so don't be alarmed if several Word documents open up as the script runs.

## Resources:
- https://stackoverflow.com/questions/10366596/how-to-read-contents-of-an-table-in-ms-word-file-using-python/33775294#33775294

- https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.DataFrame.plot.html

- https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.DataFrame.plot.html
