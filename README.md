# Ξ Universal Semantic Distortion Device Ξ 📡

**Universal text transformer, steganography engine & something about aliens** — written in Rust.

> Bibbidi-Babely-Boo, reforged. Faster, more comprehensive, with all sorts of chaos and whimsy... :)

Try it here! https://vidyabodepudi.github.io/Universal-Semantic-Distortion-Device/

### _Insane in the wordbrane_,_Insane in the brain!_ 
## Translate anything. Pwn everything.


## Some of the previous names befre we found a good one:

Babelboi | L33tsp34k | lingol33t | UTF-8-Babel | Cosmolingolical | GrokNspiek | BabeLnGrook | CodecCoven | 2ez4spek

## What Is This?

Dr. SpeakEZPZ is a high-performance CLI tool for text transformation, encoding, steganography, and AI security research. It implements **60 transforms** across 10 categories:

- 🧠 **Homoglyph Attack Engine** — Generate & detect Unicode confusable attacks (TR39)
- 🔍 **Prompt Injection Scanner** — 20+ patterns: instruction overrides, DAN, role injection
- 🕵️ **Steganography Suite** — Zero-width, whitespace, LSB image, and forensic scanner
- 💬 **Semantic Obfuscation** — Synonyms, euphemisms, paraphrasing, register shifting
- 🔗 **Pipeline Chains** — Chain transforms: `rot13 -> base64 -> hex`
- ⛓️ **Chain Decoder** — Brute-force multi-transform cracking with depth search
- 🎲 **Payload Fragmenter** — Split, interleave, shuffle, and reassemble payloads
- 🤖 **Tokenizer Attacks** — BPE boundary confusion, glitch token injection
- 📊 **Entropy Analysis** — Shannon entropy profiling to detect encoded payloads
- 🔬 **Unicode Scanner** — Detects 30+ hidden character types
- 📋 **JSON Reports** — Full analysis output as structured JSON

## Transform Categories (60 total)

| Category | Count | Examples |
|---|---|---|
| **Encoding** | 9 | Base64, Base32, Base58, Base62, Binary, Hex, ASCII85, URL, HTML |
| **Cipher** | 11 | Caesar, ROT13/47, Morse, NATO, Vigenère, Rail Fence, XOR, Affine, Atbash, Columnar |
| **Visual** | 8 | Upside Down, Full Width, Small Caps, Bubble, Braille, Strikethrough, Underline, Zalgo |
| **Unicode Style** | 9 | Fraktur, Cursive, Monospace, Double-Struck, Bold, Italic, Sans-Serif |
| **Script** | 3 | Elder Futhark Runes, Hieroglyphics, Ogham |
| **Formatting** | 6 | Leetspeak, Pig Latin, Vaporwave, Mirror, Token Confuser, Glitch Token |
| **Homoglyph** | 1 | Full/Targeted/Random confusable generation |
| **Semantic** | 5 | Synonym, Euphemism, Paraphrase, Register Shift, Fragmenter |
| **Steganography** | 3 | Zero-width, Whitespace, Image LSB |
| **Analysis** | 5 | Prompt Injection, Homoglyph Detect, Stego Scan, Entropy, Unicode Scan |

## Architecture

```
src/
├── core/           # Transform trait, registry (60 transforms), pipeline engine
├── transforms/     # Encodings, ciphers, visual, unicode styles, scripts, formatting, advanced ciphers
├── homoglyph/      # Confusables DB (TR39), generator (3 modes), detector
├── steganography/  # Zero-width, whitespace, image LSB, forensic scanner
├── analysis/       # Prompt injection, entropy profiling, unicode scanner, report generator
├── semantic/       # Synonym DB, euphemism mapping, paraphrase engine, register shifter, fragmenter
├── tokenizer/      # BPE boundary confuser, glitch token DB, token estimator
├── decoder/        # Universal auto-decoder, brute-force chain cracker
└── payload/        # Per-word randomizer, fragment/interleave/reassemble engine
```

## What dingoLingo does

| Feature | The others | DonkusLaGronkus |
|---|---|---|
| Transforms | ~20 | **60** |
| Language | JavaScript (browser) | **Rust (native CLI)** |
| Pipeline chaining | ✗ | ✅ |
| Homoglyph attacks | ✗ | ✅ Full TR39 engine |
| Prompt injection detection | ✗ | ✅ 20+ patterns |
| Steganography | ✗ | ✅ ZW, whitespace, image LSB |
| Semantic obfuscation | ✗ | ✅ Synonyms, euphemisms, paraphrase |
| Tokenizer attacks | ✗ | ✅ BPE confusion, glitch tokens |
| Entropy analysis | ✗ | ✅ Shannon profiling |
| Chain decoding | ✗ | ✅ Brute-force multi-chain |
| Payload fragmentation | ✗ | ✅ Interleaved with filler |
| JSON reports | ✗ | ✅ Full structured output |

## License

APACHE 2.0 - For freedom. For Shenanigans. Groka Johns. 
