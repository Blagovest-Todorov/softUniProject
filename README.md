# softUniProject
What is navigational property -> property that points to other class it is like a Foreign Key to another table.
what is inverse property -> property of another type class Collection into our class.
Example : we have class Student and class Course
into the class Student we have a property ICollection<Course> Courses -> this is an example of inverse property.
  Into classs Student we have property  public virtual Course StudentCourses -> this is  Navigational property(property of another type Class into our class)
  Into class Course we have property of typepublic virtual Student StudentsCourse; NAVPrpoerty
  
  Into class Course we have ICollection <Student> Students -> inverse property, so we can access using 
  Linq the Students that have courses and all the Student into colllection of a given Course.
  
  
