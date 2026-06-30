# How to Make an Up Next Bumper

An "Up Next" bumper is a short, animated sequence used in television broadcasts to tease the next show or segment. This guide covers the fundamentals of creating one in Adobe After Effects.

## Overview
An Up Next bumper typically includes:
- **Show/segment title** with animated text
- **Preview imagery** or footage from the next content
- **Branding elements** (logos, transitions)
- **Duration**: 3-5 seconds
- **Audio**: Music sting or voiceover

---

## Step 1: Set Up Your Project

1. **Create a new composition**
   - File → New → Composition
   - Set dimensions: **1920 × 1080** (HD) or **1280 × 720** (SD)
   - Set frame rate: **29.97 fps** (NTSC) or **25 fps** (PAL)
   - Set duration: **5 seconds** (300 frames for 29.97)

2. **Organize your layers**
   - Create adjustment layers for color grading
   - Use null objects to group and animate related elements

---

## Step 2: Create the Background

1. **Add a solid color layer** or gradient background
   - Layer → New → Solid
   - Choose a color that matches your brand

2. **Apply effects for visual interest**
   - Add subtle texture or pattern
   - Consider adding a gradient overlay

3. **Add background footage/imagery** (optional)
   - Import preview footage from the next show
   - Adjust opacity and position
   - Apply effects if needed (blur, color correction)

---

## Step 3: Add Text Elements

### Title Text
1. **Create the main title**
   - Select Text Tool (Ctrl+T / Cmd+T)
   - Click on the canvas to add text
   - Type the show/segment name
   - Format: Choose appropriate font (sans-serif works well)
   - Size: Large enough to read at broadcast resolution

2. **Animate the text entrance**
   - Select the text layer
   - Position at 0 frames where you want it to start
   - Set initial properties (opacity: 0%, scale: 80%)
   - Move to frame 10 and change to final state (opacity: 100%, scale: 100%)
   - Add easing for smooth motion

### "Up Next" Label
1. **Create secondary text** saying "Up Next" or similar
   - Use smaller font size
   - Position above or beside the main title
   - Animate with slight delay after main title

---

## Step 4: Create Animated Transitions

### Entrance Effect
1. **Scale and Position Animation**
   - Add keyframes for Position and Scale
   - Frame 0: Position off-screen, Scale: 50%
   - Frame 15: Position center, Scale: 100%

2. **Opacity Fade-In**
   - Add Opacity keyframe at frame 0: 0%
   - Add Opacity keyframe at frame 10: 100%

### Exit Effect
1. **Reverse the entrance**
   - Frame 270: Position center, Scale: 100%, Opacity: 100%
   - Frame 285: Position off-screen, Scale: 50%, Opacity: 0%

---

## Step 5: Add Effects and Polish

### Motion Graphics
1. **Add separator bars or accent lines**
   - Use shape tools to create geometric elements
   - Animate them sliding in
   - Layer → New Shape Layer

2. **Keyframe animation tips**
   - Use easing: Easy Ease (F9) for smooth motion
   - Adjust easing curves in Graph Editor (Shift+F3)
   - Overshoot: -10% to -20% for lively feel

### Color and Visual Effects
1. **Color grading**
   - Add Levels or Curves adjustment layer
   - Match your broadcast color standards

2. **Glow or shadow effects**
   - Layer → Layer Styles
   - Or use Effect → Light and Shadow

---

## Step 6: Add Audio

1. **Import music or sound effect**
   - File → Import → File
   - Drag audio layer to timeline

2. **Sync with animation**
   - Music sting should align with text entrance
   - Voiceover timing (if using): Place at frame 30-40

3. **Audio levels**
   - Check audio levels in the Audio Meters panel
   - Keep peaks around -6dB for safe broadcast levels

---

## Step 7: Preview and Render

### Preview
1. **RAM Preview** (0 on numeric keypad)
   - Watch full animation to check timing
   - Listen for audio sync issues

2. **Real-time preview options**
   - Draft quality: Spacebar for quick preview
   - Full quality: Use RAM Preview for final check

### Render
1. **Set up render queue**
   - Composition → Add to Render Queue
   - Set output module format (ProRes, DNxHD for broadcast)

2. **Render settings**
   - Resolution: Full (1:1)
   - Color depth: 8-bit or 16-bit
   - Audio output: Enabled

3. **Export**
   - Set output filename and location
   - Press Render

---

## Pro Tips

- **Keep it fast-paced**: Quick cuts and animations grab attention
- **Brand consistency**: Use your show's color palette and fonts
- **Safe area**: Keep important elements within the 80% safe area for older TVs
- **Template reuse**: Save as template for quick updates
- **Test on TV**: Preview on actual broadcast monitor if possible
- **Duration**: Aim for 3-5 seconds; shorter is punchier

---

## Common Bumper Variations

### Static Bumper
- Minimal animation
- Focus on bold text and imagery
- Used for lower-third graphics

### Dynamic Bumper
- Multiple animated elements
- Transitions between scenes
- Music-driven pacing

### Transition Bumper
- Used between segments
- Often features show logos
- Background may change color/style

---

## Resources

- **Adobe After Effects Help**: helpx.adobe.com/after-effects
- **Broadcast Standards**: EBU (R128) for audio levels
- **Color Space**: Rec. 709 for broadcast HD

---

**Questions? Test and iterate!** The best bumpers come from experimentation and refinement.
