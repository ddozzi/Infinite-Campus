# Infinite-Campus

Infinite Campus login thingy 

um you can see ur grades like this:

```
student = User("username", "password", "https://district.infinitecampus.org/campus/portal/students/district.jsp")
current_term = student.getGrades()
class1 = current_term.classes[0]

print(class1.letter_grade)
```
