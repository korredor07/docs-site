# First 5 minutes

This guide walks you through your first session, step by step. It assumes Pocket Timer is already installed. Pocket Timer needs no internet connection.

## Step 1: Start a session

Run `pocket start` to begin a 25-minute session. Pocket Timer counts down in the terminal and rings when the session ends.

## Step 2: Take a break

Run `pocket break` for a 5-minute break. Breaks never count toward your [daily goal](configuration.md#daily-goal).

## Step 3: Check your day

Run `pocket today` to list today's sessions and breaks. Your history is stored in `~/.pocket/history.jsonl`. See the [FAQ](faq.md#where-is-my-history-stored) for details.

## Step 4: Tune your settings (optional)

Pocket Timer reads `~/.pocket.toml` when it starts. Every key is optional. For example:

- `session_minutes = 25` sets the [session length](configuration.md#session-length).
- `sound = "bell"` picks the [sound](configuration.md#sounds) at the end of a session.
- `daily_goal = 8` sets your [daily goal](configuration.md#daily-goal).

You can also change the break length with `break_minutes = 5`. See the [FAQ](faq.md#can-i-change-the-length-of-a-break).

## Next steps

Read [Getting started](getting-started.md) for the same commands in short form, or go back to [the index](index.md).
