# TeX Golf Language Support

VS Code language support for TeX, as used in code golfing on https://code.golf.
Highlighting is careful for `\loop...\repeat`, `\newcount`, and other cases
that don't show up often outside of code golf.

Extremely WIP.

Planned:

- Improved highlighting. For example, different colors for `\newcount`'d variables (requires LSP).
- Extra allowances for some constructs (such as `\usegolf`) provided by
  my [TeX autogolfer](https://github.com/jared-hughes/tex-autogolfer) tool.
- Show the compiled TeX next to each line.
