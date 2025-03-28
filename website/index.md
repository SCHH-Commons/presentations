class: center, middle

## Build Your Own Website: Simple, Free, and No Coding Required!
### Presentation to SCHH Computer Club 
#### March 11, 2025
### Ron Snyder

---

## Agenda

1. Introduction
1. General Overview of How Websites are Built
1. A Walkthrough of the Tools We'll be Using for Our Site
  - GitHub
  - GitHub Pages and Jekyll
  - Markdown
1. Building the Site
  - Clone a Working Site to Get Started
  - Customize the Cloned Site
  - Adding New Posts
1. Formatting Posts with Markdown
1. Adding External Content using Iframes
  - Photo
  - Video
  - Map
  - Calendar

---

exclude: true

## About Me

**Married, father of 6 (including triplets), retired to SCHH in 2024**

**+45 years in software engineering, in both hands-on and leadership roles**
- 9 years in the US Air Force
- 15 years in defense contracting roles with McDonnell Douglas, General Electric, and General Dynamics
  - Software Engineering Manager for the M1A2 Abrams MBT
- 4 years working with a small startup on a DARPA research project involving autonomous agents
- 18 years working for a non-profit in the academic community
  - 10 years as Director of R&D for their Innovation Lab

Interests included digital imaging, knowledge graphs, digital mapping, and artificial Intelligence

---

## How a Website Works – A High-Level Overview

A **web page** is built using three main technologies:  
- **HTML (Hypertext Markup Language)** – Provides the structure and content of the page (text, images, links, etc.).  
- **CSS (Cascading Style Sheets)** – Controls the appearance of the page (colors, fonts, layout).  
- **JavaScript** – Adds interactivity and dynamic elements (such as buttons that respond when clicked).  

A **web page** is displayed in a **web browser** (Chrome, Safari, Edge, etc.) on a **user's device** (laptop, smartphone, tablet).  

Web pages are stored on **servers** (computers connected to the internet). When a user types a **web address (URL)** or clicks a link, their browser sends a request to the server. The server responds by sending back the web page, which the browser then displays.  

A **website** is a collection of one or more web pages, usually linked together so users can navigate between them.  

???
As of January 2025
- approx 3 billion people have access to the internet
- there are approx 1.2 billion websites, although ony 17% are maintained

---

## Popular Website Tools and Services

There are many ways to build a website, depending on your needs and technical comfort level.  The right tool depends on your **goals**, **technical skills**, and **how much control you want** over your site.

- **Beginner-Friendly Website Builders**  
  - **Wix** – Drag-and-drop website builder, easy for beginners  
  - **Squarespace** – Stylish templates, good for small businesses & portfolios  
- **Content Management Systems (CMS)**  
  - **WordPress** – Most popular CMS, flexible with themes & plugins  
  - **Ghost** – Lightweight blogging platform, good for writers  
- **Static Site Generators (For More Control & Speed)**  
  - **Jekyll** – Works with GitHub Pages, great for blogs & documentation  
  - **Eleventy (11ty)** – Simple and developer-friendly  
- **Other Free Hosting Options**  
  - **GitHub Pages** – Great for personal projects, integrates with Jekyll  
  - **Netlify** – Free hosting with automated deployment  
  - **Vercel** – Good for Next.js and modern web apps  

---

## Building a Website with GitHub Pages, Jekyll, and Markdown

Instead of writing complex code, we can use **simpler tools** to create and manage a website:  
- **Markdown** – A simple way to write content using easy-to-read text formatting.  
- **Jekyll** – A tool that turns Markdown files into a website.  
- **GitHub Pages** – A free hosting service that automatically publishes the website online.  

This approach lets us build a professional-looking website **without needing to code in HTML, CSS, or JavaScript**.  

???
As of Jan 2025
- 150 million accounts on GitHub
- 420 million repositories

---

## How It Works – Step by Step

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

## What is a Blog-Style Website?  

A **blog-style website** organizes content into a series of posts, usually displayed **newest first**. It’s great for:  
- Sharing updates, articles, or journal entries.  
- Organizing content into categories or tags.  
- Automatically generating a homepage that lists recent posts.  

