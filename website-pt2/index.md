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

## Adding Content From External Sites using Iframes

An **iframe** (short for **inline frame**) is a special feature in web pages that allows you to display content from another website or source inside your own page—kind of like a **window inside a window**.  

Think of an iframe like a **picture frame**, but instead of holding a photo, it holds another web page, a video, a map, or even interactive content.  

### Why Are Iframes Useful?

Iframes allow you to:  
- **Embed Videos** – Display a YouTube or Vimeo video inside your webpage.
- **Show Maps** – Add a Google Map without needing to send visitors to another website.
- **Include External Content** – Display content from another site (like a form or a document) without making users leave your page.

---

## YouTube Iframe Example

```html
<iframe width="560" height="315" 
  src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
  frameborder="0" allowfullscreen>
</iframe>
```

<iframe width="560" height="315" 
  src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
  frameborder="0" allowfullscreen>
  
---

## Sites that Provide Iframe Embed Codes

### 📍 Maps & Geographic Content

1. **[Google Maps](https://maps.google.com)** - Search a location → Click “Share” → Choose “Embed a map” to get the iframe code.
1. **[OpenStreetMap](https://www.openstreetmap.org)** - Navigate to a map area → Click “Share” icon → Copy the HTML iframe code.
1. **[WeatherWidget.io](https://weatherwidget.io)** - Customize a widget on the homepage → Click “Get code” to copy the iframe.

### 🎥 Media & Video

1. **[YouTube](https://www.youtube.com)** - Click “Share” under a video → Select “Embed” → Copy iframe code.
1. **[Vimeo](https://vimeo.com)** - Click the “Share” icon on a video → Copy the embed iframe code.
1. **[Twitch](https://www.twitch.tv)** - Visit [Twitch Embed Docs](https://dev.twitch.tv/docs/extensions/reference/#iframe-embedding) for instructions on live stream embed.
1. **[Spotify](https://open.spotify.com)** - Click “...” next to song/playlist → “Share” → “Embed” → Copy iframe.

---

### 📰 News & Information

1. **[Twitter/X](https://publish.twitter.com)** - Paste tweet/user URL → Customize → Copy the iframe embed code.
1. **[NPR](https://www.npr.org)** - Many audio stories have an “Embed” option under the media player.
1. **[The Guardian](https://www.theguardian.com)** - For some interactives and infographics, use developer tools or contact for embed permissions.

### 📚 Learning & Reference

1. **[Wikimedia Commons](https://commons.wikimedia.org)** - Use image or media file page → Scroll to “Use this file” → Copy iframe or embed snippet.
1. **[Desmos](https://www.desmos.com/calculator)** - Create a graph → Click “Share” → Copy the embed code.
1. **[GeoGebra](https://www.geogebra.org)** - Create an activity → Click “Share” → Choose “Embed” for iframe.

---

### 🖼️ Art & Visualization

1. **[Google Arts & Culture](https://artsandculture.google.com)** - Some exhibits/tools offer “Embed” via share menu or use [Google Art Project API](https://developers.google.com/cultural-institute) for custom embedding.
1. **[Sketchfab](https://sketchfab.com)** - View a model → Click “Embed” under the viewer → Copy iframe code.
1. **[GIPHY](https://giphy.com)** - Click on a GIF → Click “Share” → Choose “Embed” to get the iframe.
1. **[Flickr](https://www.flickr.com)** - Open an image → Click the "Share" icon (arrow) → Choose “Embed” tab → Copy the iframe code (includes attribution).
1. **[Openverse](https://openverse.org)** - Search for an image → Click on the image → Use “Copy HTML” under "Use this content" section (typically an `<img>` tag, not an `<iframe>` — can be wrapped in custom HTML if needed).

### ⚙️ Miscellaneous / Fun

1. **[JokeAPI Wrapper Site](https://jokeapi.dev)** - Use a frontend like [https://icanhazdadjoke.com/api](https://icanhazdadjoke.com/api) with a custom iframe widget.
1. **[Internet Archive](https://archive.org)** - Visit a page → Click “Share” → Copy “Embed” iframe code.
1. **[NASA APOD](https://apod.nasa.gov/apod/astropix.html)** - Some images allow iframe embedding via third-party tools or GitHub-hosted viewers.

---

### 📄 Google Workspace Embeds

1. **[Google Sheets](https://sheets.google.com)** - File → Share → “Publish to the web” → Choose sheet or entire document → Copy the provided iframe embed code.
1. **[Google Slides](https://slides.google.com)** - File → Share → “Publish to the web” → Choose embed → Set dimensions/autoplay → Copy iframe code.
1. **[Google Docs](https://docs.google.com/document)** - File → Share → “Publish to the web” → Click “Embed” → Copy the iframe snippet.
1. **[Google Calendar](https://calendar.google.com)** - Settings (⚙️) → Settings for a specific calendar → Scroll to “Integrate calendar” → Copy iframe from the “Embed code” field.

---

### 🎙️ Podcast Platforms

1. **[Spotify](https://podcasters.spotify.com)** - Go to a show or episode → Click the “...” button → Select “Share” → Click “Embed” → Customize and copy the iframe.
1. **[Apple Podcasts](https://podcasts.apple.com)** - Find a podcast on the web → Click “Share” → Choose “Embed” → Copy the iframe code (only available via the web interface, not in the app).
1. **[Buzzsprout](https://www.buzzsprout.com)** - Open a podcast episode → Click “Embed this ONE episode” or “Embed multiple” → Copy the iframe snippet.
1. **[Anchor](https://anchor.fm)** *(now part of Spotify for Podcasters)* - Episodes created with Anchor can be embedded via Spotify’s iframe tools.
1. **[Simplecast](https://www.simplecast.com)** - View an episode page → Click the “Share” icon → Choose “Embed Player” → Copy the iframe.
1. **[Transistor.fm](https://transistor.fm)** - Each episode has an “Embed” button with iframe options for both full player and mini player.
1. **[Castos](https://castos.com)** - Episodes have embed options within the dashboard → Choose player style → Copy iframe.
1. **[Podbean](https://www.podbean.com)** - Open an episode → Click “Share” → Select “Embed” → Customize and copy the code.

---

### 📊 Charts, Data & Dashboards

1. **[Datawrapper](https://www.datawrapper.de)** - Create a chart → Publish & embed → Copy iframe from the “Embed” tab.
1. **[Flourish](https://flourish.studio)** - Build a visualization → Click “Export & publish” → Choose “Embed” for iframe.
1. **[TradingView](https://www.tradingview.com/widget/advanced-chart/)** - Customize chart widget → Click “Get Widget” → Copy generated iframe code.

### 🌐 Web Tools & Widgets

1. **[CodePen](https://codepen.io)** - Open a Pen → Click “Embed” → Customize and copy the iframe code.
1. **[JSFiddle](https://jsfiddle.net)** - Save a fiddle → Click “Share” → Copy the iframe embed snippet.
1. **[Replit](https://replit.com)** - Open a project → Click “Share” → Copy the iframe embed code.
1. **[Padlet](https://padlet.com)** - Open a padlet → Click “Share” → Enable embed → Copy iframe code.
1. **[Calendly](https://calendly.com)** - Go to “Share Your Link” → “Add to Website” → Choose embed option.
1. **[Typeform](https://www.typeform.com)** - Open form → Click “Share” → “Embed into a web page” to get the code.

---

## Wikimedia Commons Example

<p style="width:60%;"><a href="https://commons.wikimedia.org/wiki/File:Mount_Washington_Cog_Railway_October_2021_015_edit.jpg#/media/File:Mount_Washington_Cog_Railway_October_2021_015_edit.jpg"><img style="width:100%;height:unset;" src="https://upload.wikimedia.org/wikipedia/commons/b/b1/Mount_Washington_Cog_Railway_October_2021_015_edit.jpg" alt="Mount Washington Cog Railway October 2021 015 edit.jpg" height="4000" width="4000"></a><br>By <a href="//commons.wikimedia.org/wiki/User:King_of_Hearts" title="User:King of Hearts">King of Hearts</a> - This file was derived from: <a href="//commons.wikimedia.org/wiki/File:Mount_Washington_Cog_Railway_October_2021_015.jpg" title="File:Mount Washington Cog Railway October 2021 015.jpg">Mount Washington Cog Railway October 2021 015.jpg</a>:&nbsp;<span typeof="mw:File"><a href="//commons.wikimedia.org/wiki/File:Mount_Washington_Cog_Railway_October_2021_015.jpg" class="mw-file-description"></a></span>, <a href="https://creativecommons.org/licenses/by-sa/4.0" title="Creative Commons Attribution-Share Alike 4.0">CC BY-SA 4.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=138455036">Link</a></p>

---

## Detailed Instructions

Each of the stater templates contains a `README.md` file in the repository root directory.

The README.md file provides more detailed instructions for setting up and maintaining your site.

**Click here and let's get started!** - [https://github.com/SCHH-Commons/website-template](https://github.com/SCHH-Commons/website-template)

