
**Index.html Code Explanation:**

1. **Document Structure and Type Declaration:**
   - The document begins with a DOCTYPE declaration, indicating that it's an HTML5 document.
   - The HTML structure consists of elements like `<html>`, `<head>`, and `<body>`.

2. **Head Section:**
   - The `<head>` section includes metadata and links to external resources.
   - It sets the document title, character set, and viewport settings.
   - Additionally, internal CSS styles for page layout and design are defined within the `<style>` tags.

3. **Body Content:**
   - The `<body>` section contains the visible content of the webpage.
   - It starts with a `<header>` displaying the title "Quantitative Trading and Analysis Portfolio".
   - The main content is organized within `<section>` elements, each comprising an `<h2>` heading and `<p>` paragraph for text content.

4. **Footer:**
   - The footer section provides contact information, including email and LinkedIn profile links.

5. **Styling:**
   - CSS styles within the `<style>` tags define the visual presentation of the content, including fonts, colors, and layout.

**GitHub Pages Deployment with Jekyll:**

1. **Workflow Setup:**
   - A GitHub Actions workflow named `jekyll-gh-pages.yml` is configured within the repository's `.github/workflows` directory.
   - This workflow automates the build and deployment process of the Jekyll site to GitHub Pages.

2. **Workflow Triggers:**
   - The workflow triggers on pushes to the default branch (main) and can also be manually triggered from the GitHub Actions tab.

3. **Workflow Structure:**
   - The workflow comprises two jobs: `build` and `deploy`, each executing specific tasks.
   - The `build` job runs on an Ubuntu environment, responsible for generating the Jekyll site.
   - Following the `build` job, the `deploy` job deploys the built site to GitHub Pages.

4. **Permissions and Concurrency:**
   - Permissions are set to allow the workflow to read repository contents and write to GitHub Pages.
   - Concurrency settings ensure only one concurrent deployment, avoiding potential conflicts.

5. **YAML Code Explanation:**
   - YAML code within the workflow file (`jekyll-gh-pages.yml`) defines the workflow's structure, including event triggers, permissions, concurrency settings, jobs, and steps.
   - Each step in the workflow executes specific actions, such as checking out the repository, building the Jekyll site, and deploying to GitHub Pages.

To visit the site: https://yllvar.github.io/j4nt4n/
