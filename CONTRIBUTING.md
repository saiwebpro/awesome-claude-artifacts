# Contributing to Awesome Claude Artifacts

Thanks for wanting to contribute! Here's how to do it right.

## Adding an entry

1. **Check it doesn't already exist** — search the README first.
2. **Pick the right category.** If nothing fits, propose a new one in your PR description.
3. **Use this row format:**

```markdown
   | [Name](https://link-to-live-demo) | One-sentence description of what it does. | 🟢 Simple / 🟡 Medium / 🔴 Complex |
```

4. **Link to something that actually works.** Prefer, in order of preference:
   - A live hosted version (GitHub Pages, CodePen, Vercel, etc.)
   - A public Claude share link (note: these can expire — mention this in your PR)
   - A GitHub repo containing the code, if no live demo exists

5. **Add the prompt.** Create a file in `/prompts/<short-name>.md` using [TEMPLATE.md](./TEMPLATE.md), containing:
   - The exact (or closely paraphrased) prompt used
   - Which Claude model generated it, if known
   - Any follow-up prompts used to refine it
   - A screenshot or GIF if you have one (drop it in `/prompts/assets/`)

## Quality bar

We're not trying to list everything — we're trying to list the **best** of each category. Ask yourself:

- Would a stranger find this genuinely impressive or useful?
- Does it actually work when you open the link?
- Is it a complete artifact (not a broken/half-finished experiment)?

If yes to all three, it belongs here.

## Style

- Keep descriptions to one sentence, no fluff ("A really cool app that..." → just say what it does)
- Alphabetize within each category table
- Complexity tags are a rough guide for readers skimming for something to build, not a technical judgment

## Code of conduct

Be kind, be constructive, credit original creators. That's it.
