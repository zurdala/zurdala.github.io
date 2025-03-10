+++
title = "How to disable Copilot in VSCode"
date = "2025-03-10T11:40:00+01:00"

tags = ["dev"]
+++

To disable Copilot in VSCode, a couple of things need to be added to the `settings.json`:

```json
{
  ...
  "chat.commandCenter.enabled": false,  // disables the chat icon in the top bar
  "chat.experimental.statusIndicator.enabled": false,  // disables status indicator in the bottom bar
  ...
}
```

Thanks to Chris for his [post](https://chriswiegman.com/2024/11/turning-off-copilot-in-vscode/).

PS: I need to find how to disable it completely. Maybe switching to [Codium](https://vscodium.com) is already a better choice.
