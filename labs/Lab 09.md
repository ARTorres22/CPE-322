# Lab 9 — YANG

used pyang to generate a `.yin` and `.uml` file with the following code

`$ pyang -f yin -o intrusiondetection.yang intrusiondetection.yin`

`$ pyang -f uml -o intrusiondetection.yang intrusiondetection.uml`

![pyang](img/pyang.png)
---

ran `$ cat intrusiondetection.yin`

![catyang](img/catyin.png)

---
ran `$ cat intrusiondetection.uml`

![catuml](img/catuml.png)

---
ran `$ python -m plantuml intrusiondetection.uml` to generate a png file

![plantuml](img/plantuml.png)

the generated png file named `intrusiondetection.png`

![plantumlimg](img/plantumlimg.png)
