# Spot the Stall

An interactive practice game for **ADHD and AI: A Different Way to Start Any Task**, Module 1, Lesson 1.

Learners practice identifying a task initiation stall in three rounds:

1. **Stall or not a stall?** Six short scenes, shown in random order.
2. **Tap the moment, then name the pattern.** Seven short stories.
3. **My stall snapshot.** Learners pick the patterns that have shown up for them and get a card they can keep.

## How it works

The whole game is one file, `index.html`. It's a static site with no server and no database.

- Nothing a learner chooses is sent anywhere.
- The Round 3 snapshot is remembered only in the learner's own browser, so a "See my last snapshot" button appears on the start screen on their next visit.
- Learners keep the card by using **Save as image** (downloads a PNG), **Print** (prints only the card), or **Copy as text**.

## Hosting on GitHub Pages

1. In the repository, go to **Settings > Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose the `main` branch and the `/ (root)` folder, then select **Save**.
4. After a minute or two, the game is live at https://adhd-and-ai.github.io/spot_the_stall/.

## Updating the game

Edit `index.html` and commit the change to `main`. GitHub Pages republishes it automatically, usually within a few minutes. The link stays the same.
