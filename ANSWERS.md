## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
The nil sets the value inside in the tag to enable the use of a placeholder

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
Because the form wasn't filled out

3. What type of request did your browser just perform?
GET

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
We have a POST route when submitting the form 