# Student Attendance and Participation Calculator

**Course:** ITM 7131 – Web Application Development  
**Institution:** Muni University, Faculty of Technoscience  
**Group:** 9  
**Application name:** AttendTrack – Student Attendance and Participation Calculator  


## 1. Project overview

AttendTrack is a front-end university utility application designed to help users review sample student attendance records, record attendance for a class session, monitor participation ratings, and check whether students meet a minimum attendance threshold.

The application is intended for demonstration by university students and teaching or academic-support staff. It uses invented sample records only.

## 2. Problem addressed

Tracking attendance manually can make it difficult to review attendance percentages and identify students who are below an institution's minimum attendance requirement. This application demonstrates a simple browser-based way to view sample records, search and filter them, record a sample session, and calculate eligibility.

## 3. Main features

1. **Dashboard:** displays the number of sample students, average attendance, number meeting the requirement, and number below the requirement.
2. **Attendance records:** displays student, course, sessions attended, attendance percentage, last attendance status, and eligibility.
3. **Search and filters:** searches by student name, student ID, or course; filters by course and last attendance status.
4. **Record attendance:** records a student's course, session date, attendance status, and participation rating, with validation and feedback.
5. **Attendance calculator:** allows the user to set a minimum requirement from 1% to 100% and recalculates eligibility.

## 4. Technology used

- HTML5 for page structure and forms.
- CSS3 for layout, styling, Flexbox, CSS Grid, and responsive layouts.
- Vanilla JavaScript for sample data, searching, filtering, validation, attendance calculations, and page updates.

No database, login, payment service, or server-side application is included.

## 5. Project structure

```text
student-attendence-calculator/
├── index.html
├── style.css
├── script.js
├── README.md
├── USER_GUIDE.md
└── TESTING_CHECKLIST.md
```

## 6. How to run the application

1. Download or clone this repository.
2. Extract the project folder if it was downloaded as a ZIP file.
3. Open `index.html` in a modern web browser.
4. Use the navigation links to move between Dashboard, Attendance Records, Record Attendance, and Calculator.

The application is front-end only and can be hosted using GitHub Pages or Netlify. Keep the HTML, CSS, and JavaScript files together in the same folder unless you update the file paths in `index.html`.

## 7. Important limitations

- The application uses ten invented sample student records.
- Attendance records added through the form are held in browser memory only. They are not saved to a database or permanently stored; refreshing or closing the page resets the changes.
- The sample session-record list used to detect duplicate submissions is also held in browser memory.
- The student and course lists are predefined in `script.js`; there is no interface for adding or deleting students or courses.
- This is an academic demonstration, not an official university attendance system.

## 8. Team members

The names below are reproduced from the ITM 7131 Group Project Submission Brief for Group 9. Add each member's registration number and confirm the spelling before submission.

| No. | Member name | Registration number |
|---:|---|---|
| 1 | Queen Nancy | _2601200843_ |
| 2 | Odama Marvin Jeremiah | _2601202481_ |
| 3 | Aita Derick | _2601202500_ |
| 4 | Nyipir Alex | _2601202188_ |
| 5 | Mercy Freda | _2501202338_ |
| 6 | Shaban Anago | _2601200835_ |

Do not claim work or commits for a member unless that member actually completed them. Update this table to match the group's agreed contribution record and GitHub history.

## 9. Acknowledgements

- HTML, CSS, and JavaScript were developed for the Group 9 ITM 7131 project.
- Sample student names, IDs, courses, and attendance figures are fictional demonstration data.
- _List any external libraries, code snippets, images, tutorials, or AI tools actually used, and state where/how they were used. If none were used, say so only after the group confirms._

## 10. Contribution and version-control evidence

Each group member should be added as a collaborator and make commits from their own GitHub account. Use clear commit messages that describe the change, for example:

- `Create attendance dashboard layout`
- `Add responsive styles for mobile screens`
- `Implement attendance percentage calculation`
- `Add form validation and success feedback`
- `Write project README and user guide`

The repository should be public for assessment. Do not upload passwords, API keys, or real student/staff personal data.
