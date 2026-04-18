GitHub Pages Deployment Guide
===========================

Follow these steps to successfully host your site on GitHub:

1. FOLDER CONTENT:
   Inside this "gitpages-only" folder, you must have the following files:
   - index.html (the one provided here)
   - webbanner123.mp4
   - photo dan.png (Recommend renaming this to photo-dan.png and updating index.html line 228 if possible, but the code currently looks for photo%20dan.png)
   - 1.jpeg, 2.jpeg, 3.jpeg... (Your gallery images)

2. UPLOAD:
   Upload ONLY the content of this "gitpages-only" folder to the root of your GitHub repository.
   Do NOT upload the other project files like "package.json", "src", "vite.config.ts", etc., as they are only used for development and will confuse GitHub Pages.

3. ACTIVATE PAGES:
   - In your GitHub repository, go to [Settings] -> [Pages].
   - Under "Build and deployment", set "Source" to "Deploy from a branch".
   - Select your branch (e.g., main) and the folder as "/ (root)".
   - Click Save.

Once activated, your site should be live at: https://yourusername.github.io/your-repository-name/

TROUBLESHOOTING:
- If you see a blank screen, it's likely a script error. Check the browser console (Right-click -> Inspect -> Console).
- Ensure all filenames match exactly, including the extension (.jpeg vs .jpg).
