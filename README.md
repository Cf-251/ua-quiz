# How Ukrainian are you?

A 20-question quiz about Ukraine, made for Gro Community's Ukrainian afterwork in Växjö, October 2026.

Live at **https://cf-251.github.io/ua-quiz/** (GitHub Pages, branch `master`, repository root).

- `index.html` is the whole quiz: one file, no dependencies, no tracking, nothing stored except the light/dark choice on the viewer's own device.
- One question at a time. An answer locks when tapped and shows whether it was right, with the correct answer and a short explanation. Earlier answers can be viewed but not changed.
- The result screen shows the score in percent, the number of correct answers, a verdict line, confetti, a review of all answers, and a Start over button.
- Edit the `QUESTIONS` array in `index.html` to change questions, `TIERS` for the verdict lines. Push to `master` and the page updates within a minute.

Style note: "russia" and "russians" are written in lowercase on purpose.
