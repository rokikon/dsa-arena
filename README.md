# dsa-arena

The essence of the platform is speedrunning. Wins the fastest. We have timers in every mode.
This is a web application with NextJS client and BunJS backend.
We don't use auto-validation by tests, so don't add e2e tests or unit tests at the point of MVP.
Style - dark souls and elden ring speedrunning. Dark gothic theme. We need to integrate cinder flame from dark souls into design. Brainstorm style in separate discussion.
We have achievement system.

Some of terminology:
"kill-list" - whenever player caught cheated, they are banned forever and their nickname is added to the list of banned people.
"TBD" - we should discuss this as a separate topic. Ask me clarifying questions and come up with own ideas with pros and cons.

We have multiple modes (open for suggestions):
1. Solo Speedrun. Has three sub modes each with own public leaderboard.
   1.1 Daily - 4 random problems connected by topic chosen randomly each day.
   1.2 Portal - Predefined lists of problems connected by topic. Finishing them adds achievement to players profile. There should portals for ultra beginners and for hard core DSA experts.
   1.3 Tower - Basically all problems randomly sorted by complexity the more person can solve in one session the higher ranking on board. Session should be timebound 2 hours.
2. Duel mode. Players can challenge each other to solve one problem. We can use two layers validation client side (pre-submit) and server side (submit) with hidden cases. If submit has a winner duel ends and dialog with a winner is shown.

Maybe we can think about mode useful for begginers?
