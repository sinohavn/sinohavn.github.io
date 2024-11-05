# sinohavn.github.io

This repository hosts the source and deployment files for the [避风港](http://sinohavn.github.io), created with [Hugo](https://gohugo.io/) and deployed on GitHub Pages using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. The setup for this repository follows the example site configuration from [PaperMod’s example site](https://github.com/adityatelange/hugo-PaperMod/tree/exampleSite).

## Project Structure

- **`source` branch**: Contains the Hugo source files for the website. All content, theme configuration, and static assets are managed in this branch.
- **`main` branch**: Used by GitHub Pages to serve the website. 

## Deployment Workflow

This repository uses GitHub Actions to automate the deployment process, and the deployment configuration is managed in `.github/workflows/deploy.yml`.

## Running Locally

To make changes and view the website locally, you can follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/sinohavn.github.io.git
   ```

2. **Switch to the source branch**:
   ```bash
   git checkout source
   ```
3. **Install Hugo**:
   Follow [Hugo's installation guide](https://gohugo.io/getting-started/installing/) if you haven't installed it already.

4. **Run the site locally**:
   ```bash
   hugo server -D
   ```
   Visit http://localhost:1313 to view the site in your browser.

## To make changes:

1. **Edit Content**: Add or modify files in the `content` folder on the `source` branch to update the site's content.
2. **Push Changes**: Commit and push changes to the `source` branch. The GitHub Actions workflow will automatically rebuild and deploy the site.

## Contributing

Contributions are welcome! Whether you want to suggest general improvements, report bugs, write blogs, or post your events on our page, we’d love to hear from you.

## Contact

For questions or suggestions, feel free to reach out to the site maintainer at [sinohavn5@gmail.com](mailto:sinohavn5@gmail.com).
