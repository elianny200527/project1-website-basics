# Project 1 – Website Basics

Template for Project 1 in MMP 240

This repository contains the starter files for **Project 1**. Follow the instructions below to set up and build your project.

---

## Step 1: Create Your Repository
1. Log in to **GitHub**.  
2. Go to this repository and click the **“Use this template”** button.  
3. Give your new repository a name (for example: `project1-website-basics`).  
   - Make sure you are creating it **under your GitHub account**.  
4. Once created, check the top left corner to confirm that the repo name has **your GitHub username** before the repository name.  

---

## Step 2: Open in VS Code

1. On your computer, make sure you have a folder where you will keep all of your **MMP 240 projects**.  
   - For example, create a folder called `MMP240` in your Documents folder.  

2. In your browser, go to your new GitHub repository page.  
   - Click the green **Code** button.  
   - Make sure the Local tab is selected
   - Make sure **HTTPS** is selected.  
   - Copy the URL that looks like this:  
     ```
     https://github.com/your-username/your-repo-name.git
     ```

3. Open **VS Code**.  
   - From the menu, choose **File > New Window** so you start fresh.  
   - In the new window, click on **Clone Git Repository** (you may see this in the middle of the screen or in the Source Control view).  

4. Paste in the URL you copied from GitHub and press **Enter**.  

5. VS Code will ask you to choose a location to save the repository.  
   - Navigate to your `MMP240` folder and select it.  
   - VS Code will create a new subfolder inside it with the same name as your repository.  

6. When it finishes, VS Code will ask if you want to **Open the repository**.  
   - Click **Open**.  

7. VS Code may also ask if you **trust the authors** of the repository.  
   - Click **Yes, I trust the authors**.  

8. If you still see the **Welcome window**, you can close it so you only see your project files in the Explorer sidebar.  

You should now see your repository files (`index.html`, `style.css`, etc.) ready to edit in VS Code.  

---

## Step 3: Create `html-guide.html`
1. In VS Code, create a new file named **`html-guide.html`**.  
2. Type `!` and press **Tab** to use **Emmet** and insert the basic HTML structure.  
3. Copy the **header** and **footer** from `index.html` into your new file.
4. Create a main element between the header and footer elements like below
   
	&lt;header&gt;
      ... existing header content here
    &lt;/header&gt;
 
    &lt;main&gt;
      ... you will paste content here
    &lt;/main&gt;
 
    &lt;footer&gt;
      ... exsting footer content here
    &lt;/footer&gt;
   
6. Open the provided text file **`Project1-HTML-Quick-Guide.txt`**.  
7. Paste the content into the `<main>` section of your new page.  
8. Add proper **HTML markup** to the content:
   - Use `<h1>` for the page title
   - `<h2>` for sections
   - `<p>` for paragraphs
   - `<ul>/<ol>` with `<li>` for lists
   - `<a>` for links  
9. Preview your page in VS Code (use **Open with Live Previewr** if installed, or open the file in your browser).  
10. Check the editor for any red underlines or warnings that may indicate syntax errors.  

---

## Step 4: Create `css-guide.html`
1. Repeat the same process for **`css-guide.html`**.  
2. Paste in the content from **`Project1-CSS-Quick-Guide.txt`**.  
3. Add HTML markup to structure the content properly.  

---

## Step 5: Style with `style.css`
1. You already have a **`style.css`** file in the repo.  
2. In the `<head>` of each page (`index.html`, `html-guide.html`, `css-guide.html`), confirm there is a line linking the stylesheet:  
   `<link rel="stylesheet" href="style.css">`
3. In style.css, start with the primary styles inside the html selector that is already there.
   - Set the base font-family, font-size, line-height, color.
   	  - For those who used the project styles form, click on View as CSS to see the styles which you can copy and paste.
   - Add styles for headings (h1, h2), paragraphs (p), and lists (ul, ol, li).
   	  - Again, you can use CSS from the projects styles form's View as CSS
   - Use pseudo-classes (a:link, a:hover, a:visited) to style links.
      - Again, you can use CSS from the projects styles form's View as CSS

⸻

## Step 6: Push Your Work to GitHub
1.	In VS Code, save all your changes.
2.	Open the **Source Control** tab (branch icon).  
3. Under **Changes**, type a short message about what you changed (e.g., *“Added new pages about HTMl and CSS and updated text styles”*).  
4. Click the **Commit** button.  
	- If VS Code says *“There are no staged changes to commit”*, click **Yes** to stage all changes.  
5. After committing, click the **Sync Changes** button to upload your changes to GitHub.  
6.	Go to your GitHub repository online and confirm your files and changes are there.

⸻

## Step 7: Publish with GitHub Pages
1.	In your GitHub repo on the GitHub site, Click on Settings
2.  In the Settings, click on Pages in the navigation on the left.
3.	Under **Build and deployment**, select Deploy from a branch (may be selected already).
4.	Under **Branch**, Select the main branch and / (root) folder.
5.	Click Save.
6.	After a minute, refresh the page to see your published site link.

⸻

✅ You now have a multi-page website with consistent navigation, styled typography, and published on the web!


