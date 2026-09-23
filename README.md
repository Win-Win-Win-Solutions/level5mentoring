# Level 5 Program Calendar

Client-facing calendar of Level 5 program sessions and events.

**Live:** https://win-win-win-solutions.github.io/level5-calendar/

## Updating

`index.html` is the whole site — a single static page, no build step.
Edit it and push; GitHub Pages redeploys within a minute or two.

Session times are stored in Pacific Time as `data-pt` attributes and
converted to the visitor's local timezone in the browser.

## Not in here

The internal ops calendar is a separate page with team-only notes
(conflicts, promise gaps, staff availability). It is not public and is
not part of this repo.
