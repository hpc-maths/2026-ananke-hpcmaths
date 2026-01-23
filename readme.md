This repository contains Quarto files and configurations for creating presentations.

Quarto must be installed to use this template. For installation instructions, visit the [Quarto website](https://quarto.org/docs/get-started/).

## How to use this template locally

1. Fork the repository to your own presentation repository.
1. Clone or download the forked repository to your local machine.
2. Open the Quarto files in your preferred editor (e.g., VSCode).
3. Customize the content as needed for your presentation in `index.qmd`.
4. Render the presentation using Quarto commands.

   ```bash
   quarto preview
   ```

## How to deploy the presentation online

We provide GitHub Actions workflows to automatically deploy your presentation to GitHub Pages. But you have to initialize the process by following these steps:

1. Ensure your presentation repository is hosted on GitHub.
2. Run the command below to create the initial deployment commit:

   ```bash
   quarto publish gh-pages
   ```

Now, every time you push changes to the main branch, the GitHub Actions workflow will automatically build and deploy your presentation to GitHub Pages.