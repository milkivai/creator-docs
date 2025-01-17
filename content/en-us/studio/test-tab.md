---
title: Test Tab
description: The Test tab contains tools for testing, simulating multiple clients, and other emulations.
---

import PlaytestOptions from '../includes/studio/testing-modes.md'
import PauseResumePhysics from '../includes/studio/pause-resume-physics.md'

The **Test** tab contains tools for testing and debugging an experience, simulating multiple clients, and emulating different devices or users with regional content policies.

<img src="../assets/studio/general/Toolbar-Test-Tab.png" width="800" alt="Test tab indicated in Studio toolbar." />

## Playtest Options

<PlaytestOptions components={props.components} />

## Pausing & Resuming Physics

<PauseResumePhysics components={props.components} />

## Clients and Servers

Using the **Clients and Servers** options, you can launch multiple sessions of Studio, one acting as the server and each other acting as a client. See [Multi-Client Simulation](../studio/testing-modes.md#multi-client-simulation) for details.

<img src="../assets/studio/general/Test-Tab-Clients-Servers.png" width="800" alt="Clients and Servers options indicated in Test tab" />

## Device Emulation

The **Device** emulator lets you emulate various devices directly in Studio, providing insight on how controls operate on a mobile device or how [on-screen UI](../ui/on-screen-containers.md) displays on different screens and aspect ratios.

<img src="../assets/studio/general/Test-Tab-Emulation-Device.png" width="800" alt="Device button indicated in Test tab" />

In emulation mode, you can select devices from the **Device Selector** dropdown menu above the 3D viewport to emulate less powerful devices and test [streaming-enabled](../workspace/streaming.md) experiences where 3D content dynamically loads/unloads based on available memory. You can also adjust the **view&nbsp;size** and change the **device orientation** between landscape and portrait modes.

<img src="../assets/studio/general/Editor-Window-Emulation-Options.jpg" width="800" alt="Emulation options above the 3D viewport" />

## Player Emulator

The **Player** emulator lets you test various [localization](../production/localization/index.md) and content policies. See [Player Emulation](../studio/testing-modes.md#player-emulation) for details.

<img src="../assets/studio/general/Test-Tab-Emulation-Player.png" width="800" alt="Player emulator button indicated in Test tab" />

## Audio Mute

The **Mute** button allows you to mute in-experience [sounds and music](../sound/index.md).

<img src="../assets/studio/general/Test-Tab-Mute.png" width="800" alt="Mute button indicated in Test tab" />
