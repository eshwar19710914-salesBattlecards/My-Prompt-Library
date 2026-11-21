# My Prompt Library

A modern, responsive personal prompt library hosted as a static site on GitHub Pages.

## Features
- Search prompt titles, descriptions, categories, tags and prompt text
- Filter by category and difficulty
- Favourites and dark/light theme (stored in the current browser)
- Fill in `{{variables}}` before copying a prompt
- Add personal prompts (stored in the current browser)
- Responsive desktop and mobile layout

## Starter categories
- Product Management
- Project & Agile Delivery
- AI & GenAI
- Data Analytics
- Leadership
- Finance
- EMBA & Academics
- Digital Transformation

The starter collection contains 19 original prompt templates. It does not reproduce the complete contents of the Prompt Vault reference site. Third-party prompts should only be imported where redistribution is permitted by the applicable licence or rights holder; retain any required attribution.

## Enable GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Open the **Actions** tab and select **Deploy static site to GitHub Pages**.
4. After GitHub Pages is enabled, re-run the failed deployment run, or push a new commit to `main`.
5. Once the workflow succeeds, the site will be available at:
   `https://eshwar19710914-salesBattlecards.github.io/My-Prompt-Library/`

## Editing and persistence
The starter prompts are embedded in `index.html`. The **Add prompt** and **Favourites** features save to browser local storage; they are local to that browser/device and are not automatically committed to GitHub. To distribute a new prompt to all visitors, edit the starter prompt array in `index.html` and commit the change.

## Privacy
Do not enter confidential, personal, customer or employer-sensitive data into prompts unless you are authorised to do so and the AI service you use is approved for that information.
