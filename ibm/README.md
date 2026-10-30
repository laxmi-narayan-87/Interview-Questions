# IBM Assessment Practice Lab

## Overview

This folder contains a browser-based practice tracker for the IBM assessment question set.

## Webpage

- **Practice tracker:** [IBM Assessment Practice Lab](./IBM_Assessment_Practice_Lab.html)

Open the HTML file in a modern browser (Chrome, Edge, or Firefox). It is self-contained and does not require a backend or installation.

## What it includes

- 100 LeetCode problems from the supplied IBM assessment dataset.
- Search by problem title and topic.
- Filters for difficulty and practice status.
- Sorting by frequency, acceptance rate, title, and difficulty.
- Per-problem practice logging for status, attempts, time spent, confidence, and notes.
- Progress summary for solved problems, revision items, and high-frequency questions.
- Browser-local progress persistence using `localStorage`.

## Data notes

The problem list and frequency/acceptance values come from the dataset supplied for this tracker. Frequency is a source metric and should not be interpreted as a guarantee that a problem will appear in a future IBM assessment.

## Usage

1. Open `IBM_Assessment_Practice_Lab.html`.
2. Filter or search the question bank.
3. Open a problem through its LeetCode link.
4. Update its status or use **Log practice** to record an attempt.
5. Reopen the tracker in the same browser profile to continue; progress is stored locally in that browser.

## Limitations

- Progress is stored in the current browser's local storage; it is not synchronized across devices or browsers.
- Clearing browser site data may remove saved progress.
- The tracker does not submit solutions to LeetCode or verify answers automatically.
