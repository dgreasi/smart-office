# smart-office

A repo to add smart automations for an office, like home assistant, taliscale and pbx asterisk. Deployed on `balena.io`

## Getting started

- Create a `.env` file based on the `.env.example` file and fill with your balena project name
- Install balena CLI
- Install dependencies with `npm install`
- Deploy with `npm run deploy`

## Enable tailscale exit node

```bash
# Run the following after connecting with SSH in your taliscale docker
tailscale up --advertise-exit-node
# This will print the exact command that you need to run in order to enable the exit node
# Copy the command and run it in your terminal
```
