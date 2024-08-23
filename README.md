```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class FranciscoMoreno(Human, SoftwareEngineer):
    
    def __init__(self):
        self.name: str = "Francisco"
        self.surnames: str="Moreno Rodríguez"
        self.age: int = 24
        self.languages: list = ["es_ES", "en_US"]
        
        self.skills = [
            "Python",
            "HTML",
            "CSS",
            "JavaScript",
            "C++"
        ]
        
        self.current_role = "Quality Assurance Specialist"
        self.expected_job_conditions: set = {"software_developer", "learning", "nice_people", "flexibility"}
        
        
    def greeting(self):
        print(f"Hi! I am {self.name} {self.surnames}")
        
    @staticmethod
    def get_interests():
        return [
            "Computer Vision",
            "Web Development",
            "DevOps",
            "Data Science"
        ]
    
    def hire_me(self, new_role: Role):
        """
        Contact me via LinkedIn, Gmail or Telegram.
        """
        if new_role.conditions == self.expected_job_conditions:
            self.current_role = new_role
            return True 
        else: 
            return False
```

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/franciscomorenorodgiruez/)](https://www.linkedin.com/in/franciscomorenorodgiruez/)
[My portfolio](https://franm99.github.io/portfolio-fr/)

## GitHub stats

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api?username=Franm99&show_icons=true&theme=dracula" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img height=200 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Franm99&theme=dracula&count_private=true&layout=compact" />
</a>
