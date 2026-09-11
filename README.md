## Hi there 👋


[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=24&pause=1000&color=0FF70F&background=2F83FF00&width=435&lines=Welcome+to+my+Github+;I'm+Davronbek+python+developer)](https://git.io/typing-svg)
<!--
**davron-abdullayev/davron-abdullayev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# 👋 Welcome to my GitHub!

## 💫 About Me

```python
from dataclasses import dataclass


@dataclass
class Developer:
    name = "Davron"
    role = "Python Backend Developer"
    education = "Tashkent State Transport University"
    languages = ["Python", "SQL", "JavaScript"]
    current_focus = "Backend Development"

    def get_skills(self):
        return {
            "frameworks": ["FastAPI", "Django", "Aiogram"],
            "databases": ["PostgreSQL", "MySQL", "Redis"],
            "tools": ["Git", "Docker", "DataGrip", "Alembic"],
        }

    def say_hello(self):
        return "Let's build something great together! 🚀"


me = Developer()
print(me.say_hello())
