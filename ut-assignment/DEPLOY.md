# UTCS homepage copy

The `index.html` in this folder is the same full portfolio as the repository root `index.html`. It includes inline CSS and browser JavaScript for motion and a scroll indicator. The browser runs that JavaScript after Apache serves the file. There are no external assets or build steps.

To publish it, copy this folder's `index.html` to `/u/<your-UTCS-login>/public_html/index.html` on your UTCS account. Keep only one index file in `public_html`.

On the UTCS machine, ensure your home directory and `public_html` are searchable, and run:

```sh
chmod o+x ~/public_html
chmod o+r ~/public_html/index.html
```

Then visit `https://www.cs.utexas.edu/~<your-UTCS-login>/` from a browser outside the UT network and confirm the page loads. The assignment also asks for a note naming the LLM used and a PDF transcript of the interaction. Export this Codex conversation to PDF for that submission; the website source is not the transcript.

Source: https://www.cs.utexas.edu/facilities/documentation/web
