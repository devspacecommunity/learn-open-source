````markdown
# 🚀 DevSpace Open Source Project for Beginners

Welcome to the _DevSpace Open Source Project for Beginners_ 🎉  
This project is designed to help **new developers** take their **first step into open source** by contributing to a real project in a safe, supportive community.

---

## 🌍 What is this project about?

This is a **community contributor directory** where beginners can:

- Add their developer profile
- Showcase their learning journey
- Share their future tech career goals
- Connect with other DevSpace members
- Practice Git & GitHub collaboration

This project is **not about being an expert** — it’s about **learning by doing** 💡

---

## 🎯 Project Goals

✅ Help beginners understand how open source works  
✅ Teach GitHub collaboration (forking, commits, pull requests)  
✅ Build confidence through small, real contributions  
✅ Create a public directory of DevSpace learners

---

## 🧑‍💻 Who Can Contribute?

Anyone who is:

- Learning software development
- New to open source
- A DevSpace community member
- Willing to follow the contribution steps

No experience required ❤️

---

## 📁 Project Structure

```yaml
project-folder/
│
├── index.html       → Main community page
├── README.md        → Project guide (this file)
├── assets/style.css → Style of the project
└── assets/images    → Where to place your avatar

```


All contributor profiles are added directly inside **index.html**

---

## ✨ What You Will Add

Each contributor adds their **profile card**, which includes:

- Profile picture
- Name
- Short message/bio
- Current/Future Job Role
- Social links (GitHub, Twitter, LinkedIn, etc.)

---

## 🛠 Step-by-Step: How to Contribute

### 1️⃣ Fork the Repository

Click the **Fork** button at the top right of this repo.

---

### 2️⃣ Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
```

---

### 3️⃣ Open the Project

Open the folder in:

- VS Code
- Any code editor

Then open **`index.html`**

---

### 4️⃣ Find the Contributor Section

Look for this part of the file:

```html
<h2>🌍 Our Contributors</h2>
```

Below it, you will see multiple blocks like this:

```html
<div class="member-card"></div>
```

---

### 5️⃣ Copy a Profile Template

Copy one full member card and paste it below the others.

```html
<div class="member-card">
  <img src="YOUR-IMAGE-LINK" />
  <div class="member-info">
    <h3>Your Name</h3>
    <p>Write a short message about your learning journey.</p>

    <div class="meta">
      <!-- <div><span>Country:</span> Your Country / City</div> -->
      <div><span>Current/Future Job Role:</span> Your Career Goal</div>
    </div>

    <div class="socials">
      <a href="https://github.com/yourusername"
        ><i class="fab fa-github"></i
      ></a>
      <a href="https://twitter.com/yourusername"
        ><i class="fab fa-twitter"></i
      ></a>
      <a href="https://facebook.com/yourusername"
        ><i class="fab fa-facebook"></i
      ></a>
      <a href="https://linkedin.com/in/yourusername"
        ><i class="fab fa-linkedin"></i
      ></a>
      <a href="https://yourwebsite.com"><i class="fas fa-globe"></i></a>
    </div>
  </div>
</div>
```

---

### 6️⃣ Add Your Details

Replace the placeholders with your real info.

You can use a free avatar image from:
👉 [https://pravatar.cc/](https://pravatar.cc/)
or visit 👉 [https://getavataaars.com/](https://getavataaars.com/) to generate your own avatar and add it to the assets/images folder (Naming convention is yourname.png or yourname.jpg)

Example:

```html
<img src="https://i.pravatar.cc/100?img=15" /> or include it in the image folder
<img src="assets/image/chris-avatar.png" />
```

---

### 7️⃣ Save and Commit

Note: Make sure you understand how to use Git and Github (You can redo the 10 Days Git/Github Challenge

```bash
git add .
git commit -m "Added my DevSpace contributor profile"
git push
```

---

### 8️⃣ Create a Pull Request

Go to your fork on GitHub and click:

**"Compare & Pull Request"**

Then submit 🎉

---

## 🧠 Contribution Rules

✔ Be respectful
✔ Keep messages positive
✔ No offensive content
✔ Only add ONE profile card
✔ Do not delete other contributors

---

## 🌟 Recommended for Beginners

Want to improve your contribution?

You can also:

- Fix typos
- Improve styling (CSS)
- Add animations (CSS only)
- Improve accessibility
- Suggest UI improvements

---

## 💬 Need Help?

If you're confused:

- Ask in the DevSpace community
- Ask a mentor
- Ask questions — that’s how we learn!

---

## ❤️ Final Note

Your first open-source contribution is special.
It’s not about perfection — it’s about participation.

Welcome to open source, DevSpace builder 🚀

```


- A **CONTRIBUTING.md**
- A **Code of Conduct**
- Or auto profile generator format

```

### Created by Christian Emenike, Lead Coordinator, DevSpace Community
