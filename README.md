# Be There Lawncare — Website

Live site: **https://www.betherelawncare.com**

---

## How to Edit the Website

This website is stored on GitHub and automatically goes live whenever you save a change. No coding knowledge required for common edits.

---

### Step 1 — Open the file editor

Go to this link (bookmark it):

**https://github.com/travisstoliker/bethere-lawncare/edit/main/index.html**

You'll need to be logged into GitHub. If you don't have an account, ask Travis to set one up and grant you access.

---

### Step 2 — Find what you want to change

The file will open in an editor. Use **Ctrl+F** (Windows) or **Cmd+F** (Mac) to search.

All editable sections are marked with a comment that starts with `<!-- EDIT:`. For example:

```
<!-- EDIT: Phone number — update "tel:5177633233" AND the display text "(517) 763-3233" -->
```

The comment tells you exactly what to change on the line right below it.

**Common things you might want to update:**

| What to change | Search for |
|---|---|
| Phone number | `EDIT: Phone number` |
| Email address | `EDIT: Email address` |
| Hero headline | `EDIT: Main headline` |
| About Us paragraph | `EDIT: About section paragraph` |
| Bullet point list | `EDIT: Bullet point list` |
| Customer reviews | `EDIT: Review 1` or `EDIT: Review 2` |
| Footer | `EDIT: Footer` |

---

### Step 3 — Make your change

Click directly on the text you want to edit and type your changes. Only change the visible text — don't change anything inside `< >` brackets unless the comment tells you to.

**Example — updating the phone number:**

Find this:
```html
<!-- EDIT: Phone number — update "tel:5177633233" AND the display text "(517) 763-3233" -->
<a href="tel:5177633233" class="btn btn-primary">
  (517) 763-3233
```

Change it to (for example):
```html
<!-- EDIT: Phone number — update "tel:5177633233" AND the display text "(517) 763-3233" -->
<a href="tel:5174441234" class="btn btn-primary">
  (517) 444-1234
```

---

### Step 4 — Save and publish

1. Scroll to the bottom of the page
2. Under **"Commit changes"**, type a short note about what you changed (e.g. "Updated phone number")
3. Click the green **"Commit changes"** button

The website will automatically update within **1–2 minutes**.

---

### Adding a new photo to the gallery

1. Go to: **https://github.com/travisstoliker/bethere-lawncare**
2. Click **"Add file"** → **"Upload files"**
3. Drag your photo in and name it (e.g. `photo48.jpg`)
4. Click **"Commit changes"**
5. Then edit `index.html` and find the gallery section — add a new line like:
   ```html
   <div class="gallery-item"><img src="photo48.jpg" alt="Lawn care Haslett MI" loading="lazy"></div>
   ```

---

### Need help?

Contact Travis or open a chat with Claude at **https://claude.ai** and paste your question — Claude built this site and knows it well.
