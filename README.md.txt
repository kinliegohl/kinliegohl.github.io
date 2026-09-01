# My Website

## How to Rebuild the Site

1. Open RStudio
2. New Project
3. New Directory
4. Add Repository from local file C:\Users\kmg200008\OneDrive - The University of Texas at Dallas\Documents\kinliegohl.github.io

## Build
Edit quarto.yml to look like this

project:
	type: website
	output-dir: docs
website:
	title: "Your Name"
	description: "One line about your research"
	navbar:
		left:
			- href: index.qmd
			text: Home
			- href: research.qmd
			text: Research
			- href: teaching.qmd
			text: Teaching
			- href: cv.qmd
			text: CV
		right:
			- icon: github
			href: https://github.com/USERNAME
			- icon: envelope
			href: mailto:you@utdallas.edu
format:
	html:
		theme: cosmo # try: flatly, litera, journal, darkly, sandstone                   (choose 1)
		css: styles.css
		toc: true ]


Edit index to look like this

title: "Kinlie Gohl"
image: profile.jpg
about:
	template: trestles # or: jolla, solana, marquee, column					(choose 1)
	image-shape: round
	image-width: 14em
	links:
		- icon: envelope
		text: Email
		href: mailto:kmg200008@utdallas.edu
		- icon: github
		text: GitHub
		href: https://kinliegohl.github.io/
		- icon: mortarboard
		text: Google Scholar
		href: https://scholar.google.com/citations?user=XXXX
---
I am a masters student in the social data analytics and research program at the
University of Texas at Dallas. My research examines ...
## Research Interests
- Interest one
- Interest two
- Interest three

## Run

[Render pages in Rstudio once you are done.
Then go to Github Desktop and commit any files to main.
Push the origin.
Fetch the origin.
Go to github desktop and look at deployments.
Wait and see if everything loads properly. 
Check your website https (make sure it is not local host) and check every page to see if its correct.]

You're done, everything should work properly. 
