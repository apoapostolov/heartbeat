<div align="center">

  <h1>Heartbeat</h1>

  <p>Give every hit a pulse with a damage overlay, impact flashes, and heartbeat cues.</p>

  <p>
    <a href="https://github.com/apoapostolov/heartbeat"><img src="https://img.shields.io/badge/Type-Foundry%20module-555" alt="Type: Foundry module"></a>
    <a href="https://github.com/apoapostolov/heartbeat"><img src="https://img.shields.io/badge/Language-JavaScript-555" alt="Primary language: JavaScript"></a>
    <a href="https://github.com/apoapostolov/heartbeat/releases"><img src="https://img.shields.io/badge/Status-Unreleased-555" alt="Unreleased"></a>
  </p>

</div>

Heartbeat adds on-screen and audio cues as a character loses or regains HP.
Damage can flash red, healing can flash green, and low health can bring in a
heartbeat and a heavier screen overlay. GMs can preview the effect by
selecting a token without joining as a player.

![Heartbeat effect during play](https://i.imgur.com/CmFBFsw.gif)

## What it does

- **Make a hit visible.** A brief flash responds to damage or healing. The
  persistent damage overlay becomes stronger as health falls.
- **Signal danger.** A heartbeat sound and animation can begin at a chosen
  HP percentage. A large single hit can play a separate sound.
- **Fit the table.** Set thresholds and effect strength, choose your own
  sounds or overlay, and turn off effects you do not want.
- **Preview as GM.** Test the look on selected tokens before players need to
  see it.

![Low-health effect](https://i.imgur.com/5UNkbSl.gif)

## Installation and status

This repository is Apo's source fork of
[Handyfon's Heartbeat](https://github.com/Handyfon/heartbeat). It has no
published GitHub Release of its own. Its manifest points to Handyfon's
package; installing that URL gets the upstream build, not this fork.

The checked-in source version is **13.3.3**, with Foundry compatibility
declared from v11 through verified v13. Review the manifest and the version
of Foundry you run before installing a source checkout.

## Credits

Heartbeat was created by Handyfon. The checked-in manifest and original
project links remain under Handyfon's name.
