Tutorial: Building Your Project 03 Website Prototype
====================================================

This tutorial walks you through the end-to-end process of building your final project. By following these steps, you will meet all technical and professional requirements for the final grade.

Phase 1: Repository Setup
-------------------------

1.  **Create the Repository:** In GitHub (or via GitHub Desktop), create a new public repository.

    -   **Name:** Follow your continuity roadmap name (e.g., `username-project-03` or `username.github.io`).

    -   **Initialize:** Add a `README.md` and a `.gitignore` (choose the 'Yeoman' or 'Web' template if available, or leave it blank).

2.  **Clone to Local:** Open the repository in **GitHub Desktop** and clone it to your local machine.

3.  **Open in VS Code:** Navigate to the folder and open it in VS Code.

Phase 2: Folder Structure & Documentation
-----------------------------------------

Project 03 requires a specific organizational structure.

1.  **Create the `docs/` Folder:** In your root directory, create a folder named `docs`.

2.  **Move/Create Markdown Files:**

    -   Place your `scope.md` (from Assignment 03) inside the `docs/` folder.

    -   Create a `plan.md` file (including your TAME risk analysis and task list).

    -   Create a `retrospective.md` file (you will fill this out *after* the build).

3.  **Draft the README:** In the root `README.md`, provide a project title, a brief description, and a placeholder for your live URL.

Phase 3: Building the Website (HTML)
------------------------------------

1.  **Create the HTML Files:** In the **root directory**, create `index.html` and `about.html`.

2.  **Semantic Structure:** Every page must include:

    -   `<!DOCTYPE html>` and `<html>` tags.

    -   A `<head>` section with a `<title>` and a link to your CSS.

    -   A `<body>` utilizing semantic tags: `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`.

3.  **Navigation:** Ensure both pages have a `<nav>` menu that links to each other correctly.

    -   Example: `<a href="index.html">Home</a>` and `<a href="about.html">About</a>`.

Phase 4: Styling (CSS)
----------------------

1.  **Create the CSS File:** In the **root directory**, create `style.css`.

2.  **Link the CSS:** Add the following line to the `<head>` of **both** HTML pages: `<link rel="stylesheet" href="style.css">`

3.  **Apply Styles:** Use the "Cozy" or "Professional" palettes defined in your scope. Focus on:

    -   Box model properties (`padding`, `margin`).

    -   Typography (web-safe fonts).

    -   Layout (using Flexbox or basic centering).

Phase 5: Version Control (The Narrative)
----------------------------------------

Your commit history is worth **30% of your grade**. Do not upload all files at once.

1.  **Commit 1:** "Initial repo setup with README and documentation folder."

2.  **Commit 2:** "Added index and about pages with semantic HTML structure."

3.  **Commit 3:** "Applied custom CSS styling and finalized navigation links."

4.  **Push:** Click "Push to Origin" in GitHub Desktop after every commit.

Phase 6: Deployment (The Launch)
--------------------------------

1.  **Enable GitHub Pages:**

    -   Go to your repo on GitHub.com.

    -   Click **Settings** -> **Pages**.

    -   Under "Branch," select **main** and **/ (root)**. Click **Save**.

2.  **Verify:** Wait 1--2 minutes, then refresh until you see "Your site is live at..."

3.  **Add the Link:** Copy the live URL and paste it into the "About" section of your GitHub repo and into your `README.md`.

Phase 7: Final Check
--------------------

-   [ ] Does the site match my **Assignment 03 Scope Statement**?

-   [ ] Are all files (`index`, `about`, `style`) in the root directory?

-   [ ] Is the documentation (`scope`, `plan`, `retrospective`) in the `docs/` folder?

-   [ ] Are there at least 3 distinct commits in the history?

**Final Step:** Submit the URL of your GitHub Repository to the Project 03 portal on Canvas.
