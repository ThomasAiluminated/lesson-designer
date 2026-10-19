# Lesson Designer

**A Claude skill that designs lessons that start from the learning objective and end with a check for understanding.**

🇧🇪 [Nederlandstalige versie](README.md) · 📄 [Examples](examples/)

Give the topic, the class and the lesson length, and get a lesson plan with realistic timing: an activating start, explicit instruction with a worked example, guided and independent practice, differentiation and an exit check.

It works in English, Dutch and French: it replies in the language you write in.

## What the skill does

- **Designs backwards from the objective**, rewritten as an observable objective with a learner-facing success criterion.
- **Follows a proven lesson rhythm:** activate → explicit instruction with a worked example → guided practice with a whole-class check → independent practice → exit check.
- **Names the typical misconception** and how to address it.
- **Practical differentiation:** a support and a challenge option per practice phase.
- **Timings that add up** exactly to the lesson length.

## What you get

1. **Objective and success criteria**
2. **Lesson plan table**: time, phase, teacher, learners, materials
3. **Worked example and misconception**
4. **Differentiation**
5. **Exit check** with answers
6. **Next lesson** based on the exit check

See [examples/](examples/) for a full input and output.

## Who it's for

Teachers, lecturers and trainers who want a well-designed lesson plan quickly, from primary school to corporate training.

This skill is part of **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, an open collection for education and L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): ready-to-paste prompts for teachers, with the pedagogy behind them
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): assessment rubrics with observable levels
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): test and exam questions with answer key and feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specific, actionable feedback on student work
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): accessible lesson materials using UDL
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): training programs and learning journeys
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): rough requests turned into strong prompts for Claude

## Install

**In Claude (web, desktop or mobile):**
1. Download [`lesson-designer.skill`](lesson-designer.skill)
2. Upload it under Skills in your Claude settings
   (or open the file in a Claude conversation and click *Save skill*)

**In Claude Code:** copy the `lesson-designer/` folder to `~/.claude/skills/`.

Then just ask, for example *"a 50-minute lesson on percentages for 12-year-olds, first lesson on the topic"*. The skill starts automatically.

## Contributing

Ideas and improvements are welcome via an issue or pull request.

## License

[CC BY 4.0](LICENSE): free to use, adapt and share, with attribution.

---

Made by **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI literacy for education.
