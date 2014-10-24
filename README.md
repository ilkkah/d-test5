d-test5
=======

An app to reproduce a Derby bug.

How to reproduce:

- Open two browsers, navigate to the app
- Click through home and home2 a couple of times, navigate into the same page with both browsers
- Add some data
- -> duplicates should appear in the other browser (that was waiting for data).
- If duplicated don't seem to appear, click to another page (home2 -> home) with both browsers and try again.
