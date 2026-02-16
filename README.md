# PenguinMod Extension Code Golfing
Thread: https://discord.com/channels/1033551490331197462/1470298832410771649

Idea by `@literally.barbarossa`
(even though i had the idea first they were just the first one to say it)

## Rules
- You are trying to code a working extension with the lowest file size possible (measured in bytes).
- To be a valid entry, the extension must be loadable in PenguinMod/TurboWarp (depending on category) via the File import tab.
- To submit, comment the categor(y/ies) and code in this space and **make sure to ping me `@the_can_of_soup`.**
- Edited messages are disqualified.
- Unless otherwise specified:
  - Errors do not disqualify submissions, as long as the requirements are still met.
  - No other extensions may be loaded before or after loading the submission when testing.
  - Loading a pre-existing extension is not allowed.
  - PenguinMod devs cannot ["toss random shit into the vm to make this more optimized"](https://discord.com/channels/1033551490331197462/1470298832410771649/1473014091143446561).
  - Completing the criteria for the category in a different browser tab from the one that loaded the extension or in the same tab but after a refresh is not a valid submission.

## Categories
- any%
  - Records:
    - PenguinMod Unsandboxed _[42 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1473006597767958690)_
    - TurboWarp Unsandboxed _[42 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1473006597767958690)_
  - Extension tab must appear.
  - Loading a pre-existing extension **is allowed.**
- unique%
  - Records:
    - PenguinMod Unsandboxed _[44 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1473019948036133017)_
    - TurboWarp Unsandboxed _[43 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1470302145055297546)_
  - Extension tab must appear.
- ACE%
  - Records:
    - PenguinMod Unsandboxed _[100 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1470310620468478095)_
    - TurboWarp Unsandboxed _[93 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1470311557882970163)_
  - Must enable arbitrary unsandboxed JS code execution that can be triggered with only blocks.
- block%
  - Records:
    - PenguinMod Unsandboxed _[74 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1470594187392192717)_
    - TurboWarp Unsandboxed _[67 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1470593834512683171)_
  - Must add a block to the palette.
  - The block does not need to have any functionality.
- customType%
  - Records:
    - PenguinMod Unsandboxed _[160 bytes](https://discord.com/channels/1033551490331197462/1470298832410771649/1473020689752522772)_
  - Must add a non-command block that always returns an instance of a custom type with a valid `customId`.
  - It should be possible with blocks alone to set the `my variable` variable to the return value of the block.
  - After setting the `my variable` variable to the return value of the block, the project should save without errors.
  - After saving the project to a `pmp` file, the project should be loadable in a blank editor tab.
  - Upon loading the project file, the variable should still contain an instance of the same custom type with the same `customId`.

**Feel free to suggest more categories!**
