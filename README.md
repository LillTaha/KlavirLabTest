# Mouse Freezing Demo

A tiny practice project for the Klavir Lab GitHub workshop.

`freezing.py` goes through a mouse's speed, second by second, and counts how
long the mouse was frozen (moving slower than a threshold). The speeds are made
up for practice, not real data.

## Installation

You only need Python 3. No extra packages are required.

## How to run

Open a terminal in this folder (in GitHub Desktop: **Repository › Open in Command Prompt** on Windows, or **Open in Terminal** on Mac) and type:

```
python freezing.py
```

On Mac you may need `python3 freezing.py`, and on Windows `py freezing.py`.

## What you should see

One line for each second, then a summary:

```
 0s   5.2 cm/s  #####    moving
 ...
 2s   0.3 cm/s           frozen
 ...
Mouse 1 was frozen for 10 of 20 seconds (50%).
```

## Try it yourself

1. Open `freezing.py` and change `SPEED_THRESHOLD = 1.0` to `0.5`. Save.
2. Run it again. The mouse is now frozen for 8 seconds (40%).
3. In GitHub Desktop, open the **Changes** tab to see the line you changed.
4. Write a short message, click **Commit to main**, then **Push origin**.
5. Refresh your fork on github.com. Your change is now in its history.

## Contact

Maintained by [name], Klavir Lab.
