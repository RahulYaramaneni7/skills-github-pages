Step 1: Create a Repository
To start, create a new repository on GitHub. For a user or organization site, name the repository <username>.github.io or <organization>.github.io and ensure all letters are lowercase 
GitHub
GitHub
+1
. You can choose to make the repository public or private (depending on your plan) and optionally initialize it with a README file 
GitHub
GitHub
+1
. Click Create repository to proceed.

Step 2: Add Your Content
GitHub Pages looks for an entry file such as index.html, index.md, or README.md at the top level of your repository or publishing folder 
GitHub
GitHub
. You can create this file directly on GitHub by clicking Add file > Create new file, then add your HTML, Markdown, or other static content 

. For example, a simple index.html could include a heading, paragraph, and image to display on your site 



Step 3: Configure the Publishing Source
Navigate to your repository Settings, then select Pages under the "Code and automation" section 

. Under Build and deployment, choose a publishing source:

Deploy from a branch: Select the branch (e.g., main) and folder (root or /docs) where your site files are located 
The GitHub Blog
The GitHub Blog
.
GitHub Actions workflow: Use a workflow to build and deploy your site automatically, which is useful for static site generators like Next.js 
The GitHub Blog
The GitHub Blog
+1
.
Step 4: Customize Your Site
You can edit the README.md or index.html to add content, and optionally configure _config.yml to change the site title or other settings 

. If you want a custom domain, GitHub Pages allows you to configure it in the Pages settings 

Step 5: Publish and View
Once your files are committed and the publishing source is configured, your site will be live at https://<username>.github.io or your custom domain. Changes may take up to 10 minutes to appear after pushing updates 

. You can continue editing your files and committing changes to update your site.
