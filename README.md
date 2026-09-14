# Mumbai welcomes Bappa

A whimsical Ganesh Chaturthi welcome animation with a 16-entry music queue with Bollywood, devotional, dhol-tasha, rocking, meditation, mantra, and festival moods.

## Deploy on Vercel

Import this GitHub repository into Vercel. Choose **Other** as the framework preset. No build command or installation is required; serve the repository root.

## Music

Plyr 3.7.8 (MIT) wraps official YouTube embeds. Ten songs are chapters in the T-Series Ganesh Aarti Collection; additional selections include Sony Music India Bollywood songs, Times Music Spiritual devotional songs, a T-Series Ganesh mantra, and Aaradhya Dhol-Tasha Pathak percussion. Recordings are streamed, not redistributed or open-source licensed.

An HTTPS deployment provides the HTTP referrer YouTube expects. Browser autoplay restrictions may require one tap on Play music. Regional, embedding, or video availability restrictions can still prevent individual tracks from playing; each selection includes its YouTube source link.

## Files

- `index.html`: embedded artwork, CSS animation, and playlist JavaScript.
- `vercel.json`: referrer header for embedded playback.

No API keys, backend, uploaded audio, or package installation required.

## Playback controls

Use the sticky **Play music** button above the animation. Both play/pause buttons reflect the same player. Playback begins only after a user gesture. Mood buttons filter the queue, and previous/next, automatic continuation, and repeat use that filtered queue.

New selections: [Deva Shree Ganesha](https://www.youtube.com/watch?v=RCCYorPLJmQ), [Sadda Dil Vi Tu](https://www.youtube.com/watch?v=lEo1RvqJOcY), [Puneri Dhol Tasha](https://www.youtube.com/watch?v=tpfJfIF-QZA), and [Ganesh Mantra](https://www.youtube.com/watch?v=YArclZ-2IeU). Meditation is a mood selection of the quieter devotional and mantra recordings, not a separate remix.

Dhol Tasha by Aaradhya Dhol-Tasha Pathak: [source](https://www.youtube.com/watch?v=tpfJfIF-QZA), [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). All media remains in its original YouTube player.
