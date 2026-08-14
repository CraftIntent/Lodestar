# Lodestar

**An open, mastery-based homeschool engine with the teacher in the loop — built to make itself unnecessary.**

> **AI is the tool. The adult is the teacher. The child is the future.**

---

Lodestar turns any AI project folder into a mastery-based homeschool tutor. A parent fills in one profile; Lodestar generates lessons the parent delivers aloud, tracks each skill by evidence rather than by calendar, and flags gaps and forgotten material before they compound. Every lesson answers to a Student's Bill of Rights. The teacher stays in the loop; mastery stays at the gate.

It runs today inside a Claude Project — no code, no accounts, no cost beyond an AI subscription. A standalone native app is on the roadmap.

## Why this exists

Three commitments hold the whole design together. They are not slogans; each one is a rule the system obeys.

**AI is the tool.** The AI drafts lessons and keeps the record. It never stands in for a person. Software can generate and drill; it does not teach. When a system hands a child to a screen and calls it instruction, it has confused the tool for the teacher — Lodestar refuses that trade.

**The adult is the teacher.** Every lesson is written for a human to deliver aloud, in their own voice, anchored to the life the child actually lives. The adult explains the *why*, reads the child in real time, and judges whether something was truly learned. That judgment is the signal the whole system turns on. The teacher is in the loop, not at the end of it.

**The child is the future.** The point is not a well-managed child; it is a child who will not need managing. Lodestar measures its own success by how fast its scaffolding can be removed — by the day the learner can direct their own deep work and teach themselves anything. A tool built to make itself unnecessary is the only honest kind.

## The Student's Bill of Rights

Every lesson Lodestar builds, and every progress call it makes, answers to these. They are stated as rights because they define what the system owes the child, not what the child must earn.

1. **Progress by mastery, not by calendar.** Advance only when the material is genuinely learned — never because time passed or a birthday came.
2. **Work at their true level, without shame.** Being "ahead" or "behind" a grade is information, not a verdict.
3. **Be met at their actual level in each subject.** Advanced in reading and still building in math on the same day is normal — each subject on its own.
4. **Never advance with gaps.** Reading and math compound; a skipped foundation becomes a permanent hole. Don't build on a cracked footing.
5. **Never be bored.** If they already know it, don't drill it. Boredom is a signal to move on, not a discipline problem in the child.
6. **Learn from a human, not a screen.** The adult teaches; software only ever drills. Every lesson carries the *why*, not just the *what*.
7. **Be given the focus and motivation they can't yet supply alone.** Scaffold attention and momentum; don't assume the child arrives with them.
8. **Fail safely and try again.** Unlimited attempts, no penalty. A miss reroutes the lesson — it never becomes a mark on a record.
9. **Work in the zone just past easy.** Hard enough to grow, reachable enough to succeed — never trivial, never crushing.
10. **Grow into someone who can direct their own deep work.** The goal isn't a well-managed child; it's a learner who no longer needs the system. That capacity — not any single lesson — is the point.

## How it works

The whole system is a short loop:

1. **Set up once.** Fill in the student profile and paste it into your AI project's instructions.
2. **Request a lesson** in plain words — *"a lesson on bees,"* *"fractions using tonight's pizza."*
3. **Deliver it aloud,** screen-free. Do the activity, ask the questions.
4. **Say how it went** in your own words. Lodestar updates the skill list from what the child actually did.
5. **Check progress** every week or two. Lodestar flags weak subjects, stalled skills, and anything taught but never revisited — then recommends what's next.

A skill is only marked *Mastered* when the child uses it again in a *later* lesson, never the same day. Real learning survives a gap — so retention is built into the definition, not assumed.

## What's in this repo

| File | What it is |
|---|---|
| `PARENT_INSTRUCTIONS.md` | Plain setup-and-use guide for the adult. Start here. |
| `CLAUDE_PROJECT_INSTRUCTIONS.md` | The AI's instructions, with fill-in fields. Paste into your project's custom instructions. |
| `README.md` | This file. |

## Quick start

1. Create a new AI project (Claude Projects works today).
2. Open `CLAUDE_PROJECT_INSTRUCTIONS.md`, fill in every `[bracket]` about your student, and paste it into the project's **Custom Instructions**.
3. Read `PARENT_INSTRUCTIONS.md` once.
4. Ask for your first lesson.

## Roadmap

- Standalone native app so parents don't need to manage a project folder by hand.
- Persistent skill tracking that survives across sessions without copy-paste.
- Optional alignment to national skill frameworks (Common Core, NGSS) for coverage checks and reporting.

## Contributing

Contributions are welcome — the point is for this to grow. Before your first pull request is merged, you'll be asked to sign a Contributor License Agreement (`CLA.md`). The CLA lets your work ship both in the open-source project and in the future native app; without it we couldn't accept the contribution. See `CONTRIBUTING.md` for the workflow.

## License

Lodestar is released under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. You may use, study, modify, and share it — including for hosted and network use — provided your modifications are made available under the same license. The AGPL's network clause is deliberate: run a changed version as a service, and you owe your users the source.

The project's copyright holder additionally offers Lodestar under a separate commercial license (this is what the CLA preserves), which is how the standalone native app will be built without opening its full source. The community version stays AGPL, always.

*Not legal advice. If you plan to build on or redistribute Lodestar commercially, read the license.*

---

*Lodestar — the star you steer by. The teacher stays in the loop; mastery stays at the gate; the child grows past the need for either.*
