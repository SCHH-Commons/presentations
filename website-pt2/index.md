class: center, middle

## Build Your Own Website: Part 2
### Presentation to SCHH Computer Club 
#### March 31, 2025
### Ron Snyder

---

## Agenda

1. Introduction
1. Part 1 Refresher
    - GitHub
    - Cloning the Website Template
    - Adding, deleting, modifying posts
1. Formatting Posts with Markdown
1. Adding External Content using Iframes
  - Photo
  - Video
  - Map
  - Calendar

---

## How Our Site Works

1. **Write content in Markdown**  
   - Instead of using complicated code, we write text with simple formatting (like `#` for headings or `**bold**` for bold text).  

2. **GitHub stores the website files**  
   - These files are saved in a special online folder (a GitHub repository).  

3. **Jekyll converts Markdown into a website**  
   - It automatically turns Markdown text into web pages with a clean layout.  

4. **GitHub Pages publishes the website**  
   - The website is made live on the internet using a free web address (e.g., `yourname.github.io`).  

Once set up, updating the website is as easy as **editing a text file**—no need to touch complicated code!  

---

## Blog-Style Websites  

A **blog-style website** organizes content into a series of posts, usually displayed **newest first**. It’s great for:  
- Sharing updates, articles, or journal entries.  
- Organizing content into categories or tags.  
- Automatically generating a homepage that lists recent posts.  

### Jekyll
[Jekyll](https://jekyllrb.com/) is a **popular website generator** that turns plain text files (Markdown) into a full website. It’s popular for blogs because:  
- It **automates** the creation of blog posts and pages.  
- It uses **templates**, so posts look consistent.  
- It works with **GitHub Pages**, making publishing easy. 
- It has a large ecosystem of developers and tools

For this website starter I've stripped Jekyll's default [minima](https://github.com/jekyll/minima) theme down to its essential elements providing an out-of-the-box configuration that is easy to setup and maintain while still providing many useful features.

---

## GitHub 

GitHub is a **free online service** for storing and managing files, especially for websites and projects.  

### **Why Use GitHub?**  
✅ **Stores your website files safely online**  
✅ **Tracks changes** so you can go back to previous versions  
✅ **Allows collaboration** – multiple people can work on the same project  
✅ **Works with GitHub Pages** to **host your website for free**  

Think of GitHub as a **file cabinet** for your website, where everything is organized and versioned.

---

## GitHub Repositories  

A **repository (repo)** is like a folder that stores all the files for a project.  

### **In a GitHub Repository, You Can:**  
📂 Store files – like your website content and settings  
📜 Edit and update files – change text, images, or settings  
🌐 Publish your site – GitHub Pages makes it live on the web  
🔄 Track changes – see what’s been updated over time  

Each website we create will have **its own repository** on GitHub.

---

## Creating a Repository  

### **Steps to Create a New Repository:**  
1. Go to [GitHub.com](https://github.com) and sign in.
1. Click the green **New** button located in the top-left portion of the page.
1. Give it a name (e.g., `my-blog`) and add a description.
1. Choose **Public** (so GitHub Pages can host it).
Check the **Add a README file** Checkbox.
1. Click **Create repository**.

---

## Adding, Deleting, and Modifying Files  

- **Adding a File**  
  1. Open your repository on GitHub.
  1. Click **Add file** → **Create new file**.
  1. Enter a name (e.g., `about.md`), add some text, and click **Commit changes**.
-  **Deleting a File**
  1. Find the file you want to delete in your repository.
  1. Click on it, then click the **trash can** icon.
  1. Confirm by clicking **Commit changes**.
- **Editing an Existing File**
  1. Click on the file in your repository.
  1. Click the **pencil icon** to edit.
  1. Make your changes, then click **Commit changes**.

These basic steps will let you **update and manage your website** easily!

---

## Creating a Website  

To quickly set up your own blog-style website, we will clone an existing site.  The website we'll be cloning is a Jekyll template that only requires minor updates for a working website.

🔹 Cloning creates **your own copy** of an existing GitHub repository.  
🔹 This lets you customize the site without affecting the original.  
🔹 It’s an easy way to get started with Jekyll and GitHub Pages.  

### **What’s in the Starter Website?**  

✅ A simple Jekyll blog with example posts  
✅ A basic layout, already set up for you.  
✅ Configurable settings for personalization.  

---

## Website Creation - Step by Step  

1. **Clone the Repository**  
   - Go to the GitHub repository page of the Website Template.
       - https://github.com/SCHH-Commons/website-template
   - Click the green **Use this template** button located in the top-right section of the page and then select the **Create a new repository** option.
   - This creates a copy in **your own GitHub account**.  
1. **Modify the `_config.yml` File**  
   - Update site title, description, and other settings.  
1. **Customize Your Content**  
   - Edit or delete the example blog posts.  
   - Add new Markdown files for your own posts.  
1. **Publish Your Site**  
   - GitHub Pages will automatically generate your website.  
   - View it at `yourusername.github.io/repository-name`.  

After this process, you’ll have **your own personalized website** up and running!

---

## Detailed Instructions

Each of the stater templates contains a `README.md` file in the repository root directory.

The README.md file provides more detailed instructions for setting up and maintaining your site.

**Click here and let's get started!** - [https://github.com/SCHH-Commons/website-template](https://github.com/SCHH-Commons/website-template)

