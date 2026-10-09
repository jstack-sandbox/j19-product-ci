<!-- jstack's pull request template (§14). Products use the copy their pinned jstack release carries. Tier comes from CODEOWNERS. no-mistakes appends risk, testing and pipeline evidence below. -->

# For humans
<!-- For the owner, reading on a phone, who should not need to open the code. One short sentence per line, everyday words a non-coder follows. No file paths, code names, check or gate numbers, rule or decision IDs, skill names, or words like contract, lock, stub or assertion; a term that cannot be avoided is explained in the same sentence. Rule IDs go only on the Look at line. Placeholders left here are requested changes. -->
**The problem:** <what was wrong or missing, in everyday terms>

**The fix:** <what this pull request does about it, as an outcome, not a mechanism>

**Picture:** <one image drawn for this change, when it alters how parts connect, flow or are laid out; a page rendered to an image, never an image generator, in the same everyday words, with its source page in a collapsed block under it. When the change has no shape to draw, write "none:" and a reason instead.>

**Why it matters:** <what goes wrong without it, or what it makes possible, and for whom>

**What it does:** <one line per behaviour this pull request adds, changes or removes, grouped under short italic headings when there are several: "When X, it does Y" or "It refuses X, and says why". Every test it adds or changes, and every behaviour its code changes, is one line here, so this list is the whole change in plain words. A docs-only change lists the rules it adds or changes the same way.>

**Checks:** <"all green", or which check is red and why that is expected, e.g. "tests are red on purpose: they were written before the code that will pass them">

**What could go wrong:** <what breaks, or what gets frozen, if a line above is wrong, and which line most needs a second look>

**What we need from you:** <the decision or action, as numbered steps, e.g. "1. say if any line under What it does is wrong 2. approve, which freezes the tests">

**Look at:** <the one thing a reviewer should open — a screen, a rule ID, the preview, or "the What it does list">

# Change request
**Outcome:** <one line, matches the issue>

**Rules** — IDs this change implements or changes, e.g. LOAN-014 (planned → active)

**Notes** — examples or failure cases specific to this change that are not already in the rules

**Open questions** (the PR is labelled `needs-answers` while any box is unchecked)
- [ ] …

# Shapes
<!-- test-first: each record, command, endpoint, error, internal function and port the tests call, one plain line each — fields, what it takes, returns and when it refuses. Approved with the tests; locked after. "None" when no shapes or signatures change. -->
- …

# Agent decisions
<!-- test-first: each low-stakes choice the agent made instead of asking — the choice, the alternative, one line of why — and any planned rule wording brought in line with an owner decision. The lock approval accepts or overturns each. "None" when there are none. -->
- …

# Owner answers
<!-- Each owner-level question the session asked the owner while working (§13.9): the question, its category, the recommendation, the answer, in prose. Never written into the facts file, and never an answer to an open question. Delete this heading when nothing was asked. -->
- …

# Tests
- Test names and the rule examples they cite: …
- Journeys (user-visible changes): name + steps …

# Docs
- [ ] Docs updated in this PR (pages: …)
- [ ] No behaviour change

# What did this delete?
<what was removed, or "Nothing, because …">

## Lessons (optional — written to memory after merge)
<what surprised us, dead ends>
