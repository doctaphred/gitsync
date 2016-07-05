# _* G I T S Y N C_

Commit and push your files automatically!

Disclaimer: this is probably a terrible idea.

## Installation (please don't)

- `brew install fswatch` [(or however you wanna get
  it)](https://github.com/emcrisostomo/fswatch)
- `cp gitsync somewhere/in/your/path/`

## Usage (seriously, just don't)

- TODON'T

## Reflections Upon First Use

This is *definitely* a terrible idea

I am scared to death of making typos

omg why would ANYBODY ever actually use this

If nothing else, at least it led me to discover [this gem of the
'90s](https://www.youtube.com/watch?v=byuPyhx5Ytg)

Is it cheating to reorder my thoughts, or post them out of order?

Welp, now I understand firsthand why Google Wave totally tanked.

I wonder how long until I get rate limited...

It's interesting to finally have exposed to me how nonlinear my edits tend to
be: I've had a half-finished sub-thought for a previous point in my clipboard
for a few commits now, because I have this instinct to keep my commits atomic.
Pretty sure that's not really relevant here, but the thought persists.

Gives a new perspective for that whole "nightly build" thing...

So the original idea behind this project was to reduce the friction between me
and my git remotes, in order to avoid the problems that come up when I let my
home directory configs get out of sync between machines. But at this point I
can say with *very* definite certainty that it is *not* the solution I am
looking for.

It might still be decent if all operations were performed on a dedicated
"_gitsync" branch, though.

    - In fact, for things like config files, totally: each machine could
      switch to the bleeding-edge _gitsync branch when desired, or hang
      out on master and wait for pull requests to get merged.
    - This would probably really help with stability, and encourage me to
      actually use branches and pull requests rather than just yolo'ing
      everything straight to master.

Also I have no idea how to actually delete stuff from git if I accidentally
drop some secret data in here while the tool is running :\
