# 🗂️ To-Do Manager (Offline)

A simple yet powerful **To-Do Manager** built entirely in one HTML file.  
No frameworks, no external libraries — just **pure HTML, CSS, and JavaScript**.  
It works completely **offline** and saves your data in **localStorage**.

---

## 🚀 Features

- ✅ Add new tasks (title required)
- 🏷️ Optional category and due date
- ✏️ Inline edit for title and category (Save / Cancel)
- ✅ Mark as completed or active
- 🗑️ Delete tasks
- 🔍 Search by title or category
- 🔄 Filters: **All / Active / Completed**
- 🧹 Clear all completed tasks
- 💾 Automatic localStorage saving (persistent data)
- 🌐 Works offline in any modern browser
- ♿ Accessible and keyboard-friendly
- 📱 Responsive, card-style UI with subtle shadows and large inputs/buttons

---

## 💻 How to Use

1. **Open the app**
   - Just double-click `index.html` (it opens directly in your browser).
   - Or serve it locally for best results:
     ```bash
     python -m http.server 8000
     ```
     Then visit [http://localhost:8000](http://localhost:8000)

2. **Add a task**
   - Enter a title (required)
   - Optionally add a category or due date
   - Click **Add Task**

3. **Manage tasks**
   - Click ✅ checkbox to mark complete
   - Click ✏️ Edit to change title/category
   - Click 🗑️ Delete to remove a task
   - Use filters and search to organize tasks

4. **Persistence**
   - All tasks are saved in your browser’s `localStorage`
   - Data remains even after you close or refresh the page

---

## 🌍 Deploy on GitHub Pages

### Step-by-step

1. Create a new GitHub repository (public or private)
2. Upload or commit your `index.html` file
3. Go to:
   **Settings → Pages → Source →** select `main` branch and folder `/ (root)`
4. Click **Save**
5. Wait a minute, then open your GitHub Pages URL:
