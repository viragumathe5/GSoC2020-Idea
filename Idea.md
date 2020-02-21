# Idea
At the time user starts the project the number of files and its extensions are created but when it comes to the project completion the project cantains lots of same, unnamed and useless files. Thus this idea is proposed to ovecome that situation. This idea extends the GSoC,s 2019 project that is "Improve programming language detection and classification in ScanCode". So basically the project idea will cover last years project along with some extensions like

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
  2. Natural Language Processig.  
  
First one is the most basic that is extension check. But some time it happen in any frameworks or templates there my be more than one languages in single extension files for that the second check is to use Natural Language Processing(NLP)

### Check for unnamed files.

Second important task is to check for the unnamed files which can be done by the extension check. And by using the library for the file executions and etc's.

### Check for redundant and same files.

For same file we can use hashing. For same files the hashing for that file gives the same output from this we can exclude the same files from the project.
For redundant files we can use the NLP.

### Check for framework present.

For classification of the frameworks initially we will strive for the two basic frameworks of Python that is
  1. django.  
  2. flask.  

django is kind a high level framework while flask is low level framework so the python files in django is more than flask so framework classification can be done on the basis of the number of Python files. The other checks can be done on the basics of different framework.

---

### Level
  - Intermidiate
  
### Tech 
  - Python, NLP
  
---
