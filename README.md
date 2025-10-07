# 🌐 Personal Website

This repository contains the source code for my personal website built with [**Quarto**](https://quarto.org/) and **R**. The site highlights my projects, research interests, and professional experience.

🔗 **Live site:** <https://hectorfajardo.github.io/>

------------------------------------------------------------------------

## 📄 Overview

-   The site content is authored in Quarto (`.qmd`) documents.
-   GitHub Pages serves the rendered HTML stored in the `docs/` directory.
-   `_freeze/` caches generated assets to speed up subsequent renders.

------------------------------------------------------------------------

## 🛠️ Technology Stack

To update the site: 
1. Edit or add content in this repository. 
2. Commit and push the changes to the `main` branch. 
3. GitHub Pages will automatically rebuild and publish the site.

------------------------------------------------------------------------

## 🔄 Deployment

GitHub Pages is configured to publish the contents of `docs/` from the `main` branch. To update the live site:

1.  Edit or add content locally.
2.  Run `quarto render` if you want to update the generated files before committing.
3.  Commit and push your changes to `main`.
4.  GitHub Pages will automatically serve the updated content.

------------------------------------------------------------------------

## 📁 Repository Structure

```         
.
├── PersonalBlog.Rproj       # RStudio project file
├── README.md
├── _freeze/                 # Quarto cache of rendered outputs
│   ├── posts/
│   └── site_libs/
├── _quarto.yml              # Global Quarto configuration
├── about.qmd
├── about/                   # Static assets for the About page
│   └── about_profile.jpg
├── blog.qmd
├── cv.qmd
├── cv/                      # Supporting assets for the CV page
│   └── CV_Fajardo_Hector.pdf
├── docs/                    # Rendered site published by GitHub Pages
│   ├── about/
│   ├── cv/
│   ├── posts/
│   └── site_libs/
├── home_pic.jpg
├── index.qmd                # Homepage source
├── posts/
│   ├── _metadata.yml        # Shared metadata for blog posts
│   ├── post-with-code/
│   │   ├── image.jpg
│   │   └── index.qmd
│   └── welcome/
│       ├── index.qmd
│       └── thumbnail.jpg
├── research_projects.qmd
├── science_communication.qmd
└── styles.css               # Custom site styling
```

------------------------------------------------------------------------

## 📜 License

A license has not been specified for this repository. If you plan to reuse the content, please contact the repository owner.
