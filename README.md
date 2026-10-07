# StudyBeats

A small, fun side project built with **HTML and CSS only** (no JavaScript). StudyBeats pairs your mood with a study sound and a tip, and has a built-in 5-minute break timer.

## What it does

- Pick a mood (Focused, Tired, Stressed, Happy, A bit down) and get a suggested style of music, a short study tip, and quick search links for Spotify and YouTube
- The animated background changes colour with your mood
- A break timer: tap "Start 5-minute break" and a progress bar fills over five minutes, then shows a "Break's over" message. Tap again to reset

## How it works without JavaScript

This was a chance to see how far CSS alone can go:

- Hidden radio buttons remember which mood is selected
- The CSS general sibling selector (`~`) shows the matching panel and background for the checked mood
- A hidden checkbox starts the break timer: when it is checked, a 300 second CSS animation fills the bar
- Labels are styled as buttons, and keyboard focus styles are included so it can be used without a mouse

## Running it

No setup needed. Download the files and open `index.html` in any modern browser.

## Files

```
studybeats/
├── index.html
├── style.css
└── README.md
```

## Notes

The Spotify and YouTube buttons open search results rather than specific playlists, so the suggestions always stay current.
