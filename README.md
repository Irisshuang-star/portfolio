# Personal Portfolio Website

This is a personal portfolio website built with [Quarto](https://quarto.org/), an open-source scientific and technical publishing system.

## Structure

- `index.qmd`: Homepage
- `about.qmd`: About me page
- `work.qmd`: Projects showcase
- `blog.qmd`: Blog listing page
- `blog/`: Directory containing blog posts
- `images/`: Directory for images
- `_quarto.yml`: Configuration file
- `styles.css`: Custom CSS styling

## Local Development

To preview the website locally, run:

```bash
quarto preview
```

## Building the Website

To build the website, run:

```bash
quarto render
```

This will generate the website in the `docs/` directory, ready for GitHub Pages deployment.

## GitHub Pages Deployment

1. Push the repository to GitHub
2. Go to repository settings
3. Under GitHub Pages, select the `docs` folder on the main branch as the source
4. Your website will be available at `https://yourusername.github.io/repository-name/`

## Customization

Edit the `.qmd` files to update content and the `_quarto.yml` file to change the website configuration.
