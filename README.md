# Ant Colony

A living, pixel-art ant farm that runs in your browser. Every ant can have its own AI brain: a small language model running right inside the browser tab (no server, no API key).

**Play:** https://emmetcohen.github.io/ant-colony/

## Controls
- **Click**: drop food (hold to pour)
- **F**: switch between sugar, cricket (protein) and water
- **Right-click**: remove food or water
- **Shift + click**: inspect an ant (see its thoughts and memories)
- **S**: stats, needs checklist, daily journal and ant-keeping tips
- **T**: time-lapse (1×, 4×, 16×)
- **A**: turn the AI brains on or off
- **Shift + R**: start a new colony

## AI brains
Press **A** to turn them on. The first time, the page downloads a small model (about 0.5–1 GB) and keeps it in the browser, so later it loads in seconds. It needs a browser with WebGPU (Chrome or Edge work best). The page picks the best model that fits your computer. Add `?model=small` to the link to force the smallest one on an older computer.

Each ant takes turns asking the AI what to do, using only what a real ant could smell and feel. While the AI is busy, or during time-lapse, the ants act on instinct.

Built with [WebLLM](https://github.com/mlc-ai/web-llm).
