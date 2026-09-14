# Mumbai welcomes Bappa

A whimsical Ganesh Chaturthi welcome animation with a 16-entry music queue with Bollywood, devotional, dhol-tasha, rocking, meditation, mantra, and festival moods.

## Deploy on Vercel

Import this GitHub repository into Vercel. Choose **Other** as the framework preset. No build command or installation is required; serve the repository root.

## Music

A single persistent YouTube IFrame API player handles playback. Ten songs are chapters in the T-Series Ganesh Aarti Collection; additional selections include Sony Music India Bollywood songs, Times Music Spiritual devotional songs, a T-Series Ganesh mantra, and Aaradhya Dhol-Tasha Pathak percussion. Recordings are streamed, not redistributed or open-source licensed.

An HTTPS deployment provides the HTTP referrer YouTube expects. Browser autoplay restrictions may require one tap on Play music. Regional, embedding, or video availability restrictions can still prevent individual tracks from playing; each selection includes its YouTube source link.

## Files

- `index.html`: embedded artwork, CSS animation, and playlist JavaScript.
- `vercel.json`: referrer header for embedded playback.

No API keys, backend, uploaded audio, or package installation required.

## Playback controls

All music controls are in one compact panel above the animation: category and song dropdowns, play/pause, previous/next, volume, repeat, and a chapter-relative seekbar. A visible 240 × 200 YouTube player remains beside the controls. Playback starts after a user gesture; navigation and repeat follow the selected category.

New selections: [Deva Shree Ganesha](https://www.youtube.com/watch?v=RCCYorPLJmQ), [Sadda Dil Vi Tu](https://www.youtube.com/watch?v=lEo1RvqJOcY), [Puneri Dhol Tasha](https://www.youtube.com/watch?v=tpfJfIF-QZA), and [Ganesh Mantra](https://www.youtube.com/watch?v=YArclZ-2IeU). Meditation is a mood selection of the quieter devotional and mantra recordings, not a separate remix.

Dhol Tasha by Aaradhya Dhol-Tasha Pathak: [source](https://www.youtube.com/watch?v=tpfJfIF-QZA), [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). All media remains in its original YouTube player.

## Playback reliability

Song changes use loadVideoById/cueVideoById on one persistent player. Unavailable or embedding-blocked uploads are skipped within the current category, with a bounded search that stops when none remain. Referrer error 153, autoplay blocking, and network stalls show separate messages. Retry and the original YouTube link remain available. Source availability and live playback are not guaranteed by the local controller tests.
