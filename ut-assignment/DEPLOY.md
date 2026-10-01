# UTCS homepage copy

The full portfolio is `../index.html`. It is a single file with inline CSS and a small amount of browser JavaScript. The browser runs that JavaScript after Apache serves the file. The separate `index.html` in this folder is a simpler HTML/CSS version for the class assignment.

To publish the simple version, copy this folder's `index.html` to `/u/<your-UTCS-login>/public_html/index.html` on your UTCS account. If you prefer the full portfolio, copy the repository root `index.html` to that same destination instead. Keep only one index file in `public_html`.

On the UTCS machine, ensure your home directory and `public_html` are searchable, and run:

```sh
chmod o+x ~/public_html
chmod o+r ~/public_html/index.html
```

Then visit `https://www.cs.utexas.edu/~<your-UTCS-login>/` from a browser outside the UT network and confirm the page loads. The assignment also asks for a note naming the LLM used and a PDF transcript of the interaction. Export this Codex conversation to PDF for that submission; the website source is not the transcript.

Source: https://www.cs.utexas.edu/facilities/documentation/web
