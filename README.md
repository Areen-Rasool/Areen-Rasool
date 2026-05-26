
from PIL import Image

img = Image.open("image.png")

frames = []
for i in range(10):
    scale = 1 + i * 0.02
    frame = img.resize((int(img.width * scale), int(img.height * scale)))
    frames.append(frame)

frames[0].save(
    "animated.gif",
    save_all=True,
    append_images=frames[1:],
    duration=100,
    loop=0
)


### 👩‍💻 About Me

🎓 PhD Researcher in Computational Mathematics and Artificial Intelligence  

🧬 Currently working on developing efficient and reliable Graph Neural Network (GNN) models for biomedical applications in drug discovery

📫 Reach me at:

<p align="center">
  <a href="https://orcid.org/0009-0005-0915-1168">
    <img src="https://img.shields.io/badge/ORCID-0009--0005--0915--1168-green?style=for-the-badge&logo=orcid">
  </a>

  <a href="https://www.linkedin.com/in/areen-rasool-57586b1b4/">
    <img src="https://img.shields.io/badge/LinkedIn-Areen%20Rasool-blue?style=for-the-badge&logo=linkedin">
  </a>
</p>

---


### 🚀 Some Tools I Have Used and Learned :

<p align="left">
<img src="https://skillicons.dev/icons?i=python,pytorch,matlab,anaconda,vscode,github" />
</p>

---
