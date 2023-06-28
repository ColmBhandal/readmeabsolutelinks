# readmeabsolutelinks

A repo to test absolute links from README files at different levels of nesting. The trick is to use `/../../` before any links (leading slash important). This escapes GitHub's usual `blob/BRANCH` entries in the URL, and the browser then resolves them to be relative to the repo URL.

Notes:
 - This has only been tested in Google Chrome
 - This depends on GitHub keeping the same URL structure

Example links:

 - [Link to actions](/../../actions)
 - [Link to repo](/../../)

Inspired by [SO question](https://stackoverflow.com/questions/40196198/automatic-link-to-github-pages-url-from-readme-md).
