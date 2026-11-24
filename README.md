# ravivh.com

The root of https://ravivh.com (GitHub user site of `ravivhi`, custom domain in `CNAME`).

- `index.html` — redirects to the Guessing Game at /guessingGame/.
- `.well-known/assetlinks.json` — Digital Asset Links for the Android apps (TWAs) that load
  ravivh.com: com.raviv.guessingGame, com.raviv.englishQuiz, com.raviv.alfi, com.raviv.ehadi.
  Must stay at the domain root. Removing an app's entry breaks that app's full-screen mode.

Every other `ravivhi` repo with GitHub Pages turned on is served at `ravivh.com/<repo>/`
by its own Pages workflow: guessingGame, englishQuiz, alfi, ehadi, butz.
Don't add folders here with those names: they would conflict with the repos' sites.
