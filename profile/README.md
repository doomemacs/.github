> [!CAUTION]
> **`doomemacs.com` is not associated with nor endorsed by this project!**
> `doomemacs.org` is our one and only domain. [Read our announcement about it
> here](https://github.com/orgs/doomemacs/discussions/129).

-----

[![Discord Server](https://img.shields.io/discord/406534637242810369?color=738adb&label=Discord&logo=discord&logoColor=white&style=flat-square)][discord]
[![Github Discussions](https://img.shields.io/github/discussions/doomemacs/community?label=Discussions&logo=github&style=flat-square)][discuss]
[![Support the project](https://img.shields.io/badge/Support-the%20project-d5649f?style=flat-square&logo=github-sponsors)](#heart-support-the-project)

<a href="http://ultravioletbat.deviantart.com/art/Yay-Evil-111710573">
  <img src="https://raw.githubusercontent.com/doomemacs/doomemacs/screenshots/cacochan.png" align="right" />
</a>

> It's a tale as old as time: a stubborn, shell-dwelling, and melodramatic
> vimmer -- tormented by Vimscript and his boundless productivity -- makes a
> formal request to the netherworld for a transfer. They agree. The terms? He
> must lure more unsuspecting souls into a life of eternal bikeshedding. Now he
> runs the place.

Doom Emacs is an Emacs Lisp development tool and configuration framework for
[GNU Emacs][emacs], tailored for Emacs enthusiasts that want a faster, more
reliable, and reproducible foundation for their next config or elisp project, or
for beginners who want a softer introduction to our favorite operating system.


## Quick start

### Install

``` sh
git clone --depth 1 https://github.com/doomemacs/core ~/.config/emacs   # or ~/.emacs.d
~/.config/emacs/bin/doom install
```

This is the quickest way to get a Doom environment up and running. Visit our
[getting started guide][getting-started] for more in-depth instructions.

### Updating

``` sh
~/.config/emacs/bin/doom upgrade
```

If this fails, see `doom upgrade --help` for steps to manually update Doom.


## Prerequisites
- GNU Emacs 27.1–31.1 **(31.1 is recommended)**
  - Using only Doom's CLI requires 27.1+
  - Using Doom as a starter kit requires 29.1+
- Git >= 2.23
- Ripgrep >= 11.0
- **Emacs Dependencies:**
  - GNU variants of `find`, `ls`, `diff`, and `tar`
  - Symbola font (Emacs' fallback font for glyphs it can't display)
- **Optional, but recommended:**
  - [fd] 7.3.0+ (used to improve file indexing performance)
  - "Symbols" Nerd Font (optional — GUI only): Doom uses this font to display
    icons. Linux users can install it via their OS package manager or from
    within Doom Emacs via ~M-x nerd-icons-install-font~. Windows and MacOS users
    will need to manually install the font from
    [nerdfonts.com](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/NerdFontsSymbolsOnly.zip).
    Alternatively, you can use one of the many patched Nerd Fonts as your
    primary font in Emacs.

> [!WARNING]
> **Avoid unstable and pre-release builds of Emacs.** These end in `.50`, `.60`,
> or `.9X` (e.g. `28.1.91`). Doom should generally work on Emacs HEAD (the
> maintainer dogfoods it), but support lags behind the bleeding edge by at least
> a month or so.
 
> [!IMPORTANT]
> Many of [Doom's modules](https://github.com/doomemacs/modules) have their own
> dependencies. Visit their README.org for instructions on how to acquire them
> (accessible within Doom Emacs via `M-x doom/help-modules` too). Running `$
> doom doctor` in the shell will summarize what dependencies you're missing (and
> diagnose any common issues with your environment).


## Project resources

- [doomemacs.org](https://doomemacs.org) (WIP)
- [docs.doomemacs.org](https://docs.doomemacs.org) (WIP)
- [wiki.doomemacs.org](https://wiki.doomemacs.org) (WIP)
- [discuss.doomemacs.org][discuss] -- Github discussions board
- [discord.doomemacs.org][discord] -- Discord server
- [Announcements](https://doomemacs.org/news)
- [Project roadmap](https://doomemacs.org/roadmap) (WIP)
- [Do-Not-PR list](https://doomemacs.org/donotpr)
- [Packages under review](https://doomemacs.org/package-review)


### Frequently asked questions

- [Common issues](https://doomemacs.org/projects/2/views/34)
- [About the project](https://doomemacs.org/faq) (WIP)
- [About the community](https://git.doomemacs.org/community/#frequently-asked-questions)


### Social media

- https://youtube.com/@doomemacs
- https://fosstodon.org/@doomemacs
- https://twitter.com/doomemacs (mirrored from fosstodon)
- https://bsky.app/profile/doomemacs.bsky.social (mirrored from fosstodon)


## :heart: Support the project

Doom and its community are labors of love and the incurable madness of its
maintainer and volunteers. Doom wouldn't be where it is today without your help.
Help us keep the lights on by:

- [Contributing bug reports, code, or documentation](https://github.com/doomemacs/community/docs/become-a-contributor.md)
- [Adding to, polishing, or translating our community wiki](https://wiki.doomemacs.org).
- Joining the Doom Emacs community as:
  - [A core or module maintainer](https://github.com/doomemacs/community/docs/become-a-maintainer.md),
  - [a moderator](https://github.com/doomemacs/community/docs/become-a-moderator.md),
  - or [a community regular](https://github.com/doomemacs/community/docs/become-a-regular.md),
- [Sponsoring the author](https://doomemacs.org/sponsor).


[discord]: https://discord.doomemacs.org
[discuss]: https://discuss.doomemacs.org
[emacs]: https://www.gnu.org/software/emacs/
[support]: https://doomemacs.org/sponsor
[getting-started]: https://github.com/doomemacs/core/blob/master/docs/getting_started.org#install
