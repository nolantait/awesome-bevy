# Awesome Bevy

This is an awesome list maintained by https://taintedcoders.com.

Only resources that are up to date with at least `0.15` Bevy will be included.

## Table of contents

- [Resources](#resources)
- [Starters](#starters)
- [Open Source Projects](#open-source-games)
- [Animation](#animation)
- [Assets](#assets)
- [Audio](#audio)
- [Code organization](#code-organization)
- [Editor and Workflow](#editor)
- [Graphics and Rendering](#graphics-and-rendering)
- [Input](#input)
- [Misc](#misc)
- [Networking](#networking)
- [Pathfinding](#pathfinding)
- [Physics](#physics)
- [UI](#ui)

## Resources

- [Tainted Coders](https://taintedcoders.com)
- [Unofficial Bevy Cheatbook](https://bevy-cheatbook.github.io/)
- [Simple Bevy Tutorial](https://github.com/fogarecious/bevy_tutorial/tree/main):
  Breaks the version rule above but still great content
- [Roguelike Tutorial - In Rust](https://bfnightly.bracketproductions.com/): Not
  quite bevy but an awesome read, lots of crossover

## Starters

- [Tainted Coders - Bevy Starter](https://github.com/nolantait/bevy-starter)
- [TheBevyFlock - `bevy_new_2d`](https://github.com/TheBevyFlock/bevy_new_2d/tree/main)
- [`bevy_space`](https://github.com/perlindgren/bevy-space)
- [`bevy_quickstart`](https://github.com/TheBevyFlock/bevy_quickstart)
- [`bevy_game_template`](https://github.com/NiklasEi/bevy_game_template)
- [`bevy_github_ci_template`](https://github.com/bevyengine/bevy_github_ci_template)
- [`limitpush`](https://github.com/heydocode/limitpush)

## Open Source Projects

Not all resources in this section will be up to date but are useful nonetheless

- [Emergence](https://github.com/leafwing-studios/emergence?tab=readme-ov-file)
- [Digial Extinction](https://github.com/DigitalExtinction/Game)
- [Riverbed](https://github.com/Inspirateur/riverbed)
- [Power](https://github.com/Kevenpvp/Power)
- [SolarSim](https://github.com/jan-tennert/SolarSim)
- [Taipo](https://github.com/rparrett/taipo)

## Assets

- [`bevy_asset_loader`](https://github.com/NiklasEi/bevy_asset_loader): Bevy plugin helping with asset loading and organization
- [`bevy_rpack`](https://github.com/Leinnan/rpack)`: Create tilemaps in seconds!
- [`skein`](https://github.com/rust-adventure/skein): Convert glTF extras to Bevy Components using reflection
- [`bevy_app_compute`](https://github.com/Kjolnyr/bevy_app_compute): An easy way to run wgpu compute shaders within a bevy app
- [`bevy_march`](https://github.com/NiseVoid/bevy_march): A ray marcher for bevy, which can function alongside the regular mesh-based rendering
- [`bevy_materialize`](https://github.com/Noxmore/bevy_materialize): Load, store, and apply type-erased materials in Bevy

## Audio

- [`bevy_fmod`](https://github.com/Salzian/bevy_fmod): Idiomatic integration of the FMOD audio engine into Bevy projects

## Animation

- [`bevy_animation_graph`](https://github.com/mbrea-c/bevy_animation_graph): Animation graphs in Bevy
- [`bevy_lookup_curve`](https://github.com/villor/bevy_lookup_curve): Editable lookup curve for Bevy
- [`bevy_magic_fx`](https://github.com/ethereumdegen/bevy_magic_fx): Define mesh-based VFX in RON files and load them into bevy

## Code Organization

- [`seldom_state`](https://github.com/Seldom-SE/seldom_state): Component-based state machine plugin for Bevy. Useful for AI, player state, and other entities that occupy different states.
- [`bevy_cli`](https://github.com/TheBevyFlock/bevy_cli): A prototype Bevy CLI tool intended to streamline common tasks when working on projects.
- [`bevy_behave`](https://github.com/RJ/bevy_behave): Behaviour trees for bevy, with on-demand entity spawning for task nodes
- [`bevy_flurx`](https://github.com/not-elm/bevy_flurx): Allows you to use coroutine in Bevy
- [`bevy_save`](https://github.com/hankjordan/bevy_save): A framework for saving and loading application state in Bevy
- [`beet`](https://github.com/mrchantey/beet): Tools for developing reactive structures in rust

## Editors and Workflow

- [`blenvy`](https://github.com/kaosat-dev/Blenvy): Bevy Code & Blender addon for a simple workflow to add & edit Bevy components in Blender
- [`skein`](https://github.com/rust-adventure/skein): Convert glTF extras to Bevy Components using reflection
- [`bevy_mod_scripting`](https://github.com/makspll/bevy_mod_scripting/): Bevy Scripting Plugin
- [`bevy_mod_outline`](https://github.com/komadori/bevy_mod_outline): a Bevy plugin for drawing outlines around meshes using the vertex extrusion and jump flood methods
- [`bevy_trenchbroom`](https://github.com/Noxmore/bevy_trenchbroom): Quake map editor, TrenchBroom integration, .map, and .bsp loading for Bevy 
- [`bevy_mod_debugdump`](https://github.com/jakobhellermann/bevy_mod_debugdump): Dump your schedules for visual inspection

## Graphics and Rendering

- [`bevy_hanabi`](https://github.com/djeedai/bevy_hanabi): a GPU particle system plugin for the Bevy game engine
- [`bevy_third_person_camera`](https://github.com/The-DevBlog/bevy_third_person_camera): A third person camera crate written for Bevy
- [`bevy_vello`](https://github.com/linebender/bevy_vello): An integration to render with Vello in the Bevy game engine
- [`bevy_vulkan`](https://github.com/HugoPeters1024/bevy_vulkan): Vulkan RTX rendering backend for the Bevy game engine written in Rust

## Input

- [`leafwing-input-manager`](https://github.com/Leafwing-Studios/leafwing-input-manager): A straightforward stateful input manager for the Bevy game engine. This library is being upstreamed into Bevy
- [`bevy_pancam`](https://github.com/johanhelsing/bevy_pancam): A bevy plugin for panning orthographic cameras
- [`bevy_enhanced_input`](https://github.com/projectharmonia/bevy_enhanced_input): Dynamic and contextual input mappings for Bevy
- [`bevy_ui_text_input`](https://github.com/ickshonpe/bevy_ui_text_input): Text input crate for Bevy UI using cosmic text

## Networking

- [`lightyear`](https://github.com/cBournhonesque/lightyear): A library for writing server-authoritative multiplayer games with Bevy
- [`bevy_replicon`](https://github.com/projectharmonia/bevy_replicon): Server-authoritative networking crate for the Bevy game engine
- [`bevy_renet`](https://github.com/lucaspoffo/renet/tree/master/bevy_renet): A Bevy Plugin for the renet crate. A network crate for Server/Client with cryptographically secure authentication and encypted packets. Designed for fast paced competitive multiplayer games
- [`renet2`](https://github.com/UkoeHB/renet2/): Renet2 is a network library for Server/Client games written in rust. It is focused on fast-paced games such as FPS, and competitive games
- [`bevy_rewind`](https://github.com/NiseVoid/bevy_rewind): Server-authoritative rollback networking for bevy
- [`bevy_oxr`](https://github.com/awtterpip/bevy_oxr): A crate for adding openxr (and in the future webxr) support to Bevy
- [`bevy_streaming`](https://github.com/rlamarche/bevy_streaming): Bevy Streaming for Cloud Gaming through WebRTC

## Misc

- [`big_space`](https://github.com/aevyrie/big_space): Floating origin plugin for spaces larger than the universe
- [`bevy_mod_raycast`](https://github.com/aevyrie/bevy_mod_raycast/): A little mesh raycasting plugin for Bevy
- [`bevy_play_card`](https://github.com/Rabbival/bevy_play_card): A card crate for the Bevy game engine
- [`bevy_serialization_extras`](https://github.com/rydb/bevy_serialization_extras): Contains plugins/systems to make serialization/deserialization with bevy smoother
- [`bevy_shuffle_bag`](https://github.com/janhohenheim/bevy_shuffle_bag): A tiny crate providing a shuffle bag, which is a collection of items that can endlessly be picked in a random, nonrepeating order.

## Physics

- [`avian`](https://github.com/Jondolf/avian): ECS-driven 2D and 3D physics engine for the Bevy game engine
- [`bevy_rapier`](https://github.com/dimforge/bevy_rapier): Official Rapier plugin for the Bevy game engine
- [`bevy_heavy`](https://github.com/Jondolf/bevy_heavy): Mass properties for Bevy's geometric primitives.
- [`bevy_transform_interpolation`](https://github.com/Jondolf/bevy_transform_interpolation): Transfom interpolation for fixed timesteps for the Bevy game engine
- [`avian_pickup`](https://github.com/janhohenheim/avian_pickup): A plugin for implementing picking up dynamic rigid bodies in Avian physics for the Bevy engine

## Pathfinding

- [`vleue_navigator`](https://github.com/vleue/vleue_navigator): Pathfinding on NavMeshes for Bevy
- [`bevy_flowfield_tiles_plugin`](https://github.com/BlondeBurrito/bevy_flowfield_tiles_plugin): Bevy plugin for Flowfield based pathfinding

## UI

- [`bevy_egui`](https://github.com/mvlabat/bevy_egui): An immediate mode UI library
- [`bevy_lunex`](https://github.com/bytestring-net/bevy_lunex): Blazingly fast path based retained layout engine for Bevy entities, built around vanilla Bevy ECS
- [`bevy_cosmic_edit`](https://github.com/StaffEngineer/bevy_cosmic_edit): Multiline text editing for bevy apps
- [`bevy_cobweb_ui`](https://github.com/UkoeHB/bevy_cobweb_ui): Reactive UI framework for Bevy
- [`haalka`](https://github.com/databasedav/haalka): Ergonomic reactive Bevy UI library powered by FRP signals
- [`i-cant-believe-its-not-bsn`](https://github.com/Leafwing-Studios/i-cant-believe-its-not-bsn): Early preview of Cart's vision of BSN
- [`bevy_plot`](https://github.com/eliotbo/bevy_plot): Plotting library for the Bevy game engine
- [`transform-gizmo`](https://github.com/urholaukkarinen/transform-gizmo): 3d transformation gizmo
- [`bevy_rich_text3d`](https://github.com/mintlu8/bevy_rich_text3d): Mesh based bevy text implementation
- [`bevy_healthbar_3d`](https://github.com/sparten11740/bevy_health_bar3d): Health bar for bevy implemented as a billboard shader
- [`bevy_ui_anchor`](https://github.com/TotalKrill/bevy_ui_anchor): Microlibrary for adding anchoring to UI
