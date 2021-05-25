# OHSU Dissertation Template

***'Forget the formatting – get to the writing!'***

This project is a Latex dissertation template following the guidelines of the School of Medicine at Oregon Health & Science University.

## Usage

**Overleaf:** This template was built in [Overleaf](https://www.overleaf.com/). To get started, I recommend grabbing it off of the [Overleaf library](https://www.overleaf.com/latex/templates/ohsu-dissertation-template/xhgmkwmftkrs). If you haven't done this before, see Overleaf's documentation on [Creating a project from a template](https://www.overleaf.com/learn/how-to/Creating_a_project_from_a_template). Overleaf's free for individual users, and $15 a month if you'd like to include collaborators. 

**Local Installation:** If you'd like to keep it local, clone this repository onto your local drive and make sure you have [pandoc](https://pandoc.org/) ready to go to render out the fruit of your hard labor. Of course, you'll also need to download and setup [LaTeX](https://www.latex-project.org/) too. If you go this route, I'd recommend installing [Homebrew](https://brew.sh/) (MacOS, Linux) or another package manager for your operating system (if it doesn't come with one already) to greatly simplify the installation of pandoc, LaTeX, and any dependencies they might require. 

## First Steps

1. To personalize this template to you, be sure to start by going into `main.tex` and updating the variables therein (lines 19 - 32). For example, change this:
`\newcommand{\projecttitle}{Your Dissertation Title}` to this `\newcommand{\projecttitle}{An Esoteric Study of the Neural Ganglion of C. elegans}`.
2. See the Background section (and its corresponding LaTeX file `sections/background.tex`) for information on creating tables and including figures, abbreviations, and citations.

## Contributing

As I write this, I'm in the last year of my PhD at OHSU. It's possible that once I finish that the style guidance will change (or be improved!) Pull requests and issues that help maintain alignment with the published style guide for OHSU School of Medicine will be included and be much appreciated! The [thesis and dissertation style guide](https://github.com/greenstick/ohsu-dissertation-template/blob/main/resources/preparation-of-dissertation-and-thesis.pdf) I've followed is in the resources folder. Further, if your department of school has more specific guidance, branches are encouraged!

## How Can I Say Thank You?

No need! Seriously. But, if you did find this helpful and feel like you have change to spare, here's one way you can show your appreciation!

[![Buy me a coffee][buymeacoffee-icon]][buymeacoffee-link]

[buymeacoffee-link]: https://www.buymeacoffee.com/O1TrCFSXa
[buymeacoffee-icon]: https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png
