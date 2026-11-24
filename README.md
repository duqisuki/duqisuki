### Hi, I'm duqisuki 👋

Game developer and modder. I build co-op mods for games that never had them, fix broken
multiplayer at the DLL level, and make small graphics and game experiments that run right in the browser.

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WebGL](https://img.shields.io/badge/WebGL2%20%2F%20GLSL-990000?style=flat-square&logo=webgl&logoColor=white)
![Unity](https://img.shields.io/badge/Unity%20%2F%20BepInEx-000000?style=flat-square&logo=unity&logoColor=white)
![Steamworks](https://img.shields.io/badge/Steamworks-171A21?style=flat-square&logo=steam&logoColor=white)
![Zig](https://img.shields.io/badge/Zig-F7A41D?style=flat-square&logo=zig&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![s&box](https://img.shields.io/badge/s%26box%20(Source%202)-1E1E1E?style=flat-square)

## Projects

<table>
<tr>
<td width="50%" valign="top">

#### [🎮 Rooftop Anthology](https://github.com/duqisuki/isometric-rooftop-diorama)
<a href="https://duqisuki.github.io/isometric-rooftop-diorama/"><img src="https://raw.githubusercontent.com/duqisuki/isometric-rooftop-diorama/main/docs/screenshot.png" alt="Rooftop Anthology"></a>

Pixel-art zombie-apocalypse story in six isometric dioramas. Custom pixel renderer,
isometric projection, A* pathfinding, crowd AI, weather and procedural audio, with zero dependencies.

**[▶ Play in browser](https://duqisuki.github.io/isometric-rooftop-diorama/)** · `JavaScript` `Canvas 2D`

</td>
<td width="50%" valign="top">

#### [💧 Hydrogen](https://github.com/duqisuki/hydrogen-sdf-shader)
<a href="https://duqisuki.github.io/hydrogen-sdf-shader/"><img src="https://raw.githubusercontent.com/duqisuki/hydrogen-sdf-shader/master/docs/screenshot.png" alt="Hydrogen"></a>

Real-time liquid glass in pure WebGL2: sphere-traced SDF generated with an exact distance
transform, refraction, chromatic dispersion, Beer–Lambert absorption, frost.

**[▶ Live demo](https://duqisuki.github.io/hydrogen-sdf-shader/)** · `WebGL2` `GLSL`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [🏊 POOLS Co-op](https://github.com/duqisuki/pools-coop)
Unofficial online co-op mod for **POOLS** (flat and VR). BepInEx 6 IL2CPP plugin that syncs
players' heads and finger-tracked hands at 60 Hz, footsteps, water, doors and scripted scares over
Steam P2P. One-command installer with SHA-256 verification.

`C#` `BepInEx` `Unity IL2CPP` `Steamworks P2P`

</td>
<td width="50%" valign="top">

#### [🔫 Serious Sam 2 Steam Invite Fix](https://github.com/duqisuki/ss2-steam-invite-fix)
Makes accepting Steam invites in Serious Sam 2 actually join the host. A tiny `steam_api.dll`
proxy in C that catches lobby join callbacks and starts the game's own client connection.
One-line PowerShell install.

`C` `Win32` `Steamworks API` `Zig`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [🚪 FailRooms Co-op](https://github.com/duqisuki/failrooms-coop)
Online two-player co-op for the single-player game **FailRooms**. A UE4SS Lua mod syncs the partner,
maps, triggers, interactions and cutscenes, and a C# launcher handles Steam lobbies, invites and
relays traffic over Steam networking: no IP or VPN needed.

`Lua` `UE4SS` `C#` `Steamworks networking`

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

I also build games on [s&box](https://sbox.game) (Source 2, C#): co-op, survival and sandbox prototypes.
