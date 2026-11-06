---
name: short-prompt
description: Turn a person's short, plain-language asks (10-25 words, often voice-dictated, often Hinglish or another mixed language, full of "this", "same as before", "the yellow thing", "make it pop") into the full brief a 100-word prompt would have spelled out, then get on with the work. Apply automatically at the start of every request from them, before any job and before loading the job's own skill. Covers videos, reels, thumbnails, posts, websites, handoffs, outreach, research, and revisions to work already made. Fill the gaps from their saved rules, design systems, past jobs and their personal word list instead of asking them to explain. Ask at most one plain question, and only when a wrong guess would waste a render or can't be undone. Also trigger on "you know what I mean", "same as last time", "like before", "do the usual", "just make it", "go on", a one-line voice note, or any ask that names a thing without describing it.
---

# Short prompt → full brief

The person writes the way they talk: short, plain and often dictated. Someone else might
write 100 words; they write 20. **That is enough, because the other 80 are already written
down** in their memory files, design systems, saved rules and past jobs. Your job is to
find those 80 words yourself. Don't send them back to write them.

A short prompt is not a vague prompt. It is a prompt that trusts you to remember.

## The read (do it quietly, in seconds, before anything else)

1. **Hear the whole message, end to end.** Voice notes correct themselves. A trailing *"yeah
   it's fine / that's fine / leave it / actually no"* cancels the request just before it.
   Dictation also mishears names: a tool name comes out as a near-homophone, the studio's
   name gets respelled, "wish" turns out to be whoosh. The sounds-like list is in
   `references/word-list.md`.

2. **Translate their words.** Look up every everyday phrase in `references/word-list.md`.
   For example, "zoom in" may mean a slow push-in, "the yellow thing" may be a saved
   thumbnail theme, and "fast-forward a bit" may mean a later in-point. Their meaning
   beats the textbook meaning, every time.

3. **Find "this / that / the video / same as before" by looking.** Work down this list and
   open the first match:
   the file they attached → the newest file in their downloads or desktop → the job already
   open in this session → the newest folder in their projects folder → the matching
   project notes.
   Then **probe it**, because a file called "recording of X" may not contain X. If they give
   a timecode or name a look ("halo", "stamp"), pull the frames or a real reference before
   building. Your mental picture of their word is the thing most likely to be wrong.

4. **Name the job and load its kit.** The routing table in `references/fill-ins.md` lists the
   skill or command to load for each kind of job. It also lists the defaults that fill the
   blanks: size, folder, client rules, captions, logo, music and look. Load the kit; the
   job's skill already knows the details, so don't re-derive them here.

5. **Say it back in one line, then start.** See below.

## Saying it back

Before real work starts (a render, a build, a generation), give one line in plain words:

> **Reading this as:** a 9:16 reel for the snack brand from the clip you just sent
> (`IMG_4412.MOV`), with your words as captions at the bottom, a slow push-in when you
> show the pack, and a soft music bed under your voice. Starting now.

- It's a statement they can interrupt, **not a question.** Don't wait for a reply; start.
- Use their words. If you need a film or design term, put their word beside it: "slow
  push-in (your 'zoom in')".
- Name the 2-3 choices you filled in yourself, because those are the ones they may want
  different. Skip the things that are always true, like the logo and safe zones.
- For a tiny edit, skip the say-back. Make the change, then say what changed and **what
  you deliberately left alone** ("the rise from the bottom I didn't touch, you said
  that's fine").

## When to ask, which is rarely

Ask only when one of these is true:

- **Nothing to work on can be found** after you've looked (no footage, file or link).
- **Two readings are both fair and lead to very different builds**, so a wrong guess costs
  a render or a day. If both readings are cheap, pick the likelier one, say so in the
  say-back, and go.
- **The step sends, posts, pays, deletes or goes public.** Always confirm these anyway.

When you ask:
- Ask **one** question, in their words, short.
- If you're asking *which file or video*, name your best candidate and why, so they can
  just say "yes": "Is it the birthday-cake one? That's the only reel where you say 'open
  the packet'." Search first: grep job transcripts and scripts for their words, and check
  contact sheets.
- If you're asking how *their ideas* map onto a framework, use the open form ("which line
  goes with which tier?"), never "I mapped it like this, OK?"
- Don't use a multiple-choice popup and don't send a list of four questions.
- Keep working on everything that doesn't depend on the answer.

**Never ask** about anything with a default: size, aspect, fonts, where to save, caption
style, music level, logo, or which browser profile to use. Those are in
`references/fill-ins.md` and their memory.

## Filling gaps without overfilling

A short prompt means "use my usual way". It does not mean "add more". Fill the blanks
with **their** defaults, not your own ideas:

- Don't add hooks, end cards, extra beats or effects they didn't ask for. A hook only goes
  in when there's a withheld payoff.
- Read an unclear revision as the **smallest change** to what they already accepted.
- If the person has said they *want* suggestions of a certain kind (for example, visuals
  for what they're saying in a talking video), that counts as their default, not an extra.
- Don't lecture and don't explain the plan at length. Build what was asked.

## Every correction makes the next prompt shorter

When they say "no, I meant…", fix it first. Then **write the phrase into
`references/word-list.md`** (their words → what they meant → job and date). If it's a
standing rule, also save it as a memory. The word list is how this skill learns the
person. Each entry is one less thing they'll ever have to explain.

When a new shortcut shows up and works without a correction (they say something new and
your reading was right), add it too, marked "inferred, worked".

## Quick self-check before you start

- [ ] Read the whole message, including any trailing "it's fine"?
- [ ] Looked up their words and resolved "this/that" by opening the actual file?
- [ ] Loaded the job's skill and its defaults (`references/fill-ins.md`)?
- [ ] Gave a one-line plain say-back with the 2-3 filled-in choices?
- [ ] Asked nothing that has a default, and at most one question overall?
