<h2 style="color: red;"> Hey There! I am Abhishek Dobliyal </h2>

[![Linkedin: Abhishek Dobliyal](https://img.shields.io/badge/-AbhishekDobliyal-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/abhishek-dobliyal-4474061b7/)](https://www.linkedin.com/in/abhishek-dobliyal-4474061b7)
[![GitHub Abhishek-Dobliyal](https://img.shields.io/github/followers/Abhishek-Dobliyal?label=follow&style=social)](https://github.com/Abhishek-Dobliyal)
![](https://komarev.com/ghpvc/?username=Abhishek-Dobliyal&color=blueviolet)


## <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little more about me...

<h2 align="center">Technology Stack <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"></h2>

<h3 align="center"> Languages:
 <img src="https://img.shields.io/badge/python-3776AB.svg?&style=flat-round&logo=python&logoColor=white" height="20"/>
 <img src="https://img.shields.io/badge/-C++-05122A?style=flat-round&logo=C%2B%2B&logoColor=white"/>
 <img src="https://img.shields.io/badge/-Java-05122A?style=flat-round&logo=Java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Julia-cc402b.svg?&style=flat-round&logo=julia&logoColor=white"/>
 <img src="https://img.shields.io/badge/Dart-2260bd.svg?&style=flat-round&logo=dart&logoColor=white"/>
 <img src="https://img.shields.io/badge/SQL-black?style=flat-round&logo=mysql&logoColor=white"/>
</h3>

<h3 align="center">Frameworks:
 <img src="https://img.shields.io/badge/-Bootstrap-05122A?style=flat-round&logo=bootstrap&logoColor=white"/>
 <img src="https://img.shields.io/badge/Flask-000000.svg?&style=flat-round&logo=flask&logoColor=white"/>
 <img src="https://img.shields.io/badge/Flutter-2260bd.svg?&style=flat-round&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-639948.svg?&style=flat-round&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/SkLearn-4cb582.svg?&style=flat-round&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-bd4267.svg?&style=flat-round&logo=streamlit&logoColor=white"/>
 </h3>
 
<h3 align="center">Additional
 <img src="https://img.shields.io/badge/-HTML-E34F26?style=flat-round&logo=html5&logoColor=white"/>
 <img src="https://img.shields.io/badge/-CSS-1572B6?style=flat-round&logo=css3"/>
 <img src="https://img.shields.io/badge/MySQL-black?style=flat-round&logo=mysql&logoColor=white"/>
 <img src="https://img.shields.io/badge/Git/Github-black?style=flat-round&logo=git&logoColor=white"/>
 <img src="https://img.shields.io/badge/MongoDB-black?style=flat-round&logo=mongodb&logoColor=white"/>
 <img src="https://img.shields.io/badge/Firebase-black?style=flat-round&logo=firebase&logoColor=white"/>
</h3>

```python
from graphic_era_university import AbhishekDobliyal

class About(AbhishekDobliyal):
    def __init__(self, first_name, last_name, age, languages=None, 
                tools=None, additional=None):
        super().__init__(first_name, last_name, age):
            self.languages = languages
            self.tools = tools
            self.additional = additional

    def get_languages(self):
        self.languages = (
                "Python",
                "Julia-Lang",
                "C++",
                "SQL",
                "Dart",
                "Java",
            )

        return self.languages

    def get_tools(self):
        self.tools = {
            "Machine Learning and Data Science": ("Sklearn", "Pandas",
                                                 "Numpy", "Matplotlib",
                                                 "Seaborn", "Plots", "XGBoost"),

            "Web Related": ("Flask", "BeautifulSoup", "Selenium", "Streamlit", "Flutter"),

            "GUIs/Automation": ("Tkinter", "Pygame", "PyAutoGUI"),

            "Image Processing": ("OpenCV", "Pillow")

        }

        return self.tools

    def get_additional(self):
        self.additional = (
                "MySQL",
                "MongoDB",
                "HTML",
                "CSS",
                "Bootstrap",
                "Git/Github",
                "Data Structures and Algorithms"
            )

        return self.additional

abhishek_dobliyal = About()

abhishek_dobliyal.stay_happy(enjoy=True)

print(abhishek_dobliyal.get_languages())
print(abhishek_dobliyal.get_tools())
print(abhishek_dobliyal.get_additional())

abhishek_dobliyal.send_msg(msg="Thank You for visiting my Repo.")

```
