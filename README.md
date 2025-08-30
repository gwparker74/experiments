# Experiments: Home Assistant Add-ons

A minimal "Hello World" add-on for Home Assistant OS on Raspberry Pi 5 (aarch64).

## Add to Home Assistant
1. Go to **Settings → Add-ons → Add-on Store**.
2. Click ⋮ (top-right) → **Repositories**.
3. Paste this repo URL: `https://github.com/gwparker74/experiments`
4. The add-on will appear under "Experiments".
5. Install → Start → check **Logs** to see the hello message.

## Development loop
- Edit something in `hello_world/`.
- Bump the `version` in `config.yaml`.
- Commit & push to GitHub.
- In Home Assistant: Add-on Store → ⋮ → **Check for updates** → Update your add-on → Start → Logs.
