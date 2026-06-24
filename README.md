# ProductTank London — LinkedIn Posts Skill

A [Claude skill](https://docs.claude.com/en/docs/claude-code/skills) for drafting
LinkedIn posts for ProductTank London events in the official brand voice.

It covers four post types — **event announcement**, **speaker introduction**,
**event reminder**, and **post-event recap** — along with the posting cadence,
tagging rules, and formatting conventions used on the
[ProductTank London LinkedIn page](https://www.linkedin.com/company/producttanklondon/).

## Installing

Clone this repo into your Claude skills directory:

```bash
# Personal (available in all projects)
git clone https://github.com/<your-username>/producttank-linkedin-posts.git \
  ~/.claude/skills/producttank-linkedin-posts

# Or per-project
git clone https://github.com/<your-username>/producttank-linkedin-posts.git \
  .claude/skills/producttank-linkedin-posts
```

Then ask Claude something like *"Draft the announcement post for our next
ProductTank London event"* and the skill will activate.

## Structure

```
producttank-linkedin-posts/
├── SKILL.md                        # Entry point — cadence, rules, routing
└── references/
    ├── announcement-post.md        # Event announcement template + example
    ├── speaker-post.md             # Speaker intro template + example
    ├── event-reminder-post.md      # Reminder template + example
    └── post-event-recap.md         # Post-event recap template
```

## Source

Templates and guidance are derived from the ProductTank London "Posting on LinkedIn"
internal guidance, with real example posts from the LinkedIn page.
