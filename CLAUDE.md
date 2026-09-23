Plain HTML and CSS only: no build step, no framework, no JavaScript unless I ask.
Keep index.html at the repo root and use relative paths (style.css, never /style.css).
Keep the "bold name" design: the oversized name is the one bold move and everything else stays quiet, colors live in the :root variables, and every text color meets 4.5:1 contrast.
Make each change on its own branch and merge it through a pull request; never commit directly to main.
Do not edit DECISIONS.md or anything in verification/; those are mine to write.
