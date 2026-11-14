<p align="center"><img src="docs/readme-banner.svg" width="100%" alt="ARK VIP / IPTV: A landscape media interface for playlists and streaming." /></p>

<p align="center"><a href="#project-guide">Project guide</a> · <a href="https://github.com/abdullahwaseem-dev/ip_tv/tree/master">Browse source</a> · <a href="https://github.com/abdullahwaseem-dev">Developer profile</a></p>

<a id="project-guide"></a>

# ARK VIP / IPTV — Flutter · GetX · VLC

ARK VIP is a Flutter IPTV/media-player interface designed to run in landscape orientation. It contains playlist, live-TV, movie, series, and player-settings screens with VLC integration.

## Highlights

- Landscape application shell with configurable themes.
- Playlist and M3U-related screens.
- Live TV, movies, series, and multi-screen interfaces.

## Run locally

Use a Flutter SDK whose bundled Dart version satisfies `>=3.4.1 <4.0.0`, as declared in [pubspec.yaml](pubspec.yaml). Configure the platform toolchain for your intended device.

```sh
git clone https://github.com/abdullahwaseem-dev/ip_tv.git
cd ip_tv
flutter pub get
flutter run
```

## Source map

- [lib/main.dart](lib/main.dart)
- [lib/app/routes/app_pages.dart](lib/app/routes/app_pages.dart)

## Current scope

Playback depends on compatible streams and provider configuration. This repository does not provide a content subscription; use only media you are authorised to access. Native VLC setup and supported devices require platform testing.

## Verification

```sh
flutter analyze
flutter test
```

These commands describe how to check the project; they were not run as part of the documentation refresh. Platform directories and declared dependencies do not prove that every target builds successfully.


---

## Author and project links

Built by [Muhammad Abdullah Waseem](https://github.com/abdullahwaseem-dev). [Portfolio](https://abdullah-waseem.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/abdullahwaseem-dev/) · [Project enquiries](mailto:maw112266@gmail.com)

For a bug report, include the affected version, environment, reproduction steps, and expected behaviour in [Issues](https://github.com/abdullahwaseem-dev/ip_tv/issues). If the project is useful to you, a star is appreciated.

**Reuse:** no root license file was found during this review. Public visibility alone does not grant permission to reuse the code; contact the author for terms.

