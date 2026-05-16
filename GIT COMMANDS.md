## Daily essentials

**Commit-and-sync**  
This is the king.

What it does:

1. Saves a snapshot of changes
2. Pulls any remote changes
3. Pushes your new snapshot

Think: _save point + upload + synchronize_

Use it after a study session, a deep writing session, or before closing Obsidian.

If automatic commit-and-sync is enabled every X minutes, even better.

---

**Commit-and-sync with specific message**

Use meaningful messages occasionally:

- "Added finance lecture notes"
- "Expanded philosophy ZK links"
- "Restructured coding concepts"

Months later you'll thank past-you.

Bad:

> update stuff

Good:

> Added machine learning concept map

Git history becomes a timeline of thought.

---

**Open history view**

This may become your anxiety killer.

If your heart ever drops:

> Wait… where did that note go?

Open history.

You can literally browse previous versions.

For a Zettelkasten this is gold.

---

**Open diff view**

Shows exactly what changed.

Added line? Deleted paragraph? Accidentally erased half a note while tired at 1:14am?

Diff exposes it.

Like footprints in fresh snow.

---

## Protection commands

**Push**

Sends your local snapshots to GitHub/remote.

Useful if auto-sync isn't running.

Think:

Local → cloud

---

**Pull**

Downloads latest remote version.

Useful if:

- using multiple devices
- editing on laptop then desktop

Think:

Cloud → local

---

**List changed files**

Quietly underrated.

Shows:

> What have I changed today?

Very useful before committing.

---

## Commands to touch carefully

**Discard all changes**

This one has dragon energy.

It means:

> Delete every uncommitted modification.

No ceremony. No poetry. Just annihilation.

Do not casually press this.

---

**Delete repository**

Absolutely not.

This is the digital equivalent of seeing a red button under glass labeled:

> FOR THE LOVE OF ALL THINGS DO NOT

---

## Probably unnecessary for now

**Create new branch**

Software developers use branches for experimentation.

You _might_ use it if doing a huge Zettelkasten redesign:

Main vault:

- normal notes

Experimental branch:

- massive restructuring

But for one-person note systems? Usually overkill.

---

**Stage current file / Unstage current file**

Advanced but occasionally useful.

Staging says:

> Commit this note, but not the others.

Most people with personal knowledge systems barely touch this.

---

One more thing—because there is a subtle misunderstanding I want to remove:

You said:

> "I just made a backup using Obsidian Git"

A Git _commit_ isn't automatically a fully protected backup.

Protection stack:

Vault files  
↓  
Git commits (history/time machine)  
↓  
Push to remote GitHub repository  
↓  
Google Drive sync  
↓  
Optional external drive backup

The important question now: