## Questions

What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
There is no initial value for :course_name.

Go to `localhost:3000/teachers` in your browser; why does this not work?
There is no route to get /teachers, only to create a new form.

What type of request did your browser just perform?
My browser just performed a get request.

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
localhost:3000/teachers

Why does `localhost:3000/teachers` work now?
I submitted a form which is a post request so therefore, there is a route to localhost:3000/teachers.