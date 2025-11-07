🎓 Beacon: Student Tutoring Form Generator

Beacon is a simple, single-file, zero-dependency web application designed for educators. It takes a CSV export of failing students and generates individual, printable tutoring sign-off forms for each student, prioritized by their grade.

This tool runs entirely in your browser. No data is ever uploaded to a server, ensuring student privacy.

Features

CSV Upload: Accepts a standard CSV file with student, class, grade, and teacher info.

Printable Forms: Generates clean, individual sign-off sheets for each student.

Prioritization: Automatically lists a student's failing classes, sorted by lowest grade (highest priority) or highest grade.

Teacher Name Cleaning: Intelligently cleans up teacher names (e.g., "Smith Jane(JSmith)" becomes "Smith Jane").

No Server Needed: Runs 100% locally in your browser. Can be hosted as a free, static site on GitHub Pages.

How to Use the Live App

Set Options: Set the "Passing Grade" and desired "Sort Priority."

Upload CSV: Click "Click to upload" and select your CSV file.

Generate: Click the "Generate Forms" button.

Print: A new tab will open with all the forms. Use the "Print All Forms" button at the top to print or "Save as PDF."

Required CSV Format

To work correctly, your CSV file must contain the following column headers:

student_Id

Student_FirstName

Student_LastName

course_code

markingPeriod_Average

Teachers

You can use the "Download CSV template" link on the app itself to get a correctly formatted example file.

How to Run Locally

Download the tutoring_forms_app.html file from this repository.

Double-click the file to open it in any modern web browser.