# Marco Mo CV Portfolio Website

A static GitHub Pages website for hosting four public CV versions:

- AI/ML Engineer CV
- Data Scientist CV
- Data Engineer CV
- Data Analyst CV

## Files

```text
index.html
styles.css
assets/
  Marco_Mo_CV_AI_ML_Engineer.pdf
  Marco_Mo_CV_Data_Scientist.pdf
  Marco_Mo_CV_Data_Engineer.pdf
  Marco_Mo_CV_Data_Analyst.pdf
  profile.jpg
```

## Publish on GitHub Pages

1. Create a new public GitHub repository, for example `cv-portfolio`.
2. Upload all files from this folder to the repository.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Click **Save**.
6. Your site will be available at:

```text
https://YOUR-GITHUB-USERNAME.github.io/cv-portfolio/
```

If you name the repository exactly `YOUR-GITHUB-USERNAME.github.io`, then the site will be available at:

```text
https://YOUR-GITHUB-USERNAME.github.io/
```

## LinkedIn public badge

The page already includes a LinkedIn badge block using the public profile vanity name:

```text
cheuk-lam-marco-mo
```

If LinkedIn changes the badge code or the badge does not render, go to LinkedIn:

**View Profile → Public profile & URL → Create a public profile badge**

Then replace the badge block in `index.html` inside:

```html
<div class="linkedin-badge-wrap" aria-label="LinkedIn public profile badge">
  ...replace this badge code...
</div>
```

## Customize

Edit `index.html` to change text, links, or project highlights. Edit `styles.css` to change colors, spacing, or layout.
