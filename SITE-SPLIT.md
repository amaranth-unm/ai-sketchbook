# AI Sketchbook / AI Workbench split

## Source roots

- This repository: **AI Sketchbook**, for teaching and course-policy sketches, published at `/ai-sketchbook/`.
- `/Users/fwgibbs/Dropbox/websites/ai-workbench/`: complete standalone **AI Workbench** source, for research experiments, intended for `/ai-workbench/`.

AI Workbench now lives beside AI Sketchbook in the websites folder. It is ready to become a separate repository. There is no nested second site in AI Sketchbook.

Seven research sketches, their template, images, and PDFs were copied before replacing the teaching site's old research pages with redirects. One existing research link was corrected from a Markdown source path to its published HTML path. Teaching/policy cross-links received the same repair. The two sites link to one another. Course-policy content remains with teaching. Old research image/PDF copies are retained in AI Sketchbook so existing direct links keep working.

## Preview both sites

From `ai-sketchbook`:

```sh
bundle exec jekyll serve --port 4003
```

From `../ai-workbench`:

```sh
bundle exec jekyll serve --port 4004
```

Open `http://localhost:4003/ai-sketchbook/` and `http://localhost:4004/ai-workbench/`. Cross-site navigation and redirects use the intended production URLs, so those links are meaningful once AI Workbench is published.

## Publication order

1. Create `amaranth-unm/ai-workbench` on GitHub for the sibling source folder.
2. Publish AI Workbench using the same GitHub Pages/custom-domain arrangement as AI Sketchbook. Confirm `/ai-workbench/`, the seven `/research/*.html` pages, their images, tags, search, and PDFs work.
3. Publish AI Sketchbook's teaching-focused navigation and old research redirects.

Neither repository has been pushed or published as part of this local split. Publishing AI Workbench first avoids sending existing research links to a site that is not available yet.

## Validation

Both sites build successfully with installed Jekyll dependencies. Validation disabled network-dependent GitHub metadata only, since GitHub is unavailable from the sandbox. All built internal page, image, stylesheet, script, and download links resolve. Search contains teaching/policy content in Sketchbook and research content in Workbench. All seven research redirects point to the intended Workbench destinations.
