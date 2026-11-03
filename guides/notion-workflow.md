# Workflow: Notion as the source of truth

Notion holds the master copies. The Claude Project holds a snapshot. The same loop works with Obsidian or plain files.

## One-time setup (20 minutes)

1. Create a page named "CEO Sparring Partner".
2. Create five sub-pages: System Prompt (reference only), Decision Log, People Profiles, Reflections Log, Company Context.
3. Paste the matching template into each.

## The update loop

1. Edit in Notion.
2. Export the page as Markdown.
3. In the Claude Project, delete the old file.
4. Upload the new file.
5. Open a new conversation.

## Triggers

| When | Do this |
|---|---|
| Something significant happens | Add an [EVENT] entry to the reflections log |
| You make a major decision | Add a decision log entry before you know the outcome |
| Your read on someone changes | Update their profile and the "last updated" note |
| You finish a relevant book chapter | Add a [BOOK] entry with why it matters |
| Quarterly | Re-export everything, replace the files, consolidate old entries |

## Why the friction helps
Writing in a real document, rather than chatting a thought into a box, gives better input. The bot is only as good as what you give it.

## Optional: draft with the bot
Ask the bot to help you write an entry in the right format, then paste the result into your document and re-upload.
