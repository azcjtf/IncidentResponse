# How This Works
This page is meant to be a reference into how this site was created. Nothing magical was done, but it does tie together various (free, open source) solution that combine to create a powerful team maintained and curated solution.

## Technologies
The following solutions are used in the creation of this site. While the steps below can help you (re)create your own site, some research and familiarity will help you 'make it your own'.

- Markdown: Markdown is a documentation markup language (think HTML) for creating documents using a streamlined syntax and toolset. All documents in this site are created using Markdown for formatting.
- [GitHub](https://github.com): Github is the document repository itself, and runs a CI/CD (action) job to build our MarkDown pages into pretty HTML pages.
- [GitHub.IO](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages): This is a free website hosting solution for GitHub housed documents.
- [MKDocs](https://www.mkdocs.org): MKDocs is used to convert the Markdown documentation into HTML formats. This allows for enhanced features in a more accessible format, along with themeing and styling not otherwise possible.
- DNS: Our old friend DNS. Its used to provide for a friendly URL to our site vs the github.io link. Totally optional.

## Getting started
You can use the steps below to create a basic documentation website. You are welcome to start with the content here, or produce your own from scratch.

### Github
1. Create an account on Github.com. I suggest a organizational account able to host the data for the site outside of any invidivual accounts.
2. Create a new repository.
3. (Here is where things get a bit more complicated) We need to create an 'Action'. An action is essentially automation that says 'Anytime we make a change to the repository created in step 2, rebuild and publish our website.
4. Create a DNS record. This is optional, but in 