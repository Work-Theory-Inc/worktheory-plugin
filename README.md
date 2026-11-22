# Work Theory

Work Theory lets people invite others to help guide their AI. This plugin connects your AI to Work Theory: the
projects you keep there, the advice of the guides you invited, and, if you guide other people's projects, your
team's playbook.

## What's in it

- **The Work Theory connector** (`.mcp.json`): `https://api.worktheory.ai/functions/v1/mcp`. You sign in to it
  with your Work Theory account, by an emailed code. It lists Work Theory's tools: reading a project's briefing,
  searching the guides' advice, saving what you decide, and asking a guide a question.
- **One skill**, *Work Theory* (`skills/work-theory/`), which says how to use those tools, for clients and guides
  alike. It has two parts:
  - *Guiding*, for guides: see what is waiting, answer clients' questions, and keep the team's playbook.
  - *Working on a project*, for a project's clients and members: work from the project's record and the guides'
    advice, say whose advice was used, and save decisions when you say yes.

The skills' full text is in this repository. Nothing they do is hidden from you.

## What it needs

A Work Theory account, as a client of a project or as a guide. Start at https://worktheory.ai.

## Adding it

- **Claude:** Customize > Plugins > Add marketplace, with this repository's address; then install Work Theory and
  connect it on the plugin's Connectors tab. In Claude Code:
  `/plugin install worktheory --marketplace Work-Theory-Inc/worktheory-plugin`
- **ChatGPT and Grok:** the Work Theory portal's setup page says how, for each.

## What is saved

Work Theory saves only what you or your guides ask your AI to save, in the project you are working on. Who sees
what is set out in the Privacy Policy: https://worktheory.ai/privacy

## License

You may install and use this plugin with Work Theory, and nothing more. See `LICENSE`. Using Work Theory is
governed by its Terms of Use: https://worktheory.ai/terms

Questions: hello@worktheory.ai
