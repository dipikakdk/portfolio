# Dipika Khadka - Portfolio Customization Guide

Your portfolio has been personalized with your name and basic information. Here are the remaining items you need to update:

## Information to Replace

### 1. Contact Information (index.html)
**Location:** Lines 212-233

Replace these placeholders with your actual information:
- **Email:** `dipika.khadka@example.com` → Your actual email
- **Phone:** `+977 98XXXXXXXX` → Your actual phone number
- **Location:** `Your City, Nepal` → Your actual city
- **LinkedIn:** `https://linkedin.com/in/dipikakhadka` → Your actual LinkedIn profile
- **GitHub:** `https://github.com/dipikakhadka` → Your actual GitHub profile
- **Facebook:** `https://facebook.com/dipikakhadka` → Your actual Facebook profile

### 2. Education Details (index.html)
**Location:** Lines 175-210

Replace these placeholders:
- **University:** `Your University Name, Nepal` → Your actual university name
- **College:** `Your College Name, Nepal` → Your actual college name
- **School:** `Your School Name, Nepal` → Your actual school name
- **Years:** Update all `Year - Present` and `Year - Year` with actual dates

### 3. About Section (index.html)
**Location:** Lines 56-69

The introduction is already personalized, but you may want to:
- Modify the career objective to match your specific goals
- Add more details about your interests or achievements
- Update the university name in the info section (Line 75)

### 4. Resume/CV (index.html)
**Location:** Line 43

The Download CV button currently links to `resume.pdf`. To add your actual CV:
1. Save your CV as `resume.pdf` in the same folder as `index.html`
2. Or update the link to your actual CV file path

### 5. Projects (index.html)
**Location:** Lines 140-158

The Patient Appointment Booking System is already included. To add more projects:
1. Copy the entire `<div class="project-card">` block (Lines 138-158)
2. Paste it after the existing project card
3. Update the project details:
   - Project name
   - Description
   - Technologies
   - GitHub link
   - Live demo link (if available)

### 6. Skills (index.html)
**Location:** Lines 95-133

The skills are already set up with your requested technologies. You can:
- Add more skills by copying a skill card
- Remove skills you don't want to showcase
- Change proficiency levels (Advanced, Intermediate, Expert)

## Optional Enhancements

### Add Profile Photo
To add your profile photo in the hero section:

1. Save your photo as `profile.jpg` in the project folder
2. Add this code after Line 37 (after the subtitle):
```html
<div class="profile-photo">
    <img src="profile.jpg" alt="Dipika Khadka" class="profile-img">
</div>
```

3. Add this CSS to `styles.css`:
```css
.profile-photo {
    margin: 2rem auto;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
    border: 4px solid var(--primary-color);
    box-shadow: var(--shadow-lg);
}

.profile-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

### Add Certificates Section
If you want to add a certificates section, add this after the Education section (before Contact):

```html
<!-- Certificates Section -->
<section id="certificates" class="section">
    <div class="container">
        <h2 class="section-title">Certificates</h2>
        <div class="skills-grid">
            <div class="skill-card">
                <div class="skill-icon">📜</div>
                <h3>Certificate Name</h3>
                <p>Issuing Organization</p>
            </div>
            <!-- Add more certificates -->
        </div>
    </div>
</section>
```

And add this to the navigation menu (Line 23):
```html
<li><a href="#certificates" class="nav-link">Certificates</a></li>
```

### Add Experience Section
If you have internships or work experience, add this after Education:

```html
<!-- Experience Section -->
<section id="experience" class="section section-alt">
    <div class="container">
        <h2 class="section-title">Experience</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-date"></div>
                <div class="timeline-content">
                    <h3>Job Title</h3>
                    <p class="timeline-institution">Company Name</p>
                    <p class="timeline-period">Month Year - Month Year</p>
                    <p>Description of your responsibilities and achievements.</p>
                </div>
            </div>
        </div>
    </div>
</section>
```

## Testing Your Portfolio

1. Open `index.html` in your web browser
2. Check all sections display correctly
3. Test the navigation links
4. Verify the contact form works (it's in demo mode)
5. Test on mobile phone (resize browser or use device mode)

## Deployment

When ready to deploy:

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Your site will be live at: `yourusername.github.io/repository-name`

### Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the project folder
3. Your site will be live instantly

## Need Help?

If you need help with any customization:
- Check the README.md for detailed instructions
- Refer to the comments in the code files
- All placeholder text is clearly marked

---

**Your portfolio is almost ready! Just fill in the placeholders above and you're good to go.**
