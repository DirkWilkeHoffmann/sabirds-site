# sabirds.co.za

Publishes **SA Birds** at <https://sabirds.co.za>. The app itself lives in
[DirkWilkeHoffmann/sa-bird-flashcards](https://github.com/DirkWilkeHoffmann/sa-bird-flashcards); nothing is edited here.

Every 10 minutes (or when run by hand) the workflow checks whether the app's `main`, `dev` or `tips`
branch has changed and, if so, publishes them:

- `main` → https://sabirds.co.za/
- `dev`  → https://sabirds.co.za/dev/
- `tips` → https://sabirds.co.za/tips/

The old address, https://dirkwilkehoffmann.github.io/sa-bird-flashcards/, keeps running from the app's
own repository and moves each player here with their progress (see `app.js`, "The move to sabirds.co.za").
