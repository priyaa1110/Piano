# Piano

A minimal web-based piano application with keyboard and mouse support.

## Features

- 13 playable keys (C to C2) with white and black keys
- Keyboard input support (A-K for white keys, W-Y for sharps)
- Mouse/touch support for clicking keys
- Volume control slider
- Toggle to show/hide keyboard shortcuts
- Web Audio API for sound synthesis
- Fully responsive design

## Usage

Open piano.html in a modern web browser. No server or dependencies required.

### Keyboard Controls

White keys: A S D F G H J K
Black keys: W E T Y U

### Controls

- Volume slider: Adjust playback volume
- Show Keys toggle: Display or hide keyboard shortcuts on keys

## Technical Details

- Single HTML file with embedded CSS and JavaScript
- Uses Web Audio API for real-time sound generation
- Sine wave oscillator for clean piano-like tones
- Responsive layout adapts to mobile and desktop screens
- Zinc theme with minimal design aesthetic

## Browser Compatibility

Requires a modern browser with Web Audio API support:
- Chrome 34+
- Firefox 25+
- Safari 14.1+
- Edge 79+

## Notes

Audio context initializes on first interaction due to browser autoplay policies.
