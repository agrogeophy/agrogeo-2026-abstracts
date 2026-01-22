# Agrogeo 2026 Abstract Submission Repository

Welcome to Agrogeo 2026! This year we are accepting submission using Curvenote and a centralized submission process that is facilitated by GitHub pull requests.

## Author Instructions

We only accept abstract submissions. All submission formats are powered by [`mystmd`][myst], and are focused on the web-first presentation of scientific content. Please only use LaTeX if you are already familiar with writing papers in LaTeX, and note that many macros will not be supported.

There are examples in the `abstracts` folder that can be used as a starting point for your submission. These templates include formatting, references, math, tables and images. This overview assumes familiarity with GitHub and Git.

<!-- Expand sections of this guide for targeting authors with less familiarity with Git or GitHub -->

- Fork and clone this repository
- In your local copy of the repository, create a branch named `abstract/<last_name>`, where `<last_name>` is your last name or appropriate identifier for your submission.
- Copy one of the existing folders in `abstracts` to a new folder with your name
- Update the ID in the `myst.yml` and title, author, and affiliation information following the instructions in the configuration
- Install [curvenote][curvenote-install] and [nodejs](https://nodejs.org)
- Run `curvenote start`, open the main abstract file, edit the content, save and see the changes in real time
- Write up your research, including any associated Jupyter Notebooks, reproducible content etc.
- Commit your content to git, ensuring you only make changes in your single folder
- Open a pull request against the origin repository
- See the GitHub actions run, and make a comment on your PR with the check results and a link to your preview
- To run these checks locally, you may run `curvenote check agrogeo --kind abstract --collection 2026`
- An editor will assign reviewers, who will make comments in GitHub, and you can respond to the comments until the reviewers and editors are satisfied with your submission. On each commit, a new preview will be made.
- The editor will mark the pull-request as accepted and merge it
- There may be extra steps the editorial team takes to make your submission live

[myst]: https://mystmd.org
[install]: https://mystmd.org/guide/quickstart
[curvenote-install]: https://curvenote.com/docs
