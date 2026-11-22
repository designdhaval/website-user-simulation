# Website user simulation — a free Claude skill

Claude visits your website as different kinds of people, uses it for real in Chrome, and tells you where they got stuck.

I made this for my own portfolio. Claude played a recruiter with 60 seconds, a junior designer on a phone and a keyboard-only visitor, and it found five problems, including a mobile menu that wouldn't close.

Watch the video: DesignLift on YouTube

## What it does
- Acts as five visitors (change them to match your users)
- Gives each one 2–3 real tasks: find the best work, find a way to get in touch, go deep and come back
- Tries edge cases: small screens, a wrong link, the back button, a form with a bad email
- Never submits a real form, never enters real details
- Reports the top fixes first, then what each visitor struggled with, then what already works

## How to use it
**Claude (claude.ai or the desktop app):** click the green **Code** button above, then **Download ZIP**. Add that zip under Skills in Claude's settings. Then ask: "Simulate users on yoursite.com".

**Claude Code:** copy `SKILL.md` into `.claude/skills/website-user-simulation/` in your project (or `~/.claude/skills/website-user-simulation/` for all projects).

It needs a browser tool, such as Claude in Chrome.

## Be honest about what it is
It's a fast first pass. It finds the obvious friction before a recruiter or customer does. It doesn't replace testing with real people.

## Credit
Made by Dhaval Shah for DesignLift. Free to use and change.
