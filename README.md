# Short Prompt

An agent skill that turns short, voice-dictated asks into full briefs. The person says twenty words, often in Hinglish, often full of "this", "same as before" and "the yellow thing", and the agent fills in the other eighty from what is already written down: a personal word list, saved defaults, and the files in front of it. It asks at most one question, says its reading back in one line, and starts. It is plain Markdown and works in Claude Code or any agent that loads skills.

By Anisha Dogra, co-founder of [RAAY Creative](https://raaycreative.com). This came out of daily work with an agent on reels, covers and websites, where most asks are dictated in a few seconds between other things, and every clarifying question cost more than the answer was worth. Corrections and disagreements are welcome. [Open an issue](../../issues/new) before opening a pull request.

## The problem

A short prompt is not a vague prompt. It is a prompt that trusts the listener to remember.

Agents are trained to treat short as vague. Ask for "a reel from the video I just sent, zoom in where I show the pack" and a careful agent comes back with five questions: which video, what aspect ratio, which fonts, where to save it, what kind of zoom. Every one of those has an answer already. The video is the newest file in Downloads. The aspect is the same as the last forty reels. "Zoom in" means a slow push-in, because it has meant that every time.

Dictation makes it worse. Voice notes correct themselves halfway through: "make the logo bigger, actually no, the logo is fine". Names come out as near-homophones. Hinglish words get transcribed as English words that mean something else. An agent that reads the transcript literally will do the thing that was cancelled and go looking for a tool that does not exist.

The cost is not the questions. It is that the person learns to write long prompts to avoid them, and the shortcut that made working with an agent fast is gone.

## The rules that matter most

**Look before you ask.** "This", "that" and "same as before" are found by opening files, not by asking. Attached file first, then the newest download, then the job already open, then the newest project folder. Then probe it, because a file called "recording of X" may not contain X.

**Hear the whole message.** A trailing "it's fine" or "actually no" cancels the request just before it. Say back what you deliberately left alone.

**Say it back in one line, then start.** A statement the person can interrupt, not a question to wait on. Name the two or three choices you filled in yourself, in their words, with the technical term beside them.

**Ask at most one question, and only when a wrong guess is expensive.** Nothing found to work on, two fair readings that lead to very different builds, or a step that sends, posts, pays or deletes. Never about anything that has a default.

**Every correction goes into the word list.** "No, I meant…" becomes a row. The list is how the skill learns one person, and each row is one less thing they have to explain again.

## What is in here

| | |
|---|---|
| **[SKILL.md](SKILL.md)** | The skill itself: the five-step read, the say-back, when to ask, and how not to overfill. |
| **[references/word-list.template.md](references/word-list.template.md)** | The word-list format with illustrative rows: dictation mishears, codenames for looks, revision words, camera terms, action phrases and a log. Copy it to `word-list.md` and make it yours. |
| **[references/fill-ins.md](references/fill-ins.md)** | A routing table from rough asks to the skill to load, who the work is probably for, and the blanks that should never need asking about. Placeholders to replace with your own. |
| **[evals/evals.json](evals/evals.json)** | Four sample prompts with the reading each one should produce. |

## How to use it

Copy the folder into your agent's skills directory (for Claude Code, `.claude/skills/short-prompt/`). Copy `references/word-list.template.md` to `references/word-list.md`, delete the example rows that do not fit, and fill `references/fill-ins.md` with your own skills, folders and defaults. Then start talking to it the way you actually talk.

The list starts thin and grows. The first week it gets corrected often; that is the point, because each correction is written down.

## A note on the word list

The word list in this repo is a template. The real one is personal: it holds client names, page handles, folder paths and the particular ways one person's dictation goes wrong, and it is only useful to the person it was built from. Yours will look nothing like the examples, and it should not.
