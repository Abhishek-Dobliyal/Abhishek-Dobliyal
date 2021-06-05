<h2 style="color: red;"> Hey There! I am Abhishek Dobliyal </h2>

[![Linkedin: Abhishek Dobliyal](https://img.shields.io/badge/-AbhishekDobliyal-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/abhishek-dobliyal-4474061b7/)](https://www.linkedin.com/in/abhishek-dobliyal-4474061b7)
[![GitHub Abhishek-Dobliyal](https://img.shields.io/github/followers/Abhishek-Dobliyal?label=follow&style=social)](https://github.com/Abhishek-Dobliyal)


## <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little more about me...
<ul> <li> Pythonista
<li> Machine Learning and Data Science Enthusiast
<li> Poblem Solver
</ul>


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
                "Dart"
            )

        return self.languages

    def get_tools(self):
        self.tools = {
            "Machine Learning and Data": ("Sklearn", "Pandas",
                                         "Numpy", "Matplotlib",
                                         "Seaborn"),

            "Web Related": ("Flask", "BeautifulSoup", "Selenium", "Streamlit", "Flutter"),

            "GUIs/Automation": ("Tkinter", "Pygame", "PyAutoGUI"),

            "Image Processing": ("OpenCV", "Pillow", "Pytesseract")

        }

        return self.tools

    def get_additional(self):
        self.additional = (
                "MySQL",
                "HTML",
                "CSS",
                "Bootstrap",
                "Git/Github",
                "Data Structures and Algorithms",
                "Problem Solving"
            )

        return self.additional

abhishek_dobliyal = About()

abhishek_dobliyal.stay_happy(enjoy=True)

print(abhishek_dobliyal.get_languages())
print(abhishek_dobliyal.get_tools())
print(abhishek_dobliyal.get_additional())

abhishek_dobliyal.send_msg(msg="Thank You for visiting my Repo.")

```
