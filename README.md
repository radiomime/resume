# Resume

## Usage

To generate a PDF from this LaTeX code, navigate to this folder in a terminal and run:

    pdflatex resume.tex

### While writing, compile on change

```sh
# compile new pdf on file save
latexmk -pdf -pvc resume.tex

# view new file via auto-refresh
open -a Skim resume.pdf
```

## Requirements

You will need to have `pdflatex` installed on your machine.

Alternatively, you can use a site like [ShareLaTeX](https://sharelatex.com) to build and edit your LaTeX instead.

## How to

## Interview notes

### questions

- Any environment mandates? I use mac and neovim, will that be an issue?

## Resume Advice

Listing some things to keep in mind when creating a resume below, a sort of checklist to lean back on

1. Show Impact, Not Just Duties
   • Focus on the impact you’ve made: “Reduced API latency by 50%,” “Led a team of five engineers on microservices migration,” etc.
2. Highlight Technical Leadership
   • Discuss design reviews, mentorship, architectural decisions, and cross-functional work.
3. Include Key Technologies
   • Senior roles often require broad experience. Summarize your primary programming languages, frameworks, and tooling in a concise Skills section.
4. Keep it to 1–2 Pages
   • Even as a senior engineer with a longer track record, avoid going beyond 2 pages unless absolutely necessary.
5. Use Clear Formatting
   • Make sure your contact info and headings are easy to read. Add enough white space so the resume doesn’t feel cramped.
