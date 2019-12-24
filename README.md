# Overlays

Game overlays are usually created by hooking into the game's process. That kind of technique is beyond my current skillset. Luckilly, I've managed to find a technique that works well enough for me by using my search engine of choice.

## Limitiations
 * The game has to be in either Windowed or Windowed Borderless.
 * Currently only works on Windows.

## How does it work?

You can see how it works by looking at `src/os.rs` and [reading this CodeProject article from 2007](https://www.codeproject.com/Articles/12877/Transparent-Click-Through-Forms). Some bits are (presumably) there to work around the way `winit` sets things up.