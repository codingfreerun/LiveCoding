---
layout: exercise_python_freerun
permalink: "Python"
title: "Python Free Coding Area"
excerpt: "Python Free Coding Area"

info:
  instructions: "Enter in some Python code below to practice."
  goals:
    - Practice Python
    
processor:  
  correctfeedback: "" 
  incorrectfeedback: ""
  submitformlink: false
  feedbackprocess: | 
    var pos = runtime.text.trim();
  correctcheck: |
    pos.includes("") 
 
files:



  - filename: "Test Code Block"
    ismain: true
    name: main
    isreadonly: false
    isvisible: true
    code: |
        print("Hello World")
        
---
