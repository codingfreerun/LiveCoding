---
layout: exercise_cpp_freerun
permalink: /Cpp
title: "C++ Free Coding Area"
excerpt: "C++ Free Coding Area"

info:
  instructions: "Enter in some C++ code below to practice."
  goals:
    - Practice C++
    
processor:  
  correctfeedback: "" 
  incorrectfeedback: ""
  submitformlink: false
  feedbackprocess: | 
    var pos = runtime.text.trim();
  correctcheck: |
    pos.includes("") 
 
files:
  - filename: "Main Area"
    name: main
    ismain: true
    isreadonly: false
    isvisible: true
    code: | 
      #include &ltstdio.h&gt
      
      int main() {
          printf("Hello world\n");
          return 0;
      }
        
---
