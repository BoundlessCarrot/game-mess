# Conceptual tester for DiaB
Now that this is public I guess it needs an actual readme! This is just a repo to test out game engine stuff for a game idea I've had for years, that I've titled Death is a Blessing.

I'd also like to get advice from people about how to proceed with certain issues.

### Tech Stack
I'm using:

  - Zig (v0.13.0)
  - [Raylib](https://github.com/raysan5/raylib) [bindings for zig](https://github.com/Not-Nik/raylib-zig)
    - Specifically raylib v5.1-dev

### Running the game
  1. Grab the release relevant to your machine from the [releases](https://github.com/BoundlessCarrot/DiaB-concept/releases)
  2. Change the permissions on it with `chmod +x [FILENAME]` (only if you're on MacOS or Linux)
  3. You should be good to go! The game will probably ping off your antivirus or app recognition software (looking at you, MacOS), this is due to the code being unsigned as of now, it is something that is 100% on the to-do list

### Developing the game/build from source
  1. Install zig
     * use your [package manager](https://github.com/ziglang/zig/wiki/Install-Zig-from-a-Package-Manager) of choice or [install from source](https://ziglang.org/download/)
  2. Fetch zig-raylib (from within the repo)
     * `zig fetch --save https://github.com/Not-Nik/raylib-zig/archive/devel.tar.gz`
  3. `zig build run`

I try to leave the main branch in a state where it'll always compile and run, but that's not guaranteed tbqh.
    
