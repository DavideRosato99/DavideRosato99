```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class SpaceEngineeringStudent:

    def __init__(self):
        self.name = "Davide Rosato"
        self.role = "Space Engineering student"
        self.organization = ["NASA JPL", "Skyward-er", "Polimi"]
        self.language_spoken = ["it_IT", "en_US"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = SpaceEngineeringStudent()
me.say_hi()
```
