# Hindsight releases

Signed and notarized downloads of Hindsight, Stencon's internal time-tracking app for macOS.
The source code is private; this repository only holds the releases and the update feed.

**Install:** download `Hindsight.dmg` from the [latest release](../../releases/latest), open it and drag
Hindsight to Applications. Hindsight keeps itself up to date from here.

Requires macOS 14 or later on Apple silicon, and a local language model running on your Mac in an app
such as Bionic (LM Studio) or [Ollama](https://ollama.com). Hindsight finds the models those apps have
downloaded; pick one in Settings → Processing → Local model. Recommended:

- **Qwen 3.8 27B** (about 16 GB at 4-bit): what Hindsight is tested with. Needs a Mac with 32 GB of memory or more.
- **Qwen3 30B-A3B** (about 18 GB at 4-bit): a mixture-of-experts model, several times faster for the same
  quality class; a good choice if processing feels slow. Not yet tested with Hindsight.

Small models (under ~14B) aren't good enough at telling clients and tasks apart.
Everything Hindsight records stays on your Mac.
