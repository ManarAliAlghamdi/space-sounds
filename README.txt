Space Sounds (أصوات الفضاء)

Files
  index.html   the whole website (design, animations, player)
  sounds/      the audio files

Add or edit a sound
  1. Put the audio file in the sounds/ folder (MP3, M4A, WAV).
  2. Open index.html in a code editor and find the SOUNDS list at the top of the <script>.
  3. Add a line: { title: "...", description: "...", anim: "blackhole", src: "sounds/your-file.mp3" },
     anim options: blackhole, pulsar, planet, waves, earth, star, comet, sun, supernova

Run it
  Best: run a local server in this folder, then open http://localhost:8000
      python3 -m http.server 8000
  Double-clicking index.html also works, but the animations won't react to the
  sound (browsers block audio analysis for files opened straight from disk).

Put it online for free
  GitHub Pages, Netlify Drop (drag the folder in), or Vercel.
