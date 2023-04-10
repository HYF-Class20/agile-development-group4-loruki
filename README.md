# Name of project

Group's 4 project that attempts to reverse engineer the Loruki website.

## Table of contents

- [Name of project](#name-of-project)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Technologies](#technologies)
  - [Code Examples](#code-examples)
  - [Source](#source)
  - [Instructions for use](#instructions-for-use)
  - [Code Quality Checks](#code-quality-checks)
  - [Continuous Integration (CI)](#continuous-integration-ci)
  - [Repo Setup](#repo-setup)

## General info

Loruki is a fictional cloud hosting website that was created by a developer to
serve as a tutorial for web development students. The website has a simple, yet
sleek design that utilizes a color scheme of blue, white, and black.

The website includes only three pages: a homepage, a features page, and a
documentation page. The homepage shows the popularity of the website as well as
brief overview of the most important features. The navigation menu is located at
the top right corner of the page for easy access.

The features page provides details on the various features offered by Loruki
each of the details being 'lorem ipsum', while the documentation page serves as
a guide for users on how to use this fake service.

## Technologies

- **HTML**
- **CSS**

Loruki was built using only HTML and CSS, making it an excellent example of how
to design a website using these foundational web development languages. It
demonstrates the importance of responsive design through the use of media
queries. The website has been optimized to provide an optimal user experience on
various devices, including desktops, tablets, and smartphones.

Loruki relies heavily on CSS grid and flexbox for layout and positioning of
various elements on the page. Furthermore, Loruki also includes a well-designed
form that allows users to sign up for the service. The form is styled using CSS,
with careful attention paid to its layout, color scheme, and user experience.

## Code Examples

```@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300&display=swap');

:root {
  --primary-color: #047aed;
  --secondary-color: #1c3fa8;
  --dark-color: #002240;
  --light-color: #f4f4f4;
  --success-color: #5cb85c;
  --error-color: #d9534f;
}

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  font-family: 'Lato', sans-serif;
  color: #333;
  line-height: 1.6;
}

ul {
  list-style-type: none;
}

```

## Source

Project was originally writtenby bradtraversy and the source code can be find
here: [source code on GitHub](https://github.com/bradtraversy/loruki-website).
The website can be visited here:
[Loruki](https://michaelfrieze-loruki.netlify.app/index.html)

## Instructions for use

<details>
  <summary>Getting Started</summary>

<!-- a guide to using this repository -->

1. `git clone git@github.com:HackYourFutureBelgium/template-markdown.git`
2. `cd template-markdown`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

## Repo Setup

- Give each member _write_ access to the repo (if it's a group project)
- Turn on GitHub Pages and put a link to your website in the repo's description
- Turn on GitHub Actions
- in the _Branches_ section of your repo's settings make sure:
  - The repository
    [requires a review](https://github.blog/2018-03-23-require-multiple-reviewers/)
    before pull requests can be merged.
  - The `master`/`main` branch must "_Require status checks to pass before
    merging_"
  - The `master`/`main` branch must "_Require require branches to be up to date
    before merging_"

</details>
