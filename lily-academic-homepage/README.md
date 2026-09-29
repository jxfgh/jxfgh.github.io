# Xiaofang (Lily) Jiang — academic homepage

This personal site is based on the MIT-licensed [academic-homepage Jekyll template](https://github.com/luost26/academic-homepage). The template attribution remains in the site footer and its original license is included here.

## Publish with GitHub Pages

1. On GitHub, create a repository from the template using the **Use this template** button.
2. Name the personal website repository `<your-github-username>.github.io`.
3. Add the files in this folder to the new repository. Do not add the parent ChatGPT project folder or its `sources/` directory.
4. In the repository, open **Settings → Pages** and enable publishing from the `main` branch and the root folder.
5. The personal site will be served at `https://<your-github-username>.github.io` after GitHub Pages finishes publishing.

For a personal `username.github.io` site, `_config.yml` uses an empty `baseurl`. If this site is published as a project site under a different repository name, set `baseurl` to `/<repository-name>` before publishing.

## Update the content

- `_data/profile.yml` contains the name, affiliations, education, experience, awards, and contact details.
- `_includes/widgets/research_teaching_card.html` contains the homepage research and teaching copy.
- `_publications/` contains one Markdown file per publication. Set `selected: true` for items to feature on the homepage.
- `_data/navigation.yml` controls the navigation links.

The source repository is available at <https://github.com/luost26/academic-homepage>.
