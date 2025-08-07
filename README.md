# Orbiting Planets Animation

A mesmerizing recreation of the two-planet orbital animation from [Future Memories](https://www.futurememories.se/), featuring authentic film grain texture and atmospheric glowing effects.

![Planets Animation Preview](planets.png)

## Features

- **Realistic Orbital Motion**: Two planets maintain perfect opposition (180° apart) while orbiting
- **Authentic Film Grain**: Uses actual noise texture overlay with proper blend modes
- **Atmospheric Glow Effects**: Sharp-edged planets with precise blur values matching the original
- **Responsive Design**: Scales beautifully across desktop and mobile devices
- **Performance Optimized**: Hardware-accelerated CSS transforms and animations

## Technical Details

### Planet Specifications
- **Large Planet**: 1000px diameter, 40px blur, deep red-orange gradient
- **Small Moon**: 110px diameter, 2.5px blur, peachy cream gradient
- **Orbit Duration**: 180 seconds per complete revolution
- **Texture**: 600x600px noise overlay at 20% opacity with overlay blend mode

### Color Palette
- **Background**: Linear gradient from `#324948` (teal) to `#090d17` (deep blue)
- **Large Planet**: `#c72b04` → `rgba(241,113,17,0.5)` → `rgba(248,180,89,0)`
- **Small Moon**: `#ffccbf` → `rgba(255,184,130,0.5)` → `rgba(255,136,0,0)`

## Usage

Simply open `planets_animation.html` in any modern web browser. The animation runs automatically and loops infinitely.

## Files

- `planets_animation.html` - Main animation file (self-contained)
- `noise_texture.png` - Film grain texture (downloaded from original site)
- `planets.png` - Screenshot reference from original site
- `target.png` - Target comparison image
- `current.png` - Current implementation screenshot

## Browser Compatibility

- Chrome/Safari/Edge: Full support with hardware acceleration
- Firefox: Full support
- Mobile browsers: Optimized responsive version

## Inspiration

This animation is a faithful recreation of the beautiful planetary animation found on the Future Memories website, a design studio based in Gothenburg, Sweden. The original implementation showcases modern web design trends including film grain textures, atmospheric gradients, and smooth CSS animations.

## Development Process

The recreation process involved:
1. Analyzing the original site's HTML/CSS structure
2. Extracting exact color values and blur parameters
3. Downloading and implementing the authentic noise texture
4. Fine-tuning positioning and scale for accuracy
5. Optimizing for performance and responsiveness

---

*Created with attention to detail and respect for the original design.*