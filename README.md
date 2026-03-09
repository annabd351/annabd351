# Anna Dickinson • Engineer • Generalist • Tech Artist • Programmer

Welcome to my site!  Here, you'll find some examples of my recent work as an Engineer and Technical Artist in the Games industry.  I've been coding professionally for quite some time, so on this site, you'll also find examples from my days as an *iOS Developer*.

## Professional Life
* [LinkedIn](https://www.linkedin.com/in/annadickinson)
* My [demo reels](https://vimeo.com/annabd)
* I even have a variety of [film credits](https://www.imdb.com/name/nm1639869)!

Please contact me via LinkedIn if you'd like to chat!

## Recent Work

### Dynamic Niagara Optimization: Trace-Occlusion Culling 
I designed a runtime system which "culls" Niagara instances not visible to the player.  "Culling," in this case, is pausing systems and setting visibility to false.  I check for occlusion through efficient batching of a fixed (small) number of line traces per tick, and use a manageably low tick rate.

In real-world use cases, it can save a significant amount of cycle time, and squeeze VFX into a limited runtime budget.

Take a look at the [code](https://github.com/annabd351/UnrealTechArt/tree/main/NiagaraTraceOcclusionCulling/Source/NiagaraTraceOcclusionCulling/Public).

See it in action. [Demo Video](https://youtu.be/zfOdDgG9BEM) 

The display shows both Niagara stats, and the overhead of the system itself.  There's very little overhead required for a sizable optimization.

### Environment Light Presets
This is an Unreal runtime system/editor tool for lighters which provides a unified way of controlling level-wide environment lighting-related actors (directional light, sky atmosphere, sky light, volumetric clouds, exponential height fog, and a postprocess volume).  It allows lighters to define presets, and store them in data assets.  It also provides a dynamic mixer, which lighters can use to blend between presets.  And it fully supports the Sequencer, allowing for runtime, dynamic, event-driven lighting changes (i.e. in response to changing weather).

[Code](https://github.com/annabd351/UnrealTechArt/tree/main/EnvironmentLightPresets)

[Environment Light Preset Mixer - User Documentation.pdf](https://github.com/user-attachments/files/24920505/Environment.Light.Preset.Mixer.-.User.Documentation.pdf)

### RichFX System
Unreal runtime system which expands the concept of "effects" to include more than just Niagara systems.  It groups together and manages all effect responses to specific gameplay events.  Configuration is via data tables.  This is an extension of the Gameplay Abilities System.

[RichVFX](https://github.com/annabd351/UnrealTechArt/tree/main/RichFX)

### VFX Placement Tool
This is an artist-requested tool/runtime system which helps with VFX distribution in large environments.  It allows you to place multiple instances of Niagara effects, and have them snap to surfaces.  You can configure it to re-trigger and re-distribute instances at specific intervals.

[VFX Placement Tool](https://github.com/annabd351/UnrealTechArt/tree/main/VFXPlacementTool)

### Written Work
Specs, designs, and production plans I wrote while working at (the now defunct) Jar of Sparks.

[Documents](https://github.com/annabd351/UnrealTechArt/tree/main/Documents)

