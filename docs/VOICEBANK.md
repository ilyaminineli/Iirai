# イーライ Voicebank Line — Voicebank Specification

This is the canonical technical overview of the イーライ voicebank family. The project is developed as a continuous voicebank line whose recordings, expression and presentation grow from one generation to the next.

## Generation 1 — イーライ

The original Japanese UTAU voicebank and the starting point of the project.

- [Character profile](../iirai.html)
- [GitHub release](https://github.com/ilyaminineli/Iirai/releases/tag/%E3%82%A4%E3%83%BC%E3%83%A9%E3%82%A4)
- [BowlRoll distribution](https://bowlroll.net/file/349204)

## Generation 2 — 茜音イーライ

The established second generation with expanded Japanese CVVC material.

- Pitches: A3 / F3 / C3
- Optimum BPM: 70–120
- Engine: UTAU / OpenUtau
- Recording method: Japanese CVVC
- Encoding: Romaji-encoded, CVVC aliased

- [Character profile](../akane-iirai.html)
- [GitHub release](https://github.com/ilyaminineli/Iirai/releases/tag/%E8%8C%9C%E9%9F%B3%E3%82%A4%E3%83%BC%E3%83%A9%E3%82%A4)
- [BowlRoll distribution](https://bowlroll.net/file/350273)

## Generation 3 — 茜音イーライ・暁

**Released as v3.0.**

### Technical specification

- Engine: UTAU / OpenUtau
- Language: Japanese
- Recording method: Japanese CVVC
- Encoding: Romaji-encoded, CVVC aliased
- Subbanks:
  - `_C4` — A#3–B7
  - `_G3` — G3–A3
  - `_F3` — D3–F#3
  - `_C3` — C1–C#3
- Sample format: 44.1kHz / 16-bit
- Approximate sample size: ~500MB
- Additional samples and consonant releases
- Moresampler expressions: Breathiness, Tension, Growl, etc.
- Recommended resamplers: Moresampler, TIPS, WORLDLINE-R
- Recommended bass setup: `g-30 MG40 Mb20`

The Generation 3 release is intended for expressive Japanese vocal synthesis with natural consonant blending and a broader expressive palette.

- [Character profile](../akane-iirai-akatsuki.html)
- [GitHub Release — v3.0](https://github.com/ilyaminineli/Iirai/releases/tag/%E8%8C%9C%E9%9F%B3%E3%82%A4%E3%83%BC%E3%83%A9%E3%82%A4%E3%83%BB%E6%9A%81)
- [BowlRoll distribution](https://bowlroll.net/file/361799)
- [Release archive](https://github.com/ilyaminineli/Iirai/releases)

## Character / Credits

- Presentation: Fluid / androgynous
- Pronouns: he/him
- Creator: Ilya Minin (Eli)
- Voice Provider: Ilya Minin (Eli)
- Illustrator: Schenchik
- OTO / Technical: eikton

The progression from イーライ to 茜音イーライ and then to 暁 is documented as continuous development of the same voicebank line.

## Moresampler expressions

- Velocity (0–200): Consonant strength
- Gender (-100 to 100): Formant shift (deep/light)
- Tone Shift (-36 to 36): Pitch selection
- Breathiness (0–100): Added noise
- Tension (-200 to 200): Voice strength
- Growl (0–100): Guttural effect

## Voicebank characteristics

The family is built around a warm, textured core with increasing access to expressive and upper-register material as the generations develop. Generation 3 broadens the available recording and expression options while preserving the lineage of the earlier voices.

## Canonical source

For released technical values, use the current generation-specific voicebank manual and release documentation. Historical information for Generation 1 and Generation 2 remains part of the archive.
