# 👋 Hi, I'm Hazem Khattab

### Frontend Developer | React.js | TypeScript | Next.js

<!-- Banner: upload the banner image to the repo root with the filename below -->

![Banner](linkedIn panner.png)

---

I'm a passionate Frontend Developer who loves building clean, responsive, and user-friendly web applications. I focus on writing clean code, optimizing performance, and delivering great user experiences.

---

## ✨ Animated Header (professional touch)

GitHub README cannot run JavaScript, so to add animation we use **animated SVG** or **animated GIF** files. Below there are two options — choose one and upload the file to the repository root.

**Option A — Use an animated SVG file** (recommended: crisp vector animation)

1. Create a file named `header-anim.svg` in the repo root and paste the SVG code below into it.
2. In this README it will be shown with:

```md
<img src="./header-anim.svg" alt="Animated Header" />
```

**Sample `header-anim.svg`** (simple moving gradient + name):

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="150" viewBox="0 0 1200 150">
  <defs>
    <linearGradient id="g" x1="0" x2="1">
      <stop offset="0%" stop-color="#00c6ff" />
      <stop offset="50%" stop-color="#0072ff" />
      <stop offset="100%" stop-color="#00c6ff" />
    </linearGradient>
    <style>
      .title { font: 700 48px 'Segoe UI', Roboto, sans-serif; fill: url(#g); }
      .subtitle { font: 400 22px 'Segoe UI', Roboto, sans-serif; fill: #bcdcff; }
      @keyframes move { from { transform: translateX(-100%);} to { transform: translateX(100%);} }
      .strip { animation: move 6s linear infinite; }
    </style>
  </defs>
  <rect width="100%" height="100%" fill="#071028" rx="6"/>
  <g transform="translate(40,40)">
    <text class="title">Hazem Ahmed Khattab</text>
    <g transform="translate(0,54)">
      <text class="subtitle">Frontend Developer • React • TypeScript • Next.js</text>
    </g>
  </g>
  <!-- decorative animated strip -->
  <g class="strip" transform="translate(-400,120)">
    <rect x="0" y="0" width="1600" height="6" fill="url(#g)" opacity="0.9" rx="3" />
  </g>
</svg>
```

**Option B — Use an animated GIF**

* Create or export an animated GIF header (e.g. `header-anim.gif`) and upload it to the repo root.
* Reference it in the README like this:

```md
![Animated Header](./header-anim.gif)
```

---

## 🚀 Technologies & Tools

* **Frontend:** HTML, CSS, JavaScript, TypeScript, React.js, Next.js
* **State Management:** Redux Toolkit, Context API
* **UI Frameworks:** TailwindCSS, Material UI, Bootstrap, Sass
* **Tools:** Git, GitHub, Postman
* **Other:** JWT Authentication, APIs, Responsive Design

---

## 📌 Featured Projects

### 🔹 Smart Trash – Graduation Project

Dashboard + Real-time monitoring system for smart waste management. Includes charts, alerts, sensors integration, and admin UI.

🔗 **Live Demo:** [https://smart-trash-deployment.vercel.app/](https://smart-trash-deployment.vercel.app/)

---

## 📫 Contact Me

* **Email:** [hazemkhattab222@gmail.com](mailto:hazemkhattab222@gmail.com)
* **LinkedIn:** [https://www.linkedin.com/in/hazem-ahmed-khattab1/](https://www.linkedin.com/in/hazem-ahmed-khattab1/)
* **GitHub:** [https://github.com/hazemkhattab](https://github.com/hazemkhattab)

---

⭐ Feel free to check out my projects or contact me for collaboration!

---

## ✅ Quick steps to apply this README to your GitHub profile

1. In GitHub create a repository with your exact GitHub username (e.g. `hazemkhattab`).
2. Add this `README.md` file to the repository root.
3. Upload the banner image file `A_LinkedIn_banner_in_digital_graphic_design_format.png` to the repo root (or rename it to `banner.png` and update the reference above).
4. (Optional) Add `header-anim.svg` or `header-anim.gif` to the repo root for the animated header.
5. Commit and push — GitHub will show this README on your profile.

If you want, I can:

* Generate a ready-to-upload `header-anim.svg` file for you, or
* Export an animated GIF version of the header, or
* Directly commit these files to your repo if you give me the repo link and permission.
