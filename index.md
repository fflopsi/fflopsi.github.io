---
layout: default
title: About me / @fflopsi
---

# Welcome!

## About me

My name is Florian and I am a 21-year-old hobby coder based in Switzerland. Since about 2016, I've been teaching myself how to code.

The main languages I've been learning are Python and Java, and more recently, Kotlin and R. I've also looked into many other languages like Shell/Bash, LaTeX, C/C++, C#, SQL, Nix, HTML/CSS/JavaScript/TypeScript, Dart, etc.

I'm currently studying physics at ETH Zurich, and thus do not have that much time to code for myself. As a result, many of my projects have not been updated recently.

## Some projects

Here's some information about my projects that are available on [my GitHub](https://github.com/fflopsi):

### Tournaments

Tournaments is an Android app built with [Jetpack Compose](https://developer.android.com/jetpack/compose) for managing croquet tournaments with multiple players and multiple games per tournament. I'm currently converting this to a [Compose Multiplatform](https://www.jetbrains.com/lp/compose-multiplatform/) project. More information about it can be found [here](/tournaments).

### ArchCustomization

Just a simple collection of some Bash scripts to customize an [EndeavourOS](https://endeavouros.com) / [Arch Linux](https://archlinux.org) installation to my liking, e.g. installing some packages, theming and customizing [Gnome](https://www.gnome.org/) and installing some [extensions](https://extensions.gnome.org/), some configuration, etc. All these scripts can be found [here](https://github.com/fflopsi/arch-customization).

### NixOS Config

Since I do not have much time to fiddle with my system during my studies, I switched from Arch/EndeavourOS (see above) to [NixOS](https://nixos.org/) to better orrganize my system configuration. I simply uploaded the [flake](https://nixos.wiki/wiki/Flakes) and all the files necessary (system configuration and some [home-manager](https://nix-community.github.io/home-manager/) files) to rebuild my systems to [this repo](https://github.com/fflopsi/nixos-config/).

### TwoBodyProblem

This was my matriculation project (project at the end of Swiss high school). It is a simulation of the gravitational [two-body problem](https://en.wikipedia.org/wiki/Two-body_problem), written in Python with [VPython](https://vpython.org). You can adjust options to define how the simulation looks/works and values to define the physical properties of the two bodies. The simulation itself can be found [here](https://github.com/fflopsi/twobodyproblem), a graphical utility for entering the options and values is available [here](https://github.com/fflopsi/twobodyproblem-gui).

### WorldUtils

WorldUtils is a [Minecraft](https://www.minecraft.net/en-us) [Spigot](https://www.spigotmc.org) plugin containing some handy utilities for your Minecraft server, i.e. saving and viewing global and personal positions, sending your positions to other players, controlling a global and personal timer and resetting the whole world/server. The plugin can be found [here](https://github.com/fflopsi/worldutils).

WorldUtils Projects is an extension to WorldUtils and contains some long-term Minecraft projects. At the moment, there is only one: AllItems, whith the objective to collect all obtainable items in the game. This plugin is available [here](https://github.com/fflopsi/worldutils-projects).

## Repositories

All the links to my repositories with descriptions:

{% for repository in site.github.public_repositories %}
  - [{{ repository.name }}]({{ repository.html_url }}): {% if repository.archived %}**(Archived)** {% endif %}{{ repository.description }}
{% endfor %}

---

*[View on GitHub](https://github.com/fflopsi/fflopsi.github.io)*
