# イーライ / 茜音イーライ・暁 — Japanese UTAU Voicebank Project

Official repository for the **イーライ** voicebank family by **Ilya Minin (Eli)**.

> **Stay Determined.**

The project is a continuously growing voicebank line:

- **イーライ (Iirai)** — Generation 1, the original voicebank.
- **茜音イーライ (Akane Iirai)** — Generation 2, the established expanded CVVC release.
- **茜音イーライ・暁 (Akane Iirai · Akatsuki)** — Generation 3, **v3.0**, now released with expanded CVVC coverage, additional samples and consonant material, and generation-specific visual design.

Each generation records another stage of the same voicebank's development. Earlier generations remain part of the archive rather than being replaced.

## Official Website

https://ilyaminineli.github.io/Iirai/

## Read the generations

- [イーライ — Generation 1 profile](iirai.html)
- [茜音イーライ — Generation 2 profile](akane-iirai.html)
- [茜音イーライ・暁 — Generation 3 profile](akane-iirai-akatsuki.html)
- [Three-generation Character page](character.html)
- [Lineup](info.html)

## Downloads

### イーライ

- [GitHub Release](https://github.com/ilyaminineli/Iirai/releases/tag/%E3%82%A4%E3%83%BC%E3%83%A9%E3%82%A4)
- [BowlRoll](https://bowlroll.net/file/349204)

### 茜音イーライ

- [GitHub Release](https://github.com/ilyaminineli/Iirai/releases/tag/%E8%8C%9C%E9%9F%B3%E3%82%A4%E3%83%BC%E3%83%A9%E3%82%A4)
- [BowlRoll](https://bowlroll.net/file/350273)

### 茜音イーライ・暁

- [GitHub Releases archive](https://github.com/ilyaminineli/Iirai/releases)
- [Generation 3 profile](akane-iirai-akatsuki.html)

The Generation 3 documentation is published as **v3.0**. Distribution is kept with the release archive so the repository can preserve the full generation history.

## Documentation

- [Documentation hub](docs/README.md)
- [Official Manual](docs/MANUAL.md)
- [Technical Specification](docs/VOICEBANK.md)
- [Usage Guide](docs/USAGE.md)
- [Character](docs/CHARACTER.md)
- [Generation History](docs/VERSIONS.md)
- [Media Archive](docs/MEDIA.md)
- [Release Documentation](docs/RELEASES.md)
- [Terms of Use](TERMS.md)
- [Generation Manifest](metadata/generations.json)

## Current released voicebank — 茜音イーライ・暁

| Property | Official value |
|---|---|
| Name | 茜音イーライ・暁 (Akane Iirai · Akatsuki) |
| Generation | 3 |
| Version | v3.0 |
| Engine | UTAU / OpenUtau |
| Language | Japanese |
| Recording method | CVVC |
| Encoding | Romaji-encoded, CVVC aliased |
| Subbanks | _C4 / _G3 / _F3 / _C3 |
| Ranges | A#3–B7 / G3–A3 / D3–F#3 / C1–C#3 |
| Sample format | 44.1kHz / 16-bit |
| Approx. sample size | ~500MB |
| Recommended resamplers | Moresampler / TIPS / WORLDLINE-R |
| Bass setup | `g-30 MG40 Mb20` |

The release also includes additional samples and consonant releases, with Moresampler expressions such as Breathiness, Tension and Growl supported by the documented workflow.

## Character & Credits

**Creator:** Ilya Minin (Eli)  
**Voice Provider:** Ilya Minin (Eli)  
**Character Design:** Schenchik  
**OTO / Technical:** eikton

The three generations document a continuous evolution of the voicebank and character rather than separate unrelated projects.

## Repository Structure

- `assets/character/イーライ/` — Generation 1 artwork
- `assets/character/茜音イーライ/` — Generation 2 artwork
- `assets/character/茜音イーライ・暁/` — Generation 3 artwork
- `assets/promotional/` — promotional artwork
- `assets/patterns/` — decorative patterns
- `assets/textures/` — shared paper textures
- `docs/` — canonical documentation and project history
- `metadata/` — machine-readable manifests
- `sample.wav`, `solfege.wav` — current audio samples
- root HTML files — GitHub Pages site

## Historical Reference

The original **イーライ (Iirai)** and the released **茜音イーライ** remain part of the archive. Their release pages and distribution links are intentionally preserved so the three generations can be compared historically.

## Source of Truth

For current Generation 3 metadata, use the Generation 3 manual/profile and current repository documentation. Earlier generations remain authoritative for their own archived releases.
