Teacher portal where teachers can sign in and view their roster of students.
Teachers can create students, view their name and their comments, edit name and comments, and delete students.


Gemfile
Rakefile
App
  controllers
    - application_controller
    - teacher_controller
    - student_controller
  models
    - teacher
    - student
  views
    - teacher
      - index (shows all teachers)
      - show (show a specific teacher and their student and has link to delete)
      - edit (shows form to update student info and also delete student)
