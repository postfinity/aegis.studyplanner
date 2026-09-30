# Aegis — Study Planner

A desktop study planner with an editor-style minimal look. Plan each day in blocks, keep track of units and assignments, and watch your progress across the term and year.

**App version: 1.0.0** (download it from the Releases page)
**Prototype in this repository: v0.1.0-alpha**

> Built with heavy AI assistance as a side project.

---

## About this repository

This repository holds the **early alpha prototype** of Aegis (`study_planner_alpha.html`) and this page.

The full app, version 1.0.0, is shared as a Mac installer on the [Releases page](../../releases/latest). Its source code is not published here, so the prototype is much smaller than the app you download.

---

## Download the app

Get the latest installer from the [Releases page](../../releases/latest).

**Requirements**

- A Mac with an Apple chip (M1, M2, M3, M4 or later).

Not sure which Mac you have? Click the Apple menu, then **About This Mac**. If it says "Chip: Apple M...", you're good to go. If it says "Processor: Intel", this version won't run on your Mac.

## Install

1. Download the `.dmg` file from the latest release.
2. Open it and drag **Aegis** into your **Applications** folder.
3. Open the app from Launchpad or Spotlight.

### First launch

The app isn't signed with an Apple developer certificate, so macOS will probably block it the first time.

1. Try to open the app once.
2. Go to **System Settings**, then **Privacy & Security**.
3. Scroll down and click **Open Anyway** next to the message about Aegis.
4. Confirm, and enter your password if asked.

You only need to do this once. On some versions of macOS, right-clicking the app and choosing **Open** also works.

---

## What's inside the app

The app has three main tabs.

**Micro (daily)**
- A monthly calendar. Click any date to open that day.
- Each day is a list of timed blocks for study, practice, breaks and buffers, with start and end times, micro-goals, an energy toggle (high energy means active recall, mock exams, etc while low energy means revising notes, making notes, etc) and spaced repetition reminders (24 hours, 3 days, 7 days).
- Ribbons for things outside study, like a extracurriculars or just leisure.
- A built-in focus timer with a length you choose.
- Week totals per subject, shown like `Math.log(3h 10m);`.
- An A/B week timetable you can set up once.

**Meso (weekly)**
- A weekly priority.
- Term progress.
- Curriculum strand lists (Knowledge & Understanding, Inquiry & Skills).
- An assignment breaker that splits big tasks into checkpoints.
- A countdown to upcoming tests.
- A unit master list with progress bars for each subject.

**Macro (big picture)**
- A subject roster (core and elective).
- A term and holiday timeline for the year.
- Senior pathway targets and a semester grade log.
- A 30-day milestone list that also shows on the calendar.

## Your data

Everything you enter is stored **on your own computer**, inside the app. Nothing is uploaded anywhere, and there are no accounts.

Because of that, back up before you update or move to a new computer:

1. Open the **transfer data** button in the top corner.
2. Copy the export text and save it somewhere safe, such as a notes app.
3. To restore it, open **Transfer data** in the app, paste it into the Import box and apply it.

The **erase data** button next to it wipes everything after three confirmation steps. There is no undo, so back up first.

## Updating

There is no automatic updater. When a new version is released:

1. Back up your data using Transfer data.
2. Download the new `.dmg` from the [Releases page](../../releases/latest).
3. Open it and drag the app into **Applications**, choosing **Replace** when asked.

Your data should stay as it was.

---

## Try the alpha prototype

The prototype in this repository is a small, early version of the idea. It has day tabs (Mon to Sun), timed blocks with line numbers, a daily total, and a focus timer. It does not include the tabs, timetable, grades or other features of the full app.

1. Download `study_planner_alpha.html` from this repository.
2. Double-click it to open it in any web browser.

Your blocks are saved in that browser only.

## Credits

- Fonts in the app: [JetBrains Mono](https://www.jetbrains.com/lp/mono/) and [Source Code Pro](https://github.com/adobe-fonts/source-code-pro), both licensed under the SIL Open Font License 1.1 and embedded in the app.
- The desktop app is built with [Electron](https://www.electronjs.org/).

## Licence

The alpha prototype in this repository is released under the MIT licence. See the `LICENSE` file for details.

The Aegis app (version 1.0.0 and later) is free to download and use. Its source code is not published and is not covered by the MIT licence.

## Comments

Thank you for even visiting my profile and seeing this repo! I'm actively learning html, js and other languages so I can cut reliance on AI. If you spot any issues, have any suggestions, criticism, or would like to just give me advice, I'd happily take it!
