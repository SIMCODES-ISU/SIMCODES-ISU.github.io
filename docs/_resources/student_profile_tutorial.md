---
title: How to Create Your SIMCODES Student Profile
layout: page
permalink: /profile-tutorial/
image:
  thumbnail: /resources/images/profile.png
  path: /resources/images/profile.png
---

This page will walk you through your first GitHub experience, creating your
profile. So get ready to say "Hello World!" to the SIMCODES community!!!

# 🧑‍🎓 How to create your SIMCODES Student Profile (With Picture and Bio)

Welcome to SIMCODES! This guide will help you create your personal student
profile that will be listed on the [Students Page](/students/). Your profile
will include:

- ✅ Your name and a short introduction
- ✅ A clear profile photo
- ✅ A dedicated profile page linked from the main list

---

## 📁 Step 1: Prepare Your Profile Picture

1. Save a photo of yourself with a square aspect ratio.
2. Resize it to **around 300x300px** (optional).
3. Name the file like `yourname.png` (e.g., `student.png`)
4. Place it inside the folder:  
   `/_students/images/`

---

## 📝 ✍️ Step 2: Create Your Profile File and fill the details

Inside the project folder, go to `_students/` and create a new Markdown file
named like this:

```
_students/your-name.md
```

You can also copy the sampleStudent.md file and rename it and make your
changes in it

---

## 🧪 Step 3: Preview Your Profile (Locally)

Since we are running the site locally with Jekyll:

```bash
bundle exec jekyll serve
```

Visit:

```
http://localhost:4000/students/
```

You’ll see your photo and name listed. Click on it to go to your full profile!

---

## 🧪 Step 4: Push your changes to SIMCODES Github repo and create a PR

Refer - [Github Basics](https://simcodes-isu.github.io/student-resources/) for
the Github setup and commands

## ✅ Profile Guidelines

- Keep your intro short (2–4 sentences).
- Use a clear profile photo and banner image.

---

## Profile Template

```.markdown
---
title: "Your Full Name"
layout: page
author: "Your Full Name"
image:
  thumbnail: /students/images/sample_student_thumbnail.png
  path: /students/images/sample_header.png
---

# About Me

Hi! I'm [Your Name], currently a [Your Year, e.g., second-year undergrad] at
[Your University / Department]. I’m passionate about [your interests — e.g.,
machine learning, hardware, security, etc.], and currently exploring
opportunities in [your field].

---

## 🛠 Skills & Technologies

- Programming Languages: Python, C, Java
- Tools: Git, VS Code, Jupyter
- OS: Linux, macOS, Windows
- Others: Markdown, LaTeX

---

## 📚 Projects or SIMCODES Contributions

### 📌 Project Name or Internship Work

**Description**: Short summary of the project or your role.  
**Tech Stack**: Python, GitHub, SQLite  
**Link**: [GitHub Repo](https://github.com/yourusername/project)

---

## 📈 Goals for This Internship

- [ ] Learn more about real-world version control workflows (Git)
- [ ] Contribute to collaborative open-source code
- [ ] Build strong Python + Linux foundations
- [ ] Document my learning journey

---

## 🔗 Links

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [linkedin.com/in/yourname](https://linkedin.com/in/yourname)
- Personal Website (if any): [yourdomain.com](https://yourdomain.com)

---
```


That's it! 🚀  
You're now part of the SIMCODES community site. Let us know if you need help or
want to update your profile later.
