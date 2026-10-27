# social-videos

Hosting for the short videos of the **Built with Claude Code** series and the **Claude Game Arena** promos
(YouTube Shorts, Instagram Reels and Stories, X). The video files live in [Releases](../../releases), so every file
has a stable public download URL for the scheduler. This repository holds no source code; the videos are made with
Remotion in [video-studio](https://github.com/Furkiozknn).

> [!NOTE]
> **The voices in these videos are AI-generated.** The game promos use Google Gemini TTS; the episode releases
> (`ep21-27`, `ep28-plus`) use Supertonic 3. Every post that uses one of these videos says so too.

## Releases

| Release | What is inside |
|---|---|
| [`promo-2026-10`](../../releases/tag/promo-2026-10) | Promo videos for the Claude Game Arena games, October 2026 |
| [`ep28-plus`](../../releases/tag/ep28-plus) | Built with Claude Code, episode 28 onward |
| [`ep21-27`](../../releases/tag/ep21-27) | Built with Claude Code, episodes 21 to 27 |

A new `promo-YYYY-MM` release is added each month for that month's game promos.

## Game promos (`promo-YYYY-MM`)

Each game gets its own set of cuts:

| Cut | Voice | Where it goes |
|---|---|---|
| `en` | English | YouTube Shorts and X (same time slots) |
| `tr` | Turkish | Instagram Reels |
| `story-tr` | Turkish | Instagram Story, posted 1 hour before that game's reel |

File names follow `<publish-date>-<game>-<en|tr|story-tr>.mp4`, for example `2026-10-27-kervan-en.mp4`. A download
URL looks like:

```
https://github.com/Furkiozknn/social-videos/releases/download/promo-2026-10/2026-10-27-kervan-en.mp4
```

`promo-2026-10` currently holds Kervan and Peri Golf (2026-10-27) and Dolmuş and Mehter (2026-10-28), plus the
Kervan story cut.

## The games

Each game in the Claude Game Arena is a 3D browser game built by a Claude model with Claude Code from one prompt. They
run in the browser on desktop and phone, with nothing to install:

| Game | Play |
|---|---|
| Kervan | [furkiozknn.github.io/kervan](https://furkiozknn.github.io/kervan/) |
| Dolmuş | [furkiozknn.github.io/dolmus](https://furkiozknn.github.io/dolmus/) |
| Peri Golf | [furkiozknn.github.io/peri-golf](https://furkiozknn.github.io/peri-golf/) |
| Mehter | [furkiozknn.github.io/mehter](https://furkiozknn.github.io/mehter/) |
| Boğaz Vapuru | [furkiozknn.github.io/bogaz-vapuru](https://furkiozknn.github.io/bogaz-vapuru/) |
| Simit Fırını | [furkiozknn.github.io/simit-firini](https://furkiozknn.github.io/simit-firini/) |
| Karagöz | [furkiozknn.github.io/karagoz](https://furkiozknn.github.io/karagoz/) |
| Lale Bahçesi | [furkiozknn.github.io/lale-bahcesi](https://furkiozknn.github.io/lale-bahcesi/) |

## Episode releases

`ep21-27` and `ep28-plus` hold the Built with Claude Code episodes: an `-en` and a `-tr` main cut, a `-tanitim-tr`
teaser and a `-hikaye-tr` story cut per episode, named `<publish-date>-<project>-<cut>.mp4`.

## Türkçe

Bu depo **Built with Claude Code** serisinin ve **Claude Game Arena** oyun tanıtımlarının kısa videolarını Releases
içinde barındırır. Oyun tanıtımlarında İngilizce kesim YouTube ve X'e, Türkçe kesim Instagram Reels'e gider; Türkçe
hikâye kesimi her Reels'ten 1 saat önce paylaşılır. Her ay yeni bir `promo-YYYY-MM` sürümü eklenir. Videolardaki sesler
yapay zekâ ile üretilmiştir (tanıtımlarda Google Gemini TTS, bölümlerde Supertonic 3).
