Understand using debug module and msg
--- 
- hosts: localhost 
  tasks: 
  - name: simple play with debug module 
    debug: 
      msg: "My name is Javeed,, hurray its workin!"
Understand using variables
---
- hosts: localhost: 
  vars:
    student_name: smitha
  tasks: 
  - name: it will use debug module to display student name
    debug: 
      msg: " Student name is {{ student_name }} "
