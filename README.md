# imcslab.github.io

Website of the Intelligent Mobility and Cybersecurity Lab. (IMCS Lab.),
Division of Computer Engineering, Hansung University.

Built with [Jekyll](https://jekyllrb.com) and deployed to GitHub Pages.

## Updating content from github.com (no tools needed)

Most updates are one edit to a YAML file in `_data/`. Open the file on GitHub,
click the pencil icon, edit, then click **Commit changes**. The site rebuilds
automatically in a minute or two. Each file starts with a copy-paste template
and instructions.

| To change | Edit this file |
| --- | --- |
| News items | `_data/news.yml` |
| Publications | `_data/publications.yml` |
| Research projects | `_data/projects.yml` |
| Student / alumni list | `_data/students.yml` |

Other content lives in the page files: `index.html` (home), `research.html`,
`members/professor.html`, `members/students.html`. Site-wide values — lab name,
address, email, menu structure — are in `_config.yml`.

YAML is indentation-sensitive: keep two spaces before `date:`, `title:` and so
on, exactly as in the existing entries. If a value contains a colon, wrap it in
double quotes.

## Structure

```
_config.yml           site settings, contact details, navigation menu
_data/*.yml           content you edit regularly (news, publications, ...)
_layouts/             default.html (shell), page.html (inner-page wrapper)
_includes/            header.html, footer.html
assets/css/style.css  all styling
assets/js/nav.js      mobile menu toggle
assets/uploads/       research figures
```

## Running locally

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Deployment

`.github/workflows/pages.yml` builds the site and deploys it on every push to
`master`. This requires **Settings → Pages → Build and deployment → Source** to
be set to **GitHub Actions**.
