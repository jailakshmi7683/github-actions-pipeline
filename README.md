# github-actions-pipeline

This repository contains a basic GitHub Actions workflow that:

- Runs on every push to the `main` branch
- Sets up a Node.js environment (Node.js 16)
- Prints a greeting message in the Actions log

## Output

Logs the message:

```

Hello from @jailakshmi7683

```

## File Structure

```

.github/
└── workflows/
└── main.yml

```

## How it Works

1. The workflow triggers on push to the `main` branch.
2. It checks out the code.
3. It sets up a Node.js environment.
4. It prints the greeting message in the log.

## Status

Successfully tested and running!