### Why Use Jekyll?  
[Jekyll](https://jekyllrb.com/) is a **popular website generator** that turns plain text files (Markdown) into a full website. It’s popular for blogs because:  
- It **automates** the creation of blog posts and pages.  
- It uses **templates**, so posts look consistent.  
- It works with **GitHub Pages**, making publishing easy. 
- It has a large ecosystem of developers and tools

For this website starter I've stripped Jekyll's default [minima](https://github.com/jekyll/minima) theme down to its essential elements providing an out-of-the-box configuration that is easy to setup and maintain while still providing many useful features.

---

## How a Jekyll Blog Works  

1. **Write blog posts in Markdown**  
   - Each post is a simple text file, stored in the `_posts` folder.  
1. **Jekyll formats the posts automatically**  
   - It applies a template to make posts look professional.  
1. **The homepage updates itself**  
   - New posts appear at the top without extra work.  
1. **GitHub Pages hosts the site for free**  
   - Once published, your blog is live on the web.  

### Why Use This Approach?  
✅ No coding required – just write text files.  
✅ Fast, secure, and free hosting with GitHub Pages.  
✅ Updating the site is as easy as adding a new text file!  

By the end of this class, you'll have your own **simple blog-style website** using Jekyll!  

---

## The Versatility of a Blog-Style Website  

A **blog-style website** isn’t just for personal blogs—it’s a flexible format that can be used for many different types of websites.  

### **Examples of How It Can Be Used**  
🔹 **Personal Blog** – Share thoughts, stories, or daily experiences.  
🔹 **Project Updates** – Document progress on a hobby, research, or work project.  
🔹 **Event Announcements** – Post news, schedules, or recaps for a club or community.  
🔹 **Learning Journal** – Keep track of new skills, tutorials, or study notes.  
🔹 **Documentation & Guides** – Provide instructions, FAQs, or technical documentation.  
🔹 **Portfolio** – Showcase writing, photography, or other creative work.  

---

## Why a Blog-Style Website Works Well  

✅ **Easy to Update** – Just add a new post, and the site updates itself.  
✅ **Organized & Searchable** – Posts are automatically sorted by date and can be categorized.  
✅ **Customizable** – Jekyll supports themes and layouts, making it adaptable for different styles.  
✅ **No Need for Databases** – Unlike WordPress, Jekyll sites are fast and secure because they don’t rely on a backend database.  
✅ **Great for Static Content** – Perfect for any site where content doesn’t need to change in real-time.  

By structuring your site in a blog-style format, you get a **simple, low-maintenance, and flexible** way to present content for almost any purpose! 🚀  

---

class: center, middle

## A Gentle Introduction to GitHub

*What it is and how to use it to build a website*

---

## What is GitHub?  

GitHub is a **free online service** for storing and managing files, especially for websites and projects.  

### **Why Use GitHub?**  
✅ **Stores your website files safely online**  
✅ **Tracks changes** so you can go back to previous versions  
✅ **Allows collaboration** – multiple people can work on the same project  
✅ **Works with GitHub Pages** to **host your website for free**  

Think of GitHub as a **file cabinet** for your website, where everything is organized and versioned.

---

## What is a Repository?  

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

Your repository is now ready to hold your website files!

...For this class we'll use an even easier approach! -- we'll clone an existing (working) website.

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

## Next Steps: Customizing Your Website  

Now that you understand GitHub basics, we will:  

✅ Clone a Jekyll website to create your own.  
✅ Modify `_config.yml` to personalize your site.  
✅ Edit, add, and remove Markdown files for content.  
✅ Publish your site with GitHub Pages!  

---

## Getting Started: Cloning a Website  

To quickly set up your own blog-style website, we will clone an existing site.  The website we'll be cloning is a Jekyll template that only requires minor updates for a working website.

### What is Meant by "Cloning"?
🔹 Cloning creates **your own copy** of an existing GitHub repository.  
🔹 This lets you customize the site without affecting the original.  
🔹 It’s an easy way to get started with Jekyll and GitHub Pages.  

### **What’s in the Starter Website?**  

✅ A simple Jekyll blog with example posts  
✅ A basic layout, already set up for you.  
✅ Configurable settings for personalization.  

---

## Overview of Steps to Create Your Website  

1. **Clone the Repository**  
   - Go to the GitHub repository page of one of the starter sites.
       - https://github.com/SCHH-Commons/website-template, or
       - https://github.com/SCHH-Commons/schh-day-trips
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

