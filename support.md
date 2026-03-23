# MIDItoOSC Support

_Last updated: 2026-03-23_

MIDItoOSC helps you monitor MIDI events and get OSC equivalent commands quickly for M32/X32 use cases.

## What the app does

- Detects available MIDI inputs on your Mac
- Lets you select the MIDI source to monitor
- Shows incoming MIDI messages in real time
- Proposes equivalent OSC commands
- Lets you copy OSC lines directly from the app

## Quick start

1. Open MIDItoOSC.
2. Select your MIDI input in the left panel.
3. Click **Refresh devices** if needed.
4. Move a fader or press a button on your mixer.
5. Copy the OSC command from the log.

## Troubleshooting

### No MIDI events appear
- Verify your mixer/interface is connected and sending MIDI.
- Check that the correct MIDI source is selected.
- Click **Refresh devices** after reconnecting hardware.

### OSC line is not what you expect
- Confirm your mixer MIDI mode/channel configuration.
- Confirm expected X32/M32 mapping.

### Copy works but target app rejects the command
- Confirm the destination app expects the same OSC format.
- Check value format (decimal separator, command style).

## Contact

For support requests, use the contact channel configured by the app publisher.
