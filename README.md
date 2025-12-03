# Simple Portfolio Template

Welcome! This is a starter template for your personal portfolio website. It uses **HTML**, **CSS**, and **Bootstrap 5** to give you a professional look that is easy to customize.

## 🚀 Getting Started with VS Code

The easiest way to work on this website is using **Visual Studio Code (VS Code)**.

### 1. Setup

1.  **Download & Install** [Visual Studio Code](https://code.visualstudio.com/) if you haven't already.
2.  **Download/Unzip** this portfolio folder to your computer.
3.  Open VS Code.
4.  Go to **File > Open Folder...** and select this portfolio folder.

### 2. Install Recommended Extensions

When you open this folder, VS Code might ask if you want to install "Recommended Extensions".

1.  Click **Install**.
2.  If it doesn't ask, click the **Extensions** icon on the left sidebar (looks like squares).
3.  Type `@recommended` in the search bar.
4.  Install **Live Server** and **GitHub Copilot**.

### 3. Run the Website

1.  Open `index.html` in VS Code.
2.  Look at the very bottom right corner of the VS Code window.
3.  Click the button that says **Go Live**.
4.  Your browser should automatically open showing your website!
    - _Note: Every time you save a file (Ctrl+S or Cmd+S), the browser will automatically reload to show your changes._

## ✏️ How to Edit

### 1. Changing Text

Open `index.html` in VS Code. Look for the comments I've added, like this:

```html
<!-- EDIT YOUR NAME HERE -->
<a class="navbar-brand" href="#">My Name</a>
```

Simply delete "My Name" and type your own name. Save the file, and watch the browser update!

### 2. Changing Images

1.  Save your images (jpg or png) into the `images` folder.
2.  In `index.html`, find the image tags:
    ```html
    <img src="https://via.placeholder.com/400x225" ... />
    ```
3.  Change the `src` (source) to match your file name:
    ```html
    <img src="images/my-project-photo.jpg" ... />
    ```

### 3. Changing Colors & Styles

Open `css/styles.css`. This file controls the "look" of your site.

- You can change colors, fonts, and spacing here.
- I've included some examples in the file to help you get started.

## 📂 Understanding the Files

- `index.html`: The main page of your website. It contains all the structure and text.
- `css/styles.css`: The styling rules. It tells the browser how to make things look (colors, layout tweaks).
- `images/`: A folder to keep your pictures organized.
- `.vscode/`: Settings for the editor (you can ignore this).

## 🎓 Student Superpowers (Free AI Help!)

If you have a student email (`.edu`), you can get **GitHub Copilot** for FREE! Copilot is an AI that helps you write code by suggesting lines as you type.

1.  **Sign up for the Student Developer Pack**: [GitHub Student Developer Pack](https://education.github.com/pack)
    - Click "Sign up for Student Developer Pack".
    - Verify your student status.
2.  **Enable Copilot**: Once approved, go to your GitHub settings and enable Copilot.
3.  **Use it in VS Code**:
    - Make sure you installed the **GitHub Copilot** extension (it's in the recommended list!).
    - Sign in to GitHub within VS Code.
    - Start typing code, and it will suggest completions!

## 🌐 Publishing Your Website (Netlify & Namecheap)

Once you are happy with your site, it's time to put it on the internet!

### 1. Deploy to Netlify (Free & Easy)

1.  Go to [Netlify Drop](https://app.netlify.com/drop) (or sign up for a free Netlify account).
2.  **Drag and drop** your entire project folder onto the page.
3.  Netlify will upload your site and give you a link (e.g., `random-name-123.netlify.app`).
4.  Your site is now online!

### 2. Connect Your Custom Domain (Namecheap)

If you bought a domain (like `yourname.com`) from Namecheap, follow these steps to connect it to your Netlify site.

**Step A: Get Info from Netlify**

1.  Log in to Netlify and select your site.
2.  Go to **Domain Settings** > **Add custom domain**.
3.  Enter your domain name (e.g., `yourname.com`) and click **Verify** > **Add domain**.

**Step B: Configure Namecheap**

1.  Log in to [Namecheap](https://www.namecheap.com/).
2.  Go to **Domain List** and click **Manage** next to your domain.
3.  Click on the **Advanced DNS** tab.
4.  **Delete** any existing records (trash can icon) so you have a clean slate.
5.  Click **Add New Record** (red button) and add these two records:

    - **Record 1 (Points the main domain):**

      - **Type:** `A Record`
      - **Host:** `@`
      - **Value:** `75.2.60.5` (This is Netlify's IP address)
      - **TTL:** Automatic

    - **Record 2 (Points the "www" version):**
      - **Type:** `CNAME Record`
      - **Host:** `www`
      - **Value:** `[your-site-name].netlify.app` (Replace this with your actual Netlify link, without `http://` or `/`)
      - **TTL:** Automatic

6.  Save changes. It might take a few minutes (or up to 24 hours) for the changes to work globally.

## 📚 Learn More

Here are some great free resources to help you learn:

- **HTML (The Structure):** [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- **CSS (The Style):** [W3Schools CSS Tutorial](https://www.w3schools.com/css/)
- **Bootstrap (The Layout System):** [W3Schools Bootstrap 5 Tutorial](https://www.w3schools.com/bootstrap5/)
- **FontAwesome (The Icons):** [FontAwesome Icon Search](https://fontawesome.com/search?m=free)

## 💡 Tips

- **Don't panic!** If you break something, you can always undo (Ctrl+Z or Cmd+Z).
- **Experiment.** Change numbers in the CSS or move tags around in the HTML to see what happens.
- **Google is your friend.** If you want to do something specific (like "how to center text css"), typing that into Google will usually give you the answer.
