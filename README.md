# CEO Sparring Partner Kit

Templates and a system prompt that turn a Claude Project into a challenge-first thinking partner for leaders.

It is not an assistant. It is built to disagree with you, name your blind spots, and ground its advice in your own decision history and in well-validated management frameworks.

## What you get

- `system-prompt.md`: the project instructions, with placeholders for your strengths, values and cognitive style
- `templates/`: four documents that form the knowledge base (decision log, people profiles, reflections log, company context)
- `guides/`: setup, a Notion-based update workflow, and calibration tests

## How it works

For every substantive question, the bot follows five steps:

1. **Steelman**: states your position as charitably as possible
2. **Challenge**: gives the strongest contrary view, naming the framework or case behind it
3. **Blind spot check**: surfaces an assumption you have not examined, including the shadow side of your own strengths
4. **Synthesis**: a recommendation with a confidence level and what it depends on
5. **Watch for**: 2 to 3 leading indicators that tell you whether you are on track

The quality comes from two things: a system prompt that explicitly forbids agreeing just because you pushed back, and a knowledge base that holds your real reasoning, not a polished version of it.

## Setup in about 90 minutes

1. Create a Project in Claude.ai.
2. Customize `system-prompt.md` (replace every `[PLACEHOLDER]`) and paste it into the project instructions. Allow 1 to 2 hours. This is where most of the value comes from.
3. Copy the four templates into your notes tool (Notion, Obsidian or plain markdown files).
4. Fill them in honestly. Start with 2 or 3 past decisions (include one that went wrong), your 5 most consequential people, 3 reflections, and the company context.
5. Export as markdown and upload the four files to the project knowledge.
6. Run the checks in `guides/calibration-tests.md`.

Detailed steps: `guides/setup-claude-project.md`.

## Keeping it current

Your notes tool is the source of truth. The project holds a snapshot. When you update a document, replace the uploaded file. See `guides/notion-workflow.md`.

Log decisions before you know the outcome. Hindsight contaminates the reasoning field, and that field is what the bot learns from.

## Privacy and safety

- **Never publish or share a filled-in version.** People profiles contain candid opinions about named individuals.
- Follow your company's AI policy and applicable data protection law (for example GDPR) before putting information about employees, clients or partners into any AI tool. Consider roles or initials instead of full names.
- Do not upload confidential client data you are not permitted to share.
- Review what you upload as if someone else might read it one day.

## Limits

- Language models lean toward agreement. This kit reduces that tendency, it does not remove it. Test it (see calibration tests).
- The bot only knows what you put in. Thin or flattering inputs produce thin or flattering advice.
- You stay accountable for decisions. This is not a substitute for professional legal, financial, medical or mental health advice, or for human coaching and mentoring.
- Claude's product features and limits change. Check Anthropic's current documentation for project and file limits.

## Credits and trademarks

CliftonStrengths is a trademark of Gallup, Inc. This kit is not affiliated with or endorsed by Gallup or Anthropic. The kit refers to strength names only as examples of self-knowledge inputs. Use your own assessment results.

## License

Creative Commons Attribution 4.0 International (CC BY 4.0). Use it, adapt it, share it, and credit the source.
