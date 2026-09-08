<div align="center">

<img src="https://scrobblewall.com/img/icon.png" width="72" alt="">

# ScrobbleWall

**Turn your Last.fm listening history into desktop wallpapers.**
Free, for Windows 10 and 11. Use your public Last.fm profile. No password required.

[Download 1.4](https://github.com/ijlsadleir/scrobblewall/releases/latest) ·
[Website](https://scrobblewall.com/) ·
[What's new](https://scrobblewall.com/whats-new/) ·
[Español](https://scrobblewall.com/es/)

</div>

<br>

<img src="https://scrobblewall.com/img/hero.jpg" alt="A desktop wallpaper showing an album cover on the right and the artist name on the left">

<br>

## What it is

Most tools in this space make you a grid of your top albums, once, and then
you set it as your wallpaper by hand. ScrobbleWall reads your Last.fm profile
and **draws wallpapers itself**, at your screen's resolution, then keeps
rotating them on a timer. You type a username and close the window.

ScrobbleWall builds each wallpaper from your listening history. You can add an animated backdrop, including your own video. For interactive web backgrounds and other wallpaper types, see the [comparison with Lively Wallpaper](https://scrobblewall.com/vs-lively-wallpaper/).

## Twelve kinds of wallpaper

A listening history holds more than a ranking, so the rotation is not one
picture that updates:

| | |
|---|---|
| **Playing right now** | The cover of what you are listening to, interrupting the rotation while it plays |
| **Album collage** | Your top 1, 4, 8, 16 or 32 albums |
| **Band collage** | The same, by artist |
| **Band word cloud** | Names sized by how much you played them |
| **Genre word cloud** | The same, by tag |
| **Most played track** | The one track of the period |
| **Listening clock** | 24 hours around a dial — what you play at 8am is not what you play at 1am |
| **New artist of the year** | What you discovered, not what you already knew |
| **New album of the year** | The same, by album |
| **Forgotten album** | Something you played to death once and have not touched in years |
| **Forgotten track** | The same, by song |
| **On repeat** | What you played most times in a single day |

Collages, word clouds and top tracks cover the last week, month, three months, six months, year or your full history. Discovery and forgotten-music designs use their own time ranges.

<img src="https://scrobblewall.com/img/albums.jpg" alt="Album collage wallpaper">
<img src="https://scrobblewall.com/img/clock.jpg" alt="24-hour listening clock wallpaper">
<img src="https://scrobblewall.com/img/soup.jpg" alt="Word cloud of band names">

## Also

- **An animated background** with eight included loops, including falling lights, or a video of your own. Covers and text stay still. Opacity, colour variation and speed are adjustable. Drawing and decoding pause when the desktop is covered; lightweight checks continue and memory can remain allocated. Resource use depends on your PC, monitors and video.
  [How it works.](https://scrobblewall.com/animated-wallpaper/)
- **Clock, date and weather**, positioned in the corner you choose. Optional weather comes from Open-Meteo; requests share the selected coordinates and the connection’s public IP with the provider.
- **Your own images** mixed into the rotation, from any folder on disk.
- **Multi-monitor**: a different wallpaper per screen.
- **21 languages**, in the window and in the text drawn on the wallpapers.
- **A portable build** that keeps its settings and cache in its folder and needs no administrator rights.

<img src="https://scrobblewall.com/img/app-en.jpg" width="520" alt="The ScrobbleWall settings window">

## Getting started

1. [Download the normal or portable ZIP](https://github.com/ijlsadleir/scrobblewall/releases/latest) and unzip it.
2. Run `ScrobbleWall.exe`.
3. Type your Last.fm username — the one in `last.fm/user/YOUR_NAME`.
4. Tick what you want in the rotation and close the window.

No password and no API key: your listening history is already public on your
Last.fm profile, so reading it needs nothing else. There is no login screen
anywhere in the app.

Using Spotify? Connect it to Last.fm and everything you play gets recorded
there. Spotify also works as a direct source, with fewer wallpaper types.

## Questions

<details>
<summary><b>Why does Windows warn me about it?</b></summary>

Windows may show a SmartScreen warning for an unfamiliar download. Check that the file came from this repository’s release page. More details are [on the site](https://scrobblewall.com/#smartscreen).
</details>

<details>
<summary><b>Is there a macOS or Linux build?</b></summary>

No. Setting the desktop wallpaper is one of the least portable things an
operating system does, so this is not a small port.
</details>

<details>
<summary><b>Why is the source not here?</b></summary>

This repository is the project's home page, issue tracker and release list —
not its source. ScrobbleWall is a one-person project that is free but not open
source, and it seems fairer to say that plainly than to leave you clicking
around looking for a `src/` folder. If open source is what you need,
[Lively Wallpaper](https://github.com/rocksdanister/lively) is GPL-v3 and very
good.
</details>

<details>
<summary><b>Does it collect anything?</b></summary>

No telemetry, no analytics, no account. It talks to Last.fm to read your
public history, to cover art sources to fetch album art, and to Open-Meteo
only if you turn the weather on. [Privacy page.](https://scrobblewall.com/privacy/)
</details>

## Bugs and ideas

Open an issue here. Screenshots help a lot, and if a wallpaper came out wrong
it is useful to say which type and which period. You can also write to
<hello@scrobblewall.com>.

---

<sub>ScrobbleWall is an independent project. It is not affiliated with,
endorsed by, or connected to Last.fm or CBS Interactive. Album art belongs to
its respective owners.
<a href="https://www.last.fm/">Powered by AudioScrobbler</a>.</sub>
