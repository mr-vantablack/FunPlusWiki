
# Chat commands

## /play
Plays an audio file via a link.
- Usage: /play `link` `volume` `loop`
	- `link` (string) - Direct link to the audio file (the end of the link should be .mp3 or .wav)
	- `volume` (float) - Audio volume from 0 to 1
	- `loop` (bool) - If true, the sound will be looped
- Example: 
		/play https://ippls.lh1.in/-_Pou_1.mp3
		/play https://ippls.lh1.in/-_Pou_1.mp3 0.8 true

## /stop
Stops the music player.
- Usage: /stop

## /me
RP command that indicates that you have performed an action.
- Usage: /me `action`
	- `action` (string) - Write anything here
- Example: 
		/me pressed the nuke button
		/me got schizophrenia

## /respawn 
Respawns the player if he gets stuck. It only works if the player is a monster and has a cooldown of 5 minutes.
- Usage: /respawn