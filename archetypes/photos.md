---
title: "{{ replace .Name "_" " " | title }}"
date: {{ .Date }}
thumbnail: /photos/{{ replace .Name "_" "-" | lower }}-thumbnail.jpg
---

Description

![{{ replace .Name "_" " " | title }}](/photos/{{ replace .Name "_" "-" | lower }}.jpg)


<!--more-->

### Image details
Camera: Canon EOS Rebel T6s  
F-stop: f/9  
Exposure time: 1/20 sec  
ISO: 200  
Focal Length: 50mm  


