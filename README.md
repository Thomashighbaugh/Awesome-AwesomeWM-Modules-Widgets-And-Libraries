# Awesome AwesomeWM Widgets, Libraries and Modules

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
<br>

<img align="left" width="28%" src="assets/awesome-logo2.svg"  alt="stylized awesome logo">
<img align="left" width="28%" src="assets/awesome-logo3.svg"  alt="stylized awesome logo">
<img align="left" width="28%" src="assets/awesome-logo5.svg"  alt="stylized awesome logo">

- [Awesome AwesomeWM Widgets, Libraries and Modules](#awesome-awesomewm-widgets-libraries-and-modules)
  - [Introduction](#introduction)
  - [Terminology and Rules](#terminology-and-rules)
  - [Configuration Related](#configuration-related)
    - [Widget Libraries](#widget-libraries)
    - [Projects that Ease Configuration](#projects-that-ease-configuration)
    - [Configuration Transpilers](#configuration-transpilers)
  - [Window Mangement](#window-mangement)
    - [Tag Management](#tag-management)
    - [Focus & Client Navigation](#focus--client-navigation)
    - [Dropdown Clients](#dropdown-clients)
    - [Client Window Geometry](#client-window-geometry)
    - [Layouts](#layouts)
  - [Environment and System Related](#environment-and-system-related)
    - [Session Related](#session-related)
    - [Tmux Integration](#tmux-integration)
    - [Multimedia](#multimedia)
    - [Laptop Specific](#laptop-specific)
    - [Networking](#networking)
    - [Optical Health](#optical-health)
  - [Keyboard Related](#keyboard-related)
    - [Caps Lock Widgets](#caps-lock-widgets)
    - [Modal Key Binding](#modal-key-binding)
  - [User Interface Related](#user-interface-related)
    - [Animations](#animations)
    - [Notifications](#notifications)
    - [Wibar Related](#wibar-related)
    - [Client Decorations](#client-decorations)
    - [Menu](#menu)
  - [Other Awesome Lists Related to AwesomeWM](#other-awesome-lists-related-to-awesomewm)

<!-- /TOC -->

## Introduction

This list provides the user with a central point with which to find various third party projects that may be used in one's Awesome Window Manager configuration I have compiled in my bouts of obsessive research into the topic and unfortunately no other active list enumerates to this degree.

My hope is that this will be of service to those new to the community customizing the interface of their open source desktop, which they will then enrich the community by making their implementation available to the rest of us and share on the larger ricing community's central gathering place `r/unixporn` in the form of a screenshot with a link to the associated repository the screenshot was derived from.

I have definitely missed something somewhere along the line, and have categorized the below in an ineffcient manner I am open to adjusting, thus **welcome contributions in the form of issues, pull requests and anything else the interested parties would be so kind to contribute to this collection**! So please don't be shy, the community is sustained by your contributions.

## Terminology and Rules

Within the context of the ricing community that customizes Awesome Window Manager specifically, it seems there is a high degree of variablity in what is a widget and a module such that a meaningful discussion is not possible based on the implementations that can be found and thus one is not drawn in the list below other than libraries, which are collections of widgets and modules. How the user interacts with them in utilizing them within their configurations is specific to each and will require consulting with their documentation for more information, often available through the project's `README.md` file.

Other than libraries, I have categorized the resources below in terms of their functionality, general and specific, to provide a taxonomy that I hope steers users towards resources conforming to their wants and needs in a way that they can easily appreciate. If any confusion exists on the part of interested third parties as to this taxnomy, if the user notices I missed a resource or were anyone in possession of a better means of organizing this information, I encourage the opening of an issue and I will respond to the best of my ability to their inquiry as I am able.

### The Rules

Included projects are those that are functionality of varying sorts that is intended to be included in a configuration of Awesome Window Manager without being configurations themselves (which I am working on a separate list for that is a lot harder to categorize). I have opted to include older projects conforming to this criteria as even if their functionality is deprecated, they often provide examples of implementations of Lua code interacting with the AwesomeWM API that may be instructive in solving one's own needs. This is a deliberately wide net being cast, such as to include the incredible diversity of options available for use in configuring AwesomeWM and give users a sense of the wide range of possibilities uniquely enabled by this particular software.

> "tl;dr give me the goods already!"

Here they are:

## Configuration Related

### Widget Libraries

- [awesome-away](https://github.com/shmilee/awesome-away)
- [awesome-buttons](https://github.com/streetturtle/awesome-buttons)
- [awesome-glorious-widgets](https://github.com/manilarome/awesome-glorious-widgets)
- [awesome-widgets](https://github.com/WillPower3309/awesome-widgets)
- [awesome-wm-widgets](https://github.com/streetturtle/awesome-wm-widgets) \* community favorite
- [awesome-zen](https://github.com/atsepkov/awesome-zen)
- [bling](https://github.com/BlingCorp/bling) \* community favorite
- [cribbed](https://github.com/duckwork/cribbed)
- [fainty](https://github.com/vladimir-g/fainty)
- [Gobo Awesome](https://github.com/gobolinux/gobo-awesome)
- [obvious](https://github.com/hoelzro/obvious)
- [radical](https://github.com/Elv13/radical)
- [vicious](https://github.com/vicious-widgets/vicious)

### Projects that Ease Configuration

- [Awesome Awesome RC](https://github.com/suconakh/awesome-awesome-rc)
- [awesome-ezconfig](https://github.com/gvalkov/awesome-ezconfig)
- [awmtt](https://github.com/serialoverflow/awmtt) \*important for beginners!
- [carrot](https://github.com/pouyanh/carrot)
- [noobie](https://github.com/streetturtle/noobie)
- [repetitive](https://github.com/Elv13/repetitive)

### Configuration Transpilers

- [awesomewm.ts.d](https://github.com/saksmt/awesomewm.d.ts) \* for typescript
- [friar](https://github.com/shtwzrd/friar) \* for fennel

<hr>
<!-- ---------------------------------------------- -->
<!-- ---------------------------------------------- -->
<!-- ---------------------------------------------- -->

## Window Mangement

### Tag Management

- [awesome-sharedtags](https://github.com/Drauthius/awesome-sharedtags)
- [awesome_tagdrag](https://github.com/jorenheit/awesome_tagdrag)
- [awesome infinite](https://github.com/8ware/awesome-infinite)
- [awesome-retain](https://github.com/Veratil/awesome-retain)
- [tyrannical](https://github.com/Elv13/tyrannical)

### Focus & Client Navigation

- [collision](https://github.com/Elv13/collision)
- [awesome-micky](https://github.com/basaran/awesomewm-micky)
- [awesomewm-backham](https://github.com/basaran/awesomewm-backham)
- [awesome-switcher](https://github.com/berlam/awesome-switcher)
  - [awesome-switcher](https://github.com/troglobit/awesome-switcher)
- [awesome_alttab](https://github.com/jorenheit/awesome_alttab)
- [awesome-revelation](https://github.com/bioe007/awesome-revelation)

### Dropdown Clients

- [awesome-handy](https://github.com/crater2150/awesome-handy)
- [awesome-scratch](https://github.com/notnew/awesome-scratch)

### Client Window Geometry

- [awesome-remember-geometry](https://github.com/basaran/awesome-remember-geometry)

### Layouts

- [awesome_floattile](https://github.com/jorenheit/awesome_floattile)
- [awesome-frames](https://github.com/notnew/awesome-frames)
- [awesome-overlap](https://github.com/sebth/awesome-overlap)
- [layout-machi](https://github.com/xinhaoyuan/layout-machi)
  - [awesomewm-machina](https://github.com/basaran/awesomewm-machina)
    <!-- ---------------------------------------------- -->
    <!-- ---------------------------------------------- -->
    <!-- ---------------------------------------------- -->
    <hr>

## Environment and System Related

### Session Related

- [gobo-awesome-screenlock](https://github.com/gobolinux/gobo-awesome-screenlock)
- [awesome-wallpaper](https://github.com/JavaCafe01/awesome-wallpaper)

### Tmux Integration

- [awesome-termgrp](https://github.com/wheatdog/awesome-termgrp)
- [awesomewm-vim-tmux-navigator](https://github.com/intrntbrn/awesomewm-vim-tmux-navigator)

### Multimedia

- [awesome-pa-utility](https://github.com/lealoureiro/awesome-pa-utility)
- [awesome-pulseaudio_widget](https://github.com/stefano-m/awesome-pulseaudio_widget)
- [alsa-volume-monitor](https://github.com/gch1p/alsa-volume-monitor)

### Laptop Specific

- [xplugd](https://github.com/troglobit/xplugd)
- [awesome_batterywidget](https://github.com/jorenheit/awesome_batterywidget)
- [awesome-upower-battery](https://github.com/berlam/awesome-upower-battery)
- [awesome-light](https://github.com/troglobit/awesome-light)

### Networking

- [awesome-connman_widget](https://github.com/stefano-m/awesome-connman_widget)
- [net_widgets](https://github.com/pltanton/net_widgets)

### Optical Health

- [awesome-redshift](https://github.com/troglobit/awesome-redshift)

    <!-- ---------------------------------------------- -->
  <!-- ---------------------------------------------- -->
  <!-- ---------------------------------------------- -->
    <hr/>

## Keyboard Related

- [keyboard_layout](https://github.com/echuraev/keyboard_layout)

### Caps Lock Widgets

- [awesomewm-capslock_widget](https://github.com/iacchus/awesomewm-capslock-widget)
- [awesomewm-capslock_widget](https://github.com/stefano-m/awesome-capslock_widget)

### Modal Key Binding

- [awesome-modalbind](https://github.com/crater2150/awesome-modalbind)
- [modalawesome](https://github.com/potamides/modalawesome)

<hr>
<!-- ---------------------------------------------- -->
<!-- ---------------------------------------------- -->
<!-- ---------------------------------------------- -->
## User Interface Related

### Animations

- [awesome-AnimationFramework](https://github.com/Aire-One/awesome-AnimationFramework)
- [awestore](https://github.com/K4rakara/awestore)
- [rubato](https://github.com/andOrlando/rubato)

### Notifications

- [AwesomeWM Memory Notifier plug-in](https://github.com/macunha1/awesomewm-memory-notifier)

### Wibar Related

- [bar](https://github.com/wezm/bar)
- [fenetre](https://github.com/cool-cool-sweat/fenetre)
- [icon_customizer](https://github.com/intrntbrn/icon_customizer)

### Client Decorations

- [color](https://github.com/andOrlando/color)
- [awesomePalettes](https://github.com/nivalderramas/awesomePalettes)
- [nice](https://github.com/mut-ex/awesome-wm-nice)
- [smart_borders](https://github.com/intrntbrn/smart_borders)

### Menu

- [awesomewm-app-drawer](https://github.com/nwdamgaard/awesomewm-app-drawer)
- [awesome-freedesktop](https://github.com/lcpz/awesome-freedesktop) \*community favorite
- [awesome-appmenu](https://github.com/montagdude/awesome-appmenu)

<hr/>

## Other Awesome Lists Related to AwesomeWM

- [Awesome AwesomeWM](https://github.com/atsepkov/awesome-awesome-wm)
