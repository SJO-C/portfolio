---
# [str] Title of the project. This is also visible when hovering over a gallery item.
title: "NixOS"
# [str] Optional subtitle of the project. 
#   Functions as an additional explanation when hovering over a gallery item (comment out the following line).
subtitle: "Ask Me about NixOS"
# [date] Project publication date.
#   Changes order: The newest item will be displayed first in the gallery. 
#   Just like Hugo's natural ordering, this is anti-chronological.
#   You can use 'weight' to order (primarily) for more control (sometimes it makes sense to put old items before new ones).
#   The specifics are documented here: https://gohugo.io/templates/lists/#order-content
date: "2024-09-11T18:00:22+01:00"
# [str] Gallery image file from the assets directory. 
image: "images/nixos.png"
# [str] Alternative (image) description.
alt: ""
# [css] Optional background color of the gallery item (if omitted, will use theme's fallback).
color: "#fff"
# [css] Optional gallery item hover color (if omitted, will use theme's fallback).
#hoverColor: "#fff"
# [map] Configure github specific options here:
# github: 
    # [str] Repo is a combination of "<user_or_org>/<repository_name>"
    # repo: "SJO-C/nixos"
    # [bool] Show repository information such project language below the buttons.
    # showInfo: true
    # showButtons: true
# [map] Optionally configure terminal to be displayed when opening up the gallery item:
#   Example (set "useTermynal" to true in config.yaml and comment out to test it):
# terminal:
    # lines:
    # - type: input
    #   data: hugo mod get -u github.com/hugo-mods/lazyimg 
    #   wait: 1250
    # - type: progress
    #   data: 100
    #   wait: 200
    # - data: ✓ Done.
    #   wait: 75
    # - data: exit
    #   wait: 75
# buttons:
#   - i18n: view # i18n key (see i18n directory, see https://gohugo.io/functions/i18n/)
#     icon: view # optional: use an icon from icons.yaml
#     newTab: false # optional: controls if url should be opened in new tab
#     url: ""
#   - i18n: code 
#     icon: code
#     url: ""
# [bool] Draft mode will decide if file will be published to 'public/' directory.
draft: true
---
As with LaTeX, I found out about NixOS during a Wikipedia Binge, and decided to try it as I have been vaguely involved in the Linux Desktop scene for about 11 Years.  As such, the idea of a Functional Paradigm based Package Management System was certainly interesting, and since I had recently fubar'd my Ubuntu Install (due to not understanding DKMS modules and the fact that ZFS on Ubuntu was reliant on them), I thought I'd give NixOS a try.

