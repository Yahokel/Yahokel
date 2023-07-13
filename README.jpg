- 👋 Hi, I’m @Yahokel
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Yahokel/Yahokel is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---># Partitura de TK from Ling Tosite Sigure

```lilypond
\version "2.18.2"
\header {
  title = "TK from Ling Tosite Sigure"
  composer = "Bing"
}
\score {
  \new StaffGroup <<
    \new Staff \with {
      instrumentName = #"Guitarra "
    } {
      \clef "treble_8"
      \key c \minor
      \time 4/4
      \tempo 4 = 160
      r8 ees'16 f' g' bes' c'' ees'' f'' g'' bes'' c''' ees''' f''' g''' bes''' c'''' ees'''' f'''' g'''' bes'''' c''''' ees''''' f''''' g''''' bes''''' c'''''' ees'''''' f'''''' g''''''
      r8 ees'16 f' g' bes' c'' ees'' f'' g'' bes'' c''' ees''' f''' g''' bes''' c'''' ees'''' f'''' g'''' bes'''' c''''' ees''''' f''''' g''''' bes''''' c''''''
      r8 ees'16 f' g' bes' c''
    }
    \new Staff \with {
      instrumentName = #"Bajo "
    } {
      \clef "bass"
      \key c \minor
      \time 4/4
      r8 c16 d ees g c' d' ees' g' c''
      r8 c16 d ees g c' d' ees'
      r8 c16 d ees
    }
    \new Staff \with {
      instrumentName = #"Batería "
    } {
      \clef "percussion"
      \time 4/4
      <<
        \new Voice {
          \repeat volta 2 {
            cymc4 sn8 hh sn hh sn hh sn hh |
            sn4 sn sn hh sn hh sn hh |
            sn4 sn sn hh sn hh sn hh |
            sn4 sn sn hh sn hh sn hh |
          }
        }
        \new Voice {
          bd4 bd bd bd |
          bd4 bd bd bd |
          bd4 bd bd bd |
          bd4 bd bd bd |
        }
      >>
    }
  >>
}
