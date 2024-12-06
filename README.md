[![Donations Received][liberapay-donations-received-url]][liberapay-link]
[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Forks][forks-shield]][forks-url]
[![AGPL-3.0 License][license-shield]][license-url]

# RustyTube

A desktop Youtube client written in Rust. Built with Leptos and Tauri; designed with Tailwind and DaisyUI.

## Why should I use it?

- 🖥️ Why not? Try it out [here][website-url]. 🖥️
- ✨ WebM support for 4k 60fps. ✨
- 👎 Dislike counts. 👎
- 🦀 Built with Rust. 🦀
- 🦋 Beautiful and modern UI. 🦋
- 🎨 30+ themes, including a custom RustyTube theme based on [Sweet Ambar Blue Dark][sweet-theme-url]. 🎨
- 💩 Not an Electron app. 💩

## Screenshots

<div>
    <img src="/screenshots/rt_video_dracula.png" width=300/>
    <img src="/screenshots/rt_video_rustytube.png" width=300/>
    <img src="/screenshots/rt_video_garden.png" width=300/>
    <img src="/screenshots/rt_video_retro.png" width=300/>
</div>

<br></br>

<div>
    <img src="/screenshots/rt_subs_dracula.png" width=300/>
    <img src="/screenshots/rt_subs_rustytube.png" width=300/>
    <img src="/screenshots/rt_subs_garden.png" width=300/>
    <img src="/screenshots/rt_subs_retro.png" width=300/>
</div>

## How do I use RustyTube?

| Platform      | Link                                              |
| ------------- | ------------------------------------------------- |
| Web           | [rustytube.rs][website-url]                       |
| Linux         | [rustytube.rs][website-url]                       |
| Windows (exe) | [RustyTube_v0.2.0_x64-setup.exe][windows-exe-url] |
| Mac           | [rustytube.rs][website-url]                       |

### Browser Support

| Browser        | Comment                                                    |
| -------------- | ---------------------------------------------------------- |
| Firefox        | Works perfectly. Testing is done mainly on Firefox.        |
| Chromium-based | Works great. Might be some ui/ux issues.                   |
| Webkit-based   | Unsupported and a massive PITA. Maybe it will work... idk. |

## Building RustyTube

Install Rust and Tauri. Go to the Tauri [prequisites](https://tauri.app/v1/guides/getting-started/prerequisites) page.

After installing Rust and Tauri, execute the following script in the base of your RustyTube directory:

```
rustup update stable-unknown-linux-gnu;
rustup component add rust-src --toolchain stable-unknown-linux-gnu;
rustup target add wasm32-unknown-unknown;
cargo install trunk;
cargo install tauri-cli;
cd frontend;
npm install;
```

## FAQ

### Windows says that RustyTube is a virus. Is it safe to install?

It's totally safe and not a virus; I'm 10 billion percent sure - trust me bro.

## Common Issues

### Video player has a green screen on Webkit-based browsers.

Change the video format. Use the cog located in the bottom right of the video player.

### No audio?

Change the video format. Use the cog located in the bottom right of the video player.

### Video won't load, changing formats doesn't fix it.

If you are trying to watch a music video, RustyTube currently does not work with VEVO videos.

## What's the recipe?

- [Leptos][leptos-url] - A modern Rust web framework.
- [Tailwind][tailwind-url] - A CSS framework.
- [DaisyUI][daisyui-url] - A Tailwind component library.
- [Tauri][tauri-url] - A Rust desktop application framework.

## Donations

RustyTube is a free and open-source project with well over _500 hours_ in development and testing time.



## Roadmap

RustyTube is still in early development. There are things missing and stuff that I would like to add.

- Mobile UI and Mobile App (Significant donations/support required for this)
- Desktop Integration with Tauri
- Full SponsorBlock API Support
- Full Playlist Support

## Alternatives

### Desktop

[Freetube][freetube-github-url] - An open source desktop YouTube player built with privacy in mind.

### Mobile

[Newpipe][newpipe-github-url] - A libre lightweight streaming front-end for Android.

[Libretube][libretube-github-url] - An alternative frontend for YouTube, for Android.

[Clipious][clipious-github-url] - Android client application for invidious, the privacy focused youtube front end.

[website-url]: https://rustytube.rs
[sweet-theme-url]: https://github.com/EliverLara/Sweet/tree/Ambar-Blue
[leptos-url]: https://leptos.dev
[tailwind-url]: https://tailwindcss.com
[daisyui-url]: https://daisyui.com
[tauri-url]: https://tauri.app

