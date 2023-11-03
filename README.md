# Bun Buildpack for Scalingo

## Requirements

- You have to use `bun x` instead of `bunx`
- You have to start your app with a Procfile containing `web: export PATH="$HOME/.scalingo/bun/bun-linux-x64:$PATH" && bun run start`
