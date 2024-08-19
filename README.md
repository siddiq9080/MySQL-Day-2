<h1>MySQL Day 2 Task </h1>

<h3>Design DB Model Guvi Zen class</h3>
<h5>References</h5>
<p> Relationships Reference </p>
 
<p> 1  : classes.instructor_id > users.id     &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp           many-to-one  </p>
<p> 2  : classes.mentor_id > mentors.id   &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp                many-to-one  </p>
<p> 3  : mentors.user_id > users.id       &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp                one-to-one   </p>
<p> 4  : enrollments.class_id > classes.id   &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp             many-to-one  </p>
<p> 5  : enrollments.user_id > users.id     &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp              many-to-one  </p>
<p> 6  : assignments.class_id > classes.id     &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp           many-to-one  </p>
<p> 7  : submissions.assignment_id > assignments.id &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      many-to-one  </p>
<p> 8  : submissions.user_id > users.id          &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp         many-to-one  </p>
<p> 9  : reviews.class_id > classes.id       &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp             many-to-one  </p>
<p> 10 : reviews.user_id > users.id           &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp            many-to-one  </p>
<p> 11 : events.class_id > classes.id         &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp            many-to-one  </p>
<p> 12 : class_categories.class_id > classes.id     &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      many-to-one  </p>
<p> 13 : class_categories.category_id > categories.id  &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp   many-to-one  </p>

