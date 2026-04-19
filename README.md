# Kumar Abhishek - Portfolio Website

Professional portfolio website showcasing my experience as a Java Backend Developer (SDE-2) at Fujitsu Research India.

## 🚀 Live Demo

Visit: `https://yourusername.github.io/portfolio`

## 📋 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Modern UI** - Clean and professional design with smooth animations
- **Sections Include:**
  - Hero section with profile photo
  - About me with key statistics
  - Technical skills showcase
  - Professional experience timeline
  - Key achievements
  - Certifications gallery
  - Education details
  - Contact information

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Grid & Flexbox)
- Vanilla JavaScript
- Font Awesome Icons

## 📦 Setup Instructions

### 1. Clone or Download

Download this portfolio folder to your local machine.

### 2. Add Your Profile Image

1. Create an `images` folder inside the `portfolio` directory
2. Add your profile photo as `profile.jpg` in the `images` folder
3. Add certificate images with these names:
   - `java-cert.jpg`
   - `sql-basic.jpg`
   - `sql-intermediate.jpg`
   - `jse-cert.jpg`
   - `fullstack-cert.jpg`
   - `internship-jee.jpg`
   - `java-interview.jpg`

### 3. Add Resume PDF

Copy your resume PDF file as `KUMAR_ABHISHEK_Resume.pdf` in the portfolio folder.

## 🌐 Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com)
2. Click "New Repository"
3. Name it: `portfolio` (or any name you prefer)
4. Keep it **Public**
5. Click "Create repository"

### Step 2: Upload Files

**Option A: Using GitHub Web Interface**

1. Click "uploading an existing file"
2. Drag and drop all portfolio files:
   - `index.html`
   - `style.css`
   - `script.js`
   - `README.md`
   - `images/` folder (with all images)
   - `KUMAR_ABHISHEK_Resume.pdf`
3. Click "Commit changes"

**Option B: Using Git Command Line**

```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 2-3 minutes
7. Your site will be live at: `https://YOUR_USERNAME.github.io/portfolio/`

## 📝 Customization

### Update Personal Information

Edit `index.html` and update:
- Name and title
- Contact details
- Social media links
- Experience details
- Skills
- Achievements

### Change Colors

Edit `style.css` and modify the CSS variables:

```css
:root {
    --primary-color: #2563eb;  /* Change to your preferred color */
    --secondary-color: #1e40af;
    --accent-color: #3b82f6;
}
```

### Add/Remove Sections

Simply edit the HTML in `index.html` to add or remove sections as needed.

## 📱 Folder Structure

```
portfolio/
├── index.html              # Main HTML file
├── style.css               # Styling
├── script.js               # JavaScript functionality
├── README.md               # This file
├── KUMAR_ABHISHEK_Resume.pdf  # Your resume
└── images/
    ├── profile.jpg         # Your profile photo
    ├── java-cert.jpg       # Certificate images
    ├── sql-basic.jpg
    ├── sql-intermediate.jpg
    ├── jse-cert.jpg
    ├── fullstack-cert.jpg
    ├── internship-jee.jpg
    └── java-interview.jpg
```

## 🎨 Image Requirements

- **Profile Photo**: 400x500px (3:4 aspect ratio recommended)
- **Certificate Images**: 600x400px (landscape orientation)
- Format: JPG or PNG
- Keep file sizes under 500KB for faster loading

## 🔗 Update Links

Make sure to update these links in `index.html`:

1. LinkedIn profile URL
2. GitHub profile URL
3. LeetCode profile URL
4. GeeksforGeeks profile URL
5. HackerRank profile URL
6. Certificate links (Google Drive or HackerRank)

## 📧 Contact

- **Email**: kumarabhishek120044@gmail.com
- **Phone**: +91 7367018043
- **Location**: Bengaluru, Karnataka, India

## 📄 License

This portfolio template is free to use and modify for personal purposes.

---

**Built with ❤️ by Kumar Abhishek**
