# Glossary

These are the four terms Pocket Timer uses most.

## Session

A session is a block of focused work. Run `pocket start` to begin one. It lasts `session_minutes = 25` by default, and you can set 5 to 120. See [Session length](configuration.md#session-length).

## Break

A break is a short rest between sessions. Run `pocket break` for a 5-minute break, or change it with `break_minutes = 5`. Breaks never count toward your daily goal.

## Daily goal

Your daily goal is how many sessions make a full day. It is `daily_goal = 8` by default, and `pocket today` shows your progress. See [Daily goal](configuration.md#daily-goal).

## History

Your history is the record of your sessions and breaks. It lives in `~/.pocket/history.jsonl`, with one line per session or break. Delete the file to start over. See [Where is my history stored?](faq.md#where-is-my-history-stored).

Back to [the index](index.md).
