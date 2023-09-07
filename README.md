# Instructions

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
2. Fork [this repository](https://github.com/flexiblecommits/flexiblecommits.github.io) by clicking the "fork" button in the top right.
3. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
4. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
5. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.
6. Check status by going to the repository settings, in the "GitHub pages" section
7. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://flexiblecommits.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
2. Run `index.html` in root folder.

# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch.
