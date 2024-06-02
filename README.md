<!--
**ksadowy/ksadowy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

# Hello 👋

![Profile views](https://gpvc.arturio.dev/[ksadowy])

## 🔧 Technologies & Tools
- **Languages:** Python
- **Frameworks:** React
- **Tools:** Git

## 📈 GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=[ksadowy]&show_icons=true&theme=light)

## 📫 Contact
- [Email](mailto:krzysztof.sadowy01@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/krzysztof-sadowy-622b27295)

---

<div style="position: fixed; bottom: 10px; left: 10px;">
  <div style="position: relative;">
    <img src="https://ksadowy.github.io/hamster.github.io/chomik.png" style="width: 200px; height: 200px;">
    <div id="eye" style="position: absolute; width: 8px; height: 8px; background-color: black; border-radius: 50%;"></div>
  </div>
  <script>
    const eye = document.getElementById('eye');
    document.addEventListener('mousemove', (e) => {
      moveEye(eye, e.clientX, e.clientY);
    });

    function moveEye(eye, mouseX, mouseY) {
      const rect = eye.getBoundingClientRect();
      const eyeX = rect.left + rect.width / 2;
      const eyeY = rect.top + rect.height / 2;
      const angle = Math.atan2(mouseY - eyeY, mouseX - eyeX);
      const distance = 10;
      eye.style.transform = `translate(${Math.cos(angle) * distance}px, ${Math.sin(angle) * distance}px)`;
    }
  </script>
</div>