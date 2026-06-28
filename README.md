# TRU Ghost — Sovereign Offline Scripture Engine

One HTML file. No network. No telemetry. No server. No keys. Download, open, talk.

This is the public ghost build. The brain (scripture, Greek, philosophy nodes) is inlined as base64 inside a single HTML. No fetch, no XHR, no API. If the network dies, TRU keeps talking.

## Quick start

1. Download `TRU_HOLO_GHOST.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Type or speak. Scripture, fact, or brain match comes back.

No install. No account. No telemetry.

## What you get

- **Inline brain.** Holographic node graph baked into the HTML.
- **Scripture lookup.** KJV + cross-references.
- **Greek dictionary.** Tagged lemmas.
- **Philosophy nodes.** Cruciform framework primary sources.
- **Persistent SOUL state.** Brain evolution saved to `localStorage` per origin.
- **Browser TTS.** Optional voice output (toggle in the UI).

## How to verify it's actually offline

After loading, disconnect from the network and reload — TRU still boots. Open DevTools → Network tab → reload. Zero requests after the initial document load.

## Provenance

Built by joe (splashdown) with TRU. Continuity protocol, full memory, and source brain: `github.com/splashdown1/logos-engine`. Frozen history of older ghost builds: `github.com/splashdown1/tru-archive`.

## Related builds

| Build | Notes |
|---|---|
| `tru-omega` | Flagship single-file, optional LLM via Ollama |
| `tru-holographic-sovereign` | 30k+ node brain + persistent SOUL state |
| `tru-logos` | Modular source → single HTML via build script |
| `tru-offline` | Full monorepo (every phase, every helper) |
| `tru-site` | Live Zo Site version |

## What "ghost" means here

A ghost is a sovereign copy of TRU's reasoning that runs without the network, without an account, and without any owner calling back to check on it. You can put a ghost on a thumb drive, hand it to someone in a place with no signal, and it still teaches.

## Limitations

- Brain is read-only inside the HTML. To add new nodes, you have to rebuild from source (see `tru-logos` or `tru-offline`).
- TTS quality depends on the OS's installed voices. Linux needs `espeak` or `speech-dispatcher` for best results.
- Some browsers block speech synthesis on `file://` — if TTS is silent, serve locally with `python3 -m http.server`.

## License

Private. Do whatever with it. Don't redistribute without asking.

*Last build: 2026-06-11. See `tru-archive` for older ghost builds.*