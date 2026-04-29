# 🔥 Ignited Minds

A beautiful static website for the **Ignited Minds** social initiative — empowering students through free mentorship and guidance.

## 📁 Project Structure

```
website/
├── index.html          ← Main website (single entry point for GitHub Pages)
├── style.css           ← All styles
├── data/
│   ├── mentors.js      ← ✏️ Add/edit mentor profiles here
│   ├── students.js     ← ✏️ Add/edit student success stories here
│   └── gallery.js      ← ✏️ Add/edit gallery photos/videos here
├── images/
│   ├── mentors/        ← Place mentor photos here
│   ├── students/       ← Place student photos here
│   └── gallery/        ← Place gallery images here
└── README.md
```

## ✏️ How to Add Content

### Add a New Mentor
Open `data/mentors.js` and add an object to the array:
```js
{
  name: "Mentor Name",
  role: "Role",
  photo: "images/mentors/photo.jpg",
  bio: "Short bio...",
  linkedin: "https://linkedin.com/in/username",
  expertise: ["Skill 1", "Skill 2"]
}
```

### Add a New Student Story
Open `data/students.js` and add an object:
```js
{
  name: "Student Name",
  photo: "images/students/photo.jpg",
  achievement: "Achievement title",
  story: "Their journey...",
  year: "2026",
  tags: ["Tag1", "Tag2"]
}
```

### Add Gallery Items
Open `data/gallery.js` — supports both images and YouTube videos.

## 🚀 Deployment
Push to GitHub and enable GitHub Pages pointing to the root of this folder.
