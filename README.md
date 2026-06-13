# 💍 Wedding Website - Paris

A beautiful, one-page responsive wedding website built with **Tailwind CSS** and **Vanilla JavaScript**.

## 🎨 Design Features
- **Theme:** Elegant Parisian (Ivory, Gold, Navy).
- **Parallax Effects:** Scenic river/boat views for a romantic atmosphere.
- **Responsive:** Works on mobile, tablet, and desktop.
- **RSVP Logic:** Built-in countdown/activation logic for the RSVP button.

---

## 🚀 Local Development

To preview the website locally on your machine, follow one of the methods below:

### Method 1: Using Python (Easiest/No Install Required)
If you have Python installed (most macOS and Linux systems do), you can start a server instantly.

**For Windows:**
```bash
python -m http.server 8000
```

**For macOS/Linux:**
```bash
python3 -m http.server 8000
```
*Once running, open your browser and go to:* `http://localhost:8000`

---

### Method 2: Using Node.js (`npx`)
If you have Node.js installed, you can run a server without installing anything permanently.

```bash
npx serve .
```
*Once running, follow the URL provided in your terminal (usually `http://localhost:3000`).*

---

### Method 3: VS Code "Live Server" (Recommended for Editing)
If you use **Visual Studio Code**:
1.  Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension.
2.  Open `index.html`.
3.  Click the **"Go Live"** button in the bottom right status bar of VS Code.
4.  Your browser will open automatically and **auto-refresh** every time you save a change.

---

## 🛠️ Customization Instructions

### 1. Editing Content
Open `index.html` in your text editor. Search for the following placeholders to replace them with your actual data:
- `[Date Placeholder]`
- `[Time Placeholder]`
- `[Boat Name Placeholder]`
- `[Location/Dock Placeholder]`
- `[How to get there Placeholder]`
- `[RSVP Deadline Placeholder]`

### 2. Enabling the RSVP Button
The RSVP button is locked by default. To change the date when it becomes active:
1.  Scroll to the bottom of `index.html`.
2.  Find the line: `const releaseDate = new Date('2025-12-31T00:00:00');`
3.  Change the date to your desired release date (Format: `YYYY-MM-DDTHH:mm:ss`).

### 3. Deployment
To host this online for free:
1.  Upload `index.html` to a GitHub repository.
2.  Go to **Settings** > **Pages**.
3.  Under **Build and deployment**, set Source to **Deploy from a branch** and select `main`.
4.  Your site will be live at `https://<your-username>.github.io/<repository-name>/`

---

## 📦 Technologies Used
- **HTML5**
- **Tailwind CSS** (via CDN)
- **Google Fonts** (Playfair Display & Lato)
- **Vanilla JavaScript**
