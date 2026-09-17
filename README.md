# Learning Game Dev

Over the past year, I’ve been learning game development, making small games, and collecting resources along the way. I started with Unreal Engine. I loved its 3D tools and how much I could build with Blueprints without writing code. I spent months learning and experimenting, but Unreal felt like an ocean: every new thing I learned revealed something else to explore.

Then I wanted to make a 2D game and found Godot. Its open-source approach appealed to me, and I used it to make a few game jam projects and small games. Finishing those projects helped me put what I was learning into practice. More recently, I got curious about why so many indie developers enjoy Unity. As I’ve explored it, I’ve really enjoyed the built-in features and workflows. I’ve decided to use Unity as my primary engine for my next release. That’s a personal choice shaped by what I want to make.

Throughout this journey, I’ve saved resources in my Notion board. This repository brings that collection together so I can share it with the community I’ve learned from.

There are plenty of great game development lists out there. This is my version: a growing collection of resources gathered during my own learning journey. Contributions, corrections, and suggestions are welcome, see [how to contribute](CONTRIBUTING.md).

## Index

- **Start**
  - [How to start game development](#how-to-start-game-development)
  - [Game engines](#game-engines)
    - [Godot](#godot)
    - [Unity](#unity)
    - [Unreal Engine](#unreal-engine)
  - [Programming basics](#programming-basics)
  - [Intro to math](#intro-to-math)
- **Design**
  - [Game design and game feel](#game-design-and-game-feel)
  - [Level design](#level-design)
- **Gameplay systems**
  - [Gameplay architecture and saving](#gameplay-architecture-and-saving)
  - [Physics and collision](#physics-and-collision)
  - [Game AI and pathfinding](#game-ai-and-pathfinding)
  - [Procedural generation](#procedural-generation)
  - [Multiplayer and networking](#multiplayer-and-networking)
- **Art and presentation**
  - [2D art and pixel art](#2d-art-and-pixel-art)
  - [3D art and asset pipelines](#3d-art-and-asset-pipelines)
  - [Animation and rigging](#animation-and-rigging)
  - [Shaders and graphics](#shaders-and-graphics)
  - [Audio and music](#audio-and-music)
  - [UI, accessibility, and localization](#ui-accessibility-and-localization)
- **Build and release**
  - [Testing and debugging](#testing-and-debugging)
  - [Version control and collaboration](#version-control-and-collaboration)
  - [Production, publishing, and marketing](#production-publishing-and-marketing)
    - [Planning and production](#planning-and-production)
    - [Publishing and store pages](#publishing-and-store-pages)
    - [Marketing and audience research](#marketing-and-audience-research)
    - [Trailers, press kits, and outreach](#trailers-press-kits-and-outreach)
    - [Demos, festivals, and playtests](#demos-festivals-and-playtests)
    - [Community and post-launch support](#community-and-post-launch-support)
    - [Funding and crowdfunding](#funding-and-crowdfunding)
  - [Assets and practice](#assets-and-practice)
- **Study formats**
  - [Source projects to study](#source-projects-to-study)
  - [Books](#books)
  - [Study materials and research](#study-materials-and-research)
  - [YouTube channels](#youtube-channels)
  - [Courses](#courses)

🌱 **Beginner** · 🌿 **Intermediate** · 🌳 **Advanced** 

## How to start game development

> Game development is simply the art of combining storytelling, design, and code to build interactive worlds that people can play and have fun.

**While that might sound complicated, getting started is easier than you think.**

Start with one small, playable game. No engine or programming experience required.

1. **Think of a simple idea:** Keep it very very small, like - licking a moving target.
2. **Pick a engine:** So many game engines out there, pick one and just go, [Game engines](#game-engines).
3. **Follow a tutorial:** Find a tutorial and build a game step-by-step from start to finish. Event just understanding all about basic engine features and basics will get you far when starting.
4. **Make it yours:** Once the tutorial game works, try changing one small thing (like the player's speed or color).
5. **Share it:** Have a friend play your game and celebrate your first creation!
6. **Repeat:** Keep doing it and practice more. Join game jam.
 

[Back to index](#index)

## Game engines

| Engine / tool | Focus | Learning links |
| --- | --- | --- |
| [Godot](#godot) | 2D / 3D, GDScript / C# | [Step by step](https://docs.godotengine.org/en/stable/getting_started/step_by_step/index.html) · [First 2D game](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/) |
| [Unity](#unity) | 2D / 3D, C# | [Essentials](https://learn.unity.com/pathway/unity-essentials) · [Junior Programmer](https://learn.unity.com/pathway/junior-programmer) |
| [Unreal Engine](#unreal-engine) | 3D, Blueprints / C++ | [New user guide](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-for-new-users) |
| [GameMaker](#gamemaker) | 2D, GML / visual logic | [Tutorials](https://gamemaker.io/en/tutorials) · [LTS manual](https://manual.gamemaker.io/lts/en/Content.htm) |
| GDevelop | Visual events | [Getting started](https://wiki.gdevelop.io/gdevelop5/getting_started/) |
| Defold | Lua | [Tutorials and manuals](https://defold.com/learn/) |
| Phaser | Browser games, JavaScript / TypeScript | [Setup](https://phaser.io/tutorials/getting-started) · [First game](https://docs.phaser.io/phaser/getting-started/making-your-first-phaser-game) |
| Ren'Py | Visual novels | [Engine](https://www.renpy.org/) · [Quickstart](https://www.renpy.org/doc/html/quickstart.html) |
| Twine | Interactive stories | [Tool](https://twinery.org/) · [Cookbook](https://twinery.org/cookbook/) |
| Construct | Visual events | [Tutorials](https://www.construct.net/en/tutorials) · Mixed levels |
| MonoGame | C# framework | [Getting started](https://docs.monogame.net/articles/getting_started/) · C# basics needed |
| raylib | C programming library | [Examples](https://www.raylib.com/examples.html) · C basics needed |

Engine licensing and export costs are separate from learning-resource access.

### Godot

- [Official documentation](https://docs.godotengine.org/en/stable/) — Engine manual and feature guides · 🌱🌿🌳
- [Official demo projects](https://github.com/godotengine/godot-demo-projects) — Working examples by feature · Match engine version · 🌱🌿
- [GDQuest](https://www.gdquest.com/) — Projects and workflows · Free tutorials; paid courses · 🌱🌿
- [Performance guides](https://docs.godotengine.org/en/stable/tutorials/performance/index.html) — CPU, GPU, optimization · 🌿🌳
- [Asset Library](https://godotengine.org/asset-library/asset) — Add-ons, templates, tools
- [Godot Forum](https://forum.godotengine.org/) — Questions and community discussions

### Unity

- [Unity Manual](https://docs.unity3d.com/Manual/index.html) — Editor and engine systems · 🌱🌿🌳
- [Unity Learn](https://learn.unity.com/pathways) — Structured learning paths · Free; account for progress · 🌱🌿
- [Shader Graph](https://docs.unity3d.com/Packages/com.unity.shadergraph@17.0/manual/Getting-Started.html) — Visual shader workflows · Package 17.0 · 🌱🌿
- [Unity Asset Store](https://assetstore.unity.com/) — Assets and extensions · Free and paid
- [Unity Discussions](https://discussions.unity.com/) — Questions and community discussions

### Unreal Engine

- [Official documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine) — Engine systems and workflows · 🌱🌿🌳
- [Blueprints visual scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/blueprints-visual-scripting-in-unreal-engine) — Visual gameplay logic · 🌱🌿
- [Epic learning library](https://dev.epicgames.com/community/unreal-engine/learning) — Tutorials, courses, demonstrations · 🌱🌿🌳
- [Fab](https://www.fab.com/) — Assets and plugins · Free and paid; check compatibility
- [Epic Developer Community Forums](https://forums.unrealengine.com/) — Questions and community discussions

### GameMaker

- [GameMaker Manual](https://manual.gamemaker.io/monthly/en/) — Editor, language, features · Monthly documentation · 🌱🌿🌳
- [Official tutorials](https://gamemaker.io/en/tutorials) — Projects and individual techniques · Filter by level · 🌱🌿🌳
- [GameMaker Community](https://gamemaker.io/en/community) — Forums and community channels

[Back to index](#index)

## Programming basics

- [Microsoft: Get started with C#](https://learn.microsoft.com/en-us/training/paths/get-started-c-sharp-part-1/) — C# fundamentals · 🌱
- [Learn C++](https://www.learncpp.com/) — C++ fundamentals and beyond · 🌱🌿🌳
- [Harvard CS50x](https://cs50.harvard.edu/x/) — Computer science and problem solving · Free course materials · 🌱
- [MDN: Game development](https://developer.mozilla.org/en-US/docs/Games) — Web game programming · 🌱🌿

[Back to index](#index)

## Intro to math

Suggested order: coordinates → vectors → trigonometry → interpolation → matrices → quaternions.

- [Khan Academy: Trigonometry](https://www.khanacademy.org/math/trigonometry) — Angles, sine, cosine · 🌱
- [3D Math Primer](https://gamemath.com/book/) — Coordinate spaces, matrices, rotations, quaternions · Free online book · 🌱🌿🌳
- [Red Blob Games](https://www.redblobgames.com/) — Grids, geometry, probability, algorithms · Interactive · 🌱🌿
- [The Nature of Code](https://natureofcode.com/) — Forces, motion, simulation · JavaScript basics · Free online book · 🌿

[Back to index](#index)

## Game design and game feel

- [The Art of Game Design](https://schellgames.com/art-of-game-design) — Mechanics and player experience · Paid book · 🌱🌿
- [Game Maker's Toolkit](https://gamemakerstoolkit.com/) — Design analysis and production · Video · 🌱🌿

[Back to index](#index)

## Level design

- [The Level Design Book](https://book.leveldesignbook.com/) — Layout, blockout, encounters · Free online; work in progress · 🌱🌿
- [How to make a level](https://book.leveldesignbook.com/process/overview) — Design workflow · 🌱
- [Blockout](https://book.leveldesignbook.com/process/blockout) — Playable greybox prototypes · 🌱🌿

[Back to index](#index)


## Gameplay architecture and saving

- [Game Programming Patterns](https://gameprogrammingpatterns.com/index.html) — State machines, events, object pools · Programming basics · 🌿
- [Godot: Best practices](https://docs.godotengine.org/en/stable/tutorials/best_practices/index.html) — Scenes, scripts, project structure · 🌿

[Back to index](#index)

## Physics and collision

- [Godot: Physics introduction](https://docs.godotengine.org/en/stable/tutorials/physics/physics_introduction.html) — Bodies, collision shapes, layers · 🌱
- [Gaffer: Fix Your Timestep!](https://gafferongames.com/post/fix_your_timestep/) — Simulation timing · Classic article · 🌿
- [Box2D documentation](https://box2d.org/documentation/) — Rigid bodies, contacts, joints · Match library version · 🌿🌳

[Back to index](#index)

## Game AI and pathfinding

- [Red Blob: Introduction to A*](https://www.redblobgames.com/pathfinding/a-star/introduction.html) — Graph search and pathfinding · Interactive · 🌱🌿
- [Unreal: Behavior Trees](https://dev.epicgames.com/documentation/en-us/unreal-engine/behavior-trees-in-unreal-engine) — NPC decision making · 🌿
- [Game AI Pro](https://www.gameaipro.com/) — Production AI techniques · Free chapters · 🌿🌳

[Back to index](#index)


## 2D art and pixel art

- [Krita user manual](https://docs.krita.org/en/user_manual.html) — Painting, layers, brushes · 🌱🌿
- [Aseprite documentation](https://www.aseprite.org/docs/) — Pixel art, sprites, animation · Free docs; paid official binaries · 🌱🌿
- [Kenney assets](https://kenney.nl/assets) — Study consistent sprites and UI packs · Asset library · 🌱

[Back to index](#index)

## 3D art and asset pipelines

- [Blender: Modeling](https://www.blender.org/features/modeling/) — Modeling tools and UV overview · Overview · 🌱
- [Blender modeling manual](https://docs.blender.org/manual/en/4.0/modeling/index.html) — Meshes and modeling workflows · Blender 4.0 reference · 🌱🌿

[Back to index](#index)

## Animation and rigging

- [Blender: Animation and rigging](https://docs.blender.org/manual/en/4.2/animation/index.html) — Armatures, constraints, animation · Blender 4.2 reference · 🌿
- [Dikko](https://www.youtube.com/@Dikko) — Character modeling and rigging · Video · 🌿

[Back to index](#index)

## Shaders and graphics

### Start here

- [The Book of Shaders](https://thebookofshaders.com/) — GLSL fragment shaders · Interactive · 🌱
- [Catlike Coding](https://catlikecoding.com/unity/tutorials/) — Unity shaders and rendering · Version-specific series · 🌱🌿🌳
- [Unity: Shader Graph](https://docs.unity3d.com/Packages/com.unity.shadergraph@17.0/manual/Getting-Started.html) — Visual shader authoring · Package 17.0 · 🌱🌿

### Go deeper

- [LearnOpenGL](https://learnopengl.com/) — Rendering, lighting, textures · C++ required · 🌿
- [Scratchapixel](https://www.scratchapixel.com/) — Graphics mathematics and implementation · 🌿🌳

[Back to index](#index)

## Audio and music

- [Audacity manual](https://manual.audacityteam.org/) — Record, edit, and process sound · 🌱
- [FMOD Learn](https://www.fmod.com/learn) — Interactive audio and game integration · Check software access and licensing · 🌱🌿

[Back to index](#index)

## UI, accessibility, and localization

- [Unity: UI Toolkit](https://docs.unity3d.com/6000.0/Documentation/Manual/UIElements.html) — Interface construction · Unity 6.0 · 🌿
- [Game Accessibility Guidelines](https://gameaccessibilityguidelines.com/basic/) — Controls, readability, alternatives · 🌱

[Back to index](#index)

## Testing and debugging

- [The Level Design Book: Playtesting](https://book.leveldesignbook.com/process/blockout/playtesting) — Observe players and collect feedback · 🌱

[Back to index](#index)

## Version control and collaboration

- [GitHub: Hello World](https://docs.github.com/en/get-started/using-github/hello-world) — Repositories and pull requests · Account required · 🌱
- [Pro Git](https://git-scm.com/book/en/v2) — Branching, merging, team workflows · Free online book · 🌱🌿🌳
- [Git LFS](https://git-lfs.com/) — Large art and audio files · Hosting limits vary · 🌿

[Back to index](#index)

## Production, publishing, and marketing

Platform documentation is free to read; using publishing tools may require an approved developer account. Check current eligibility for funding and events.

### Planning and production

- [Develop Games](https://www.develop.games/) — Scope and project planning · 🌱
- [The Level Design Book: Pre-production](https://book.leveldesignbook.com/process/preproduction) — Research and planning · 🌱🌿

### Publishing and store pages

- [itch.io: Your first page](https://itch.io/docs/creators/getting-started) — Upload and share · Account required · 🌱
- [Steamworks: Store presence](https://partner.steamgames.com/doc/store) — Store pages and release presentation · 🌿
- [Steamworks: Pricing](https://partner.steamgames.com/doc/store/pricing) — Pricing tools and regional currencies · 🌿

### Marketing and audience research

- [How To Market A Game](https://howtomarketagame.com/) — Audience, positioning, and email marketing · Free articles; paid courses · 🌱🌿
- [How To Market A Game: Starter articles](https://howtomarketagame.com/favorite-posts/) — Selected marketing lessons · 🌱🌿
- [Steamworks: Wishlists](https://partner.steamgames.com/doc/marketing/wishlist) — Wishlist features and notifications · 🌱🌿

### Trailers, press kits, and outreach

- [Derek Lieu: How to make a trailer](https://www.derek-lieu.com/start-here) — Capture, structure, editing · Free guides; optional paid course · 🌱🌿
- [Steamworks: Trailers](https://partner.steamgames.com/doc/store/trailer) — Store video requirements · 🌿
- [presskit()](https://dopresskit.com/) — Build a game press kit · Self-hosted tool · 🌱🌿

### Demos, festivals, and playtests

- [Steam Playtest](https://partner.steamgames.com/doc/features/playtest) — Recruit players and manage test access · 🌿
- [Steam Next Fest](https://partner.steamgames.com/doc/marketing/upcoming_events/nextfest) — Demo festival preparation and eligibility · 🌿
- [The Level Design Book: Playtesting](https://book.leveldesignbook.com/process/blockout/playtesting) — Gather and interpret player feedback · 🌱

### Community and post-launch support

- [Steamworks: Events and announcements](https://partner.steamgames.com/doc/marketing/event_tools) — Updates, announcements, player communication · 🌿

### Funding and crowdfunding

- [Kickstarter Creator Handbook](https://www.kickstarter.com/help/handbook) — Campaign planning, rewards, communication · 🌱🌿
- [Epic MegaGrants](https://www.unrealengine.com/megagrants) — Program scope, eligibility, application guidance · 🌿

[Back to index](#index)

## Assets and practice

- [Kenney](https://kenney.nl/assets) — 2D, 3D, UI, audio.
- [Poly Haven](https://polyhaven.com/) — Models, textures, HDRIs.
- [OpenGameArt](https://opengameart.org/) — Community art and audio; licenses vary.
- [Freesound](https://freesound.org/) — Sound recordings; licenses vary, download account required.
- [itch.io game jams](https://itch.io/jams) — Time-boxed practice and themes.
- [Gamedev.js](https://gamedevjs.com/) — Web game development community and events.

Keep each asset's license and attribution requirements with your project.

[Back to index](#index)

## Source projects to study

- [Godot demo projects](https://github.com/godotengine/godot-demo-projects) — Small examples by feature · 🌱🌿

Use each repository's documented engine version and setup instructions.

[Back to index](#index)

## Books

| Book | Author(s) | Topic / level | Access |
| --- | --- | --- | --- |
| [The Art of Game Design](https://schellgames.com/art-of-game-design) | Jesse Schell | Design and player experience · 🌱🌿 | Paid book |
| [Game Programming Patterns](https://gameprogrammingpatterns.com/index.html) | Robert Nystrom | Code structure and patterns · 🌿 | Free online; paid editions |
| [3D Math Primer for Graphics and Game Development](https://gamemath.com/book/) | Fletcher Dunn, Ian Parberry | Vectors, matrices, rotations · 🌱🌿🌳 | Free online |
| [Real-Time Rendering](https://www.realtimerendering.com/) | Tomas Akenine-Möller et al. | Rendering techniques · 🌳 | Paid book; free selected chapters |
| [Physically Based Rendering](https://www.pbr-book.org/) | Matt Pharr, Wenzel Jakob, Greg Humphreys | Renderer implementation · 🌳 | Free online; paid print |
| [The Level Design Book](https://book.leveldesignbook.com/) | Robert Yang and contributors | Level design · 🌱🌿 | Free online; work in progress |

[Back to index](#index)

## Study materials and research

- [Advances in Real-Time Rendering](https://advances.realtimerendering.com/) — SIGGRAPH course slides and talks · 🌳
- [Real-Time Rendering resources](https://www.realtimerendering.com/) — Papers, bibliographies, graphics references · 🌳
- [DiGRA Digital Library](https://dl.digra.org/index.php/dl/issue/archive) — Game studies research and proceedings · 🌿🌳
- [GDC Vault: Free content](https://gdcvault.com/free) — Production talks and postmortems · 🌿🌳

[Back to index](#index)

## YouTube channels

| Channel | Topics | Level |
| --- | --- | --- |
| [Brackeys](https://www.youtube.com/@Brackeys) | Godot; older Unity tutorials | 🌱 |
| [GDQuest](https://www.youtube.com/@Gdquest) | Godot, GDScript, workflows | 🌱🌿 |
| [Game Maker's Toolkit](https://www.youtube.com/@GMTK) | Game design, levels, player experience | 🌱🌿 |
| [3Blue1Brown](https://www.youtube.com/@3blue1brown) | Visual mathematics | 🌱🌿🌳 |
| [Acerola](https://www.youtube.com/@Acerola_t) | Shaders, rendering, graphics experiments | 🌿🌳 |
| [Dikko](https://www.youtube.com/@Dikko) | Character modeling and rigging | 🌿 |

[Back to index](#index)



### Courses

- [Unity Learn pathways](https://learn.unity.com/pathways) — Guided Unity learning · Free; account for progress · 🌱🌿
- [GDQuest courses](https://www.gdquest.com/) — Structured Godot learning · Paid courses; free tutorials · 🌱🌿
- [GameDev.tv](https://gamedev.tv/) — Unity, Unreal, Godot, art · Paid courses / account required · 🌱🌿

[Back to index](#index)

---

[Contribute a resource](CONTRIBUTING.md)

Last updated: **2026-09-17**.