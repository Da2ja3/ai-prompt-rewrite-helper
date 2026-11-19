# AI Prompt Rewrite Helper

Paste a weak prompt, get a tighter one back. It strips the filler, finds the real request, and lays it out with role, task, output, audience and tone, so the model knows exactly what you want.

## How to use

Open the page, paste a prompt as you would normally write it, and hit **Rewrite it**. Fill in anything in amber `[brackets]`, then copy the result and use it.

There are three examples to try: a prompt about dogs, a space story for a kid, and a time-off email to a boss.

## How it works

No API key, no sign-up, no server. A set of plain rules does the rewrite in your browser:

- Strips filler openers like "please", "can you", "I want you to" and "help me".
- Cuts hedge words like "very", "really", "just" and "actually".
- Pulls out the role, output format, length, audience and tone when they are there.
- Rebuilds the prompt in a fixed structure: ROLE, TASK, CONTEXT, OUTPUT, AUDIENCE, TONE.
- Flags whatever is still missing, with a line on why each piece matters.

It also scores the prompt before and after on eight checks: role, clear task, context, output format, length, audience, tone, and a constraint or example.

## Run it locally

Just open `index.html` in a browser. It is a single self-contained page.

## License

MIT
