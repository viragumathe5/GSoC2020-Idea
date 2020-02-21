# Idea
At the time the user starts the project the number of files and its extensions is created but when it comes to the project completion the project contains lots of same, unnamed and useless files. Thus this idea is proposed to overcome that situation. This idea extends the GSoC,s 2019 project that is "Improve programming language detection and classification in ScanCode". So basically the project idea will cover last years project along with some extensions like

- Detect the programming language.
- Do classification as required in ScanCode.
- Check for unnamed files.
- Check for redundant and same files.
- Check for framework present.

---
# Tasks and Possible solutions

### Detect the programming language.

For detecting the programming language there may be two possible ways which are
  1. Extension Check.
  2. Natural Language Processing.  
  
The first one is the most basic that is an extension check. But sometimes it happens in any frameworks or templates there may be more than one languages in single extension files for that the second check is to use Natural Language Processing(NLP)

### Check for unnamed files.

The second important task is to check for the unnamed files which can be done by the extension check. And by using the library for the file executions and etc's.

### Check for redundant and same files.

For the same file detection, we can use hashing. For same files, the hashing for that file gives the same output from this we can exclude the same files from the project.
For redundant files, we can use the NLP.

### Check for framework present.

For the classification of the frameworks initially, we will strive for the two basic frameworks of Python that are
  1. django.  
  2. flask.  

django is a kinda high-level framework while the flask is a low level framework so the python files in django is more than flask so framework classification can be done on the basis of the number of Python files. The other checks can be done on the basis of a different framework.

---

### Level
  - Intermediate
  
### Tech 
  - Python, NLP
  
---
