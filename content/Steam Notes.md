---
title: Steam notes
tags:
  - steam
---

![[Pasted image 20240111155313.png]]

![[Pasted image 20240111155255.png]]

## Publishing changes
Any changes you make in the steam admin require you to go through a manual publishing step, including activating new builds. It is kinda nice and gives you a somewhat clunky diff of what you've changed.

### Builds & Depots
You can have one or more depots for your app. Depots are for separate builds, which can be for different OSs, translations, betas, or DLCs, whatever.

![[Pasted image 20240111155105.png]]

### Uploading builds!
You can upload `.zip` files for builds, but I would recommend using their SteamPipe application. When you download the SDK, you can find it in the folder `sdk\\tools\\SteamPipeGUI`. It’s a bit like a GUI version of itch’s `butler`.

### Users
You can add users to the app for testing or collaboration. You have to first invite them via email. It will add them to the “Everyone” group. Then they need to accept the invite (and if I remember right you have to accept their acceptance 😄). Once they’re full in then you can put them in a group by editing the group, not the user, and selecting “Add user to this group”.