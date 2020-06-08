# PortaPack Mayhem

[![Build Status](https://travis-ci.com/eried/portapack-mayhem.svg?branch=master)](https://travis-ci.com/eried/portapack-mayhem) [![buddy pipeline](https://app.buddy.works/eried/portapack/pipelines/pipeline/252276/badge.svg?token=48cd59d53de0589a8fbe26bc751d77a59a011cf72581da049343879402991c34 "buddy pipeline")](https://app.buddy.works/eried/portapack/pipelines/pipeline/252276) [![CodeScene Code Health](https://codescene.io/projects/8381/status-badges/code-health)](https://codescene.io/projects/8381) [![Docker Hub Pulls](https://img.shields.io/docker/pulls/eried/portapack.svg)](https://hub.docker.com/r/eried/portapack)

This is a fork of the [Havoc](https://github.com/furrtek/portapack-havoc/) firmware, which itself was a fork of the [PortaPack](https://github.com/sharebrained/portapack-hackrf) firmware, an add-on for the [HackRF](http://greatscottgadgets.com/hackrf/). A fork is a derivate, in this case one that has extra features and fixes when compared to the older versions.

[<img src="https://raw.githubusercontent.com/wiki/eried/portapack-mayhem/img/hw_overview_h2_front.png" height="400">](https://github.com/eried/portapack-mayhem/wiki/Hardware-overview) [<img src="https://raw.githubusercontent.com/wiki/eried/portapack-mayhem/img/hw_overview_h2_inside.png" height="400">](https://github.com/eried/portapack-mayhem/wiki/Hardware-overview#portapack-internals)

*[PortaPack H2](https://s.click.aliexpress.com/e/_dSMPvNo) (clone) with a custom [3d printed case](https://github.com/eried/portapack-mayhem/wiki/H2-Enclosure)*

# FAQ

This repository expands upon the previous work by many people and aims to constantly add new features, bugfixes and generate documentation to make further development easier.  In a project such as this [collaboration](https://github.com/eried/portapack-mayhem/wiki/How-to-collaborate) is always welcomed and appreciated.

To clarify any basic questions, please read the following common ones:

## Does it work on H1/H2 PortaPack?

Yes, both devices are the [same](https://github.com/eried/portapack-mayhem/wiki/First-steps). The one I am using to test all changes is this [Portapack H2+HackRF+battery](https://s.click.aliexpress.com/e/_dSMPvNo), which is a kit that includes everything you need. Sadly, the people making the H2 never made the updated schematics available, which is not ideal (and goes against the terms of the license).

To support the people behind the hardware, please buy a genuine [HackRF](https://greatscottgadgets.com/hackrf/) and [PortaPack](https://store.sharebrained.com/products/portapack-for-hackrf-one-kit).

## Where is the latest firmware?

The current stable release is on the [Release](https://github.com/eried/portapack-mayhem/releases/latest) page. Follow the instructions you can find in the release description. There is also [nightly builds](https://github.com/eried/portapack-mayhem/releases/tag/nightly) generated frequently which have the latest features but may contain incomplete or buggy functionality (at  least until the bug is found!).

## Is this the newest firmware for my PortaPack? 
Most probably: **YES**. *If you find new features somewhere else, please [suggest](https://github.com/eried/portapack-mayhem/issues/new/choose) them*.

## Which one is actually the newest?
There is a lot of confusion of which is the latest version because no old version used any actual "version number". Additionally, since the files were distributed on facebook groups, github issue links and similar temporal sources, then there was no central location for them. 

This fork (**Mayhem**) uses *major.minor.release* [semantic versioning](https://en.wikipedia.org/wiki/Software_versioning), so you can always compare your current version with the latest from [Releases](https://github.com/eried/portapack-mayhem/releases/latest).

## What about Havoc/GridRF/jamesshao8/jboone's?
* jboone's PortaPack: the [vanilla](https://en.wikipedia.org/wiki/Vanilla_software) experience
* Havoc: It was the most popular fork of jboone's PortaPack, currrently it in Archive status so it is not being developed
* jamesshao8: He keeps his own version of the fork, while not attached as a fork to anything
* GridRF: They sell PortaPack clones with their own firmware based on a old version, which has no sourcecode available

## How can I collaborate
You can write [documentation](https://github.com/eried/portapack-mayhem/wiki), fix bugs and [answer issues](https://github.com/eried/portapack-mayhem/issues) or add new functionality. Please check the following [guide](https://github.com/eried/portapack-mayhem/wiki/How-to-collaborate) with details.

Consider that the hardware and firmware has been created and maintain by a [lot](https://github.com/mossmann/hackrf/graphs/contributors) of [people](https://github.com/eried/portapack-mayhem/graphs/contributors), so always try colaborating your time and effort first. 

As a last option, if you want to send money directly to me for getting more boards, antennas and such:

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CBPQA4HRRPJQ6&source=url)

## What if I need help?
First, check the [documentation](https://github.com/eried/portapack-mayhem/wiki). If you find a bug or you think the problem is related to the current repository, please open an [issue](https://github.com/eried/portapack-mayhem/issues/new/choose).

You can reach the [official community](https://www.facebook.com/groups/177623356165819) in Facebook. 

## What if I find incongruencies, or grammatical errors in the text?
If is on the [Wiki](https://github.com/eried/portapack-mayhem/wiki), you can modify it directly. If is on files of the repository, you can send corrections as [pull requests](https://github.com/eried/portapack-mayhem/wiki/How-to-collaborate#coding-new-stuff-or-fixing-bugs). As a last resource, open an [issue](https://github.com/eried/portapack-mayhem/issues/new/choose).
