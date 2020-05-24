# Charity Betting Platform

## Idea
- platform for people to register predictions and make bets

### 1 Minimal concept to start with:
- people who know each other register bets publicly
- platform stores names, amount, odds, content, expected due date and sends periodic reminders
- once bet is resolved losing party can pay via the app (to think: how do they get a donation receipt?)
- platform stores who won/lost and whether the debt was paid
- people can browse past bets

To think: who needs to have the app installed? who needs to have an account? Can we avoid forcing people to sign up?

### 2 Extend to public predictions
- people can make a prediction and propose odds even without a second person to bet with
- others can then challenge the prediction and they make a bet


Proposed App Structure

    My bets

        - Bet 1
        - Bet 2
        - ...

        Bet

            - Topic
            - Betting with
            - Settled? --> Paid?
            - Amount
            - Odds
            - Due date
            - Reminders

    My stats

        - number of bets won
        - number of bets lost
        - money donated
        - money earned for charity

    Leaderboard

        - most donated
        - most bets one
        - most money earned for charity

    Register new bet
        - Claim
        - exact win condition
        - With whom to bet? --> send invite link
        - Expected due date
        - periodicity of reminders
        - make content of bet private

### Flutter info

resources

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
