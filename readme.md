# Safari Column Bug

When there are 2+ CSS columns and a child element
has an overflow, space is preserved for the child element
but it is not painted.

Minimal test case in `index.html` or see `demo.mov` for a repro.

Does not happen in Chrome.
