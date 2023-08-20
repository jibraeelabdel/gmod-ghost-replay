# GMod Ghost Replay

Addon that allows you to record and replay your movements in Garry's Mod. This is a proof-of-concept that should be improved before being used in production.

## Installation

1. Go to your `garrysmod/addons` directory
2. Clone this repository into it using `git clone https://github.com/luttje/gmod-ghost-replay ghost_replay`

## Usage

1. Start a game in Garry's Mod
2. Open the console and type `ghost_replay_record` to start recording your movements
3. When you're done, type `ghost_replay_stop_recording` to stop recording
4. Use `ghost_replay_list_recordings` to list all recordings and their IDs
5. Type `ghost_replay_play 1` to play back the specified recording

## Known limitations

- Animations are not recorded properly (so you will not see the player jump, crouch or taunt)
- There is no limit on the recording length. If a player starts a recording and never stops it, the server will eventually run out of memory