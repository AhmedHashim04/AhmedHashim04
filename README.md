<h1 align="center">Hi 👋, I'm Ahmed Hashim</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/ahmedhashim04/">
    <img src="https://img.shields.io/badge/Ahmed%20Hashim-LinkedIn-0077b5" alt="LinkedIn" />
  </a>
  <a href="https://github.com/AhmedHashim04">
    <img src="https://img.shields.io/badge/Ahmed%20Hashim-GitHub-2b3137" alt="GitHub" />
  </a>
  <a href="https://twitter.com/ahmedhashim04">
    <img src="https://img.shields.io/badge/Ahmed%20Hashim-Twitter-1DA1F2" alt="Twitter" />
  </a>
  <a href="https://www.instagram.com/ahmedhashim04/">
    <img src="https://img.shields.io/badge/Ahmed%20Hashim-Instagram-E1306C" alt="Instagram" />
  </a>
</p>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=3000&pause=500&center=true&vCenter=true&width=1000&lines=Hey+there+%F0%9F%91%8B;I'm+Ahmed+Hashim;AI+Student+%7C+Django+Developer+;Love+Python%2C+Django%2C+FastAPI+%26+Data+Science" alt="Typing SVG" />
</a>

---

### 👨‍💻 About Me

```python
from rest_framework.decorators import api_view
from rest_framework.response import Response

@api_view(['POST'])
def introduce_yourself(request):
    name = request.data.get('name', 'Ahmed Hashim')
    occupation = request.data.get('occupation', 'Backend Developer')
    interests = request.data.get('interests', ['Python', 'Django', 'Data Science'])

    introduction = f"Hello, my name is {name}. I am a {occupation} and my interests include {', '.join(interests)}."

    return Response({'introduction': introduction})
