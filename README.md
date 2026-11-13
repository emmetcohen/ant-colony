# Ant Colony

A living, pixel-art ant farm that runs in your browser. Every ant can have its own AI brain: a small language model running right inside the browser tab (no server, no API key).

**Play:** https://emmetcohen.github.io/ant-colony/

## Controls
- **Click**: drop food (hold to pour)
- **F**: switch between sugar, cricket (protein) and water
- **Right-click**: remove food or water
- **Shift + click**: inspect an ant (see its thoughts, memories, and its route in yellow)
- **S**: stats, needs checklist, daily journal and ant-keeping tips
- **T**: time-lapse (1×, 4×, 16×)
- **A**: turn the AI brains on or off
- **B**: thought bubbles (important only, every thought, or off)
- **Shift + R**: start a new colony

## AI brains
Press **A** to turn them on. The first time, the page downloads a small model (about 0.5–1 GB) and keeps it in the browser, so later it loads in seconds. It needs a browser with WebGPU (Chrome or Edge work best). The page picks the best model that fits your computer. Add `?model=small` to the link to force the smallest one on an older computer.

Every time an ant finishes a job it asks the AI what to do next, using only what a real ant could smell and feel, and waits its turn for an answer. Important thoughts pop up as speech bubbles. Ants only fall back on instinct if the AI is off, very busy, at 16× time-lapse, or while catching up after the page was closed.

Built with [WebLLM](https://github.com/mlc-ai/web-llm).
