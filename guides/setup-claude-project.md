# Setup: Claude Project

Menu names and limits change. If something looks different, check Anthropic's current documentation.

## 1. Create the project
In Claude.ai, open Projects and create a new project. Name it something functional, for example "CEO Sparring Partner".

## 2. Add the instructions
1. Open `system-prompt.md` and replace every `[PLACEHOLDER]`.
2. Paste the prompt text (not the customization guide) into the project instructions.

Spend real time on the strengths, shadow sides and values. A generic prompt gives generic advice.

## 3. Write your first entries before uploading
Blank templates are useless. Before uploading anything:

- Decision log: 2 or 3 past decisions, including one that went wrong
- People profiles: your 5 most consequential people
- Reflections log: 3 entries (one event, one book idea, one friction)
- Company context: fully filled in (about 20 minutes)

## 4. Upload the knowledge base
Export each document as markdown and upload the four files to the project knowledge. Do not upload the system prompt as a file. It belongs in the instructions.

## 5. Start a conversation inside the project
Conversations in the project use the instructions and the uploaded files. What you say in a conversation does not update the files. To add knowledge, update the source document and re-upload.

## 6. Test it
Run the checks in `calibration-tests.md` before trusting the output.

## Tips
- Use one file per document type with consistent headings, so the bot can cross-reference.
- Keep people profiles to roles or initials if you share your screen often.
- Log decisions before outcomes are known.
- Consolidate old entries every few months to keep files lean.
