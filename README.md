# Browser-Based Teleprompter

A simple, efficient teleprompter application that runs in your web browser. Features mirrored text display and Bluetooth presenter compatibility.

## Features

- 🪞 Mirrored text display
- 🎮 Bluetooth presenter support
- ⚡ Adjustable scroll speed
- 📱 Responsive design
- 🔄 Toggle between mirrored and normal view
- 👥 Optional split-screen mode
- 📝 External transcript loading

## Setup

1. Ensure both files are in the same directory:
   ```
   your-directory/
   ├── teleprompter.html
   └── transcript.txt
   ```

2. Open `teleprompter.html` in a web browser
   - For best results, use Chrome or Firefox
   - Enable full screen mode (F11) for optimal viewing

## Controls

### On-Screen Controls
- **Reset**: Return to the beginning of the text
- **Start/Stop**: Toggle auto-scrolling
- **Toggle Mirror**: Switch between mirrored and normal view
- **Toggle Split**: Enable/disable split-screen mode
- **Speed Controls**: Adjust scrolling speed with + and - buttons

### Keyboard/Presenter Controls
- **Space Bar**: Start/Stop scrolling
- **Up Arrow**: Scroll up
- **Down Arrow**: Scroll down
- **Home**: Return to top
- Most Bluetooth presenters will map to these keys automatically

## Transcript Format

The `transcript.txt` file supports special markers for timing and pacing:
- `[PAUSE]`: Indicates a natural pause point
- `[SLOW]`: Indicates sections to be read more slowly
- `[END]`: Marks the end of the transcript

Example:
```
This is a sample line. [PAUSE]

This should be read more slowly. [SLOW]

This is the final line. [END]
```

## Customization

### Text Formatting
- Edit `transcript.txt` to change the displayed text
- Use double line breaks between paragraphs
- Add markers ([PAUSE], [SLOW], [END]) as needed

### Styling
Adjust in `teleprompter.html`:
- Font size: Modify `.script { font-size: 24px; }`
- Colors: Change pause/slow marker colors
- Width: Adjust maximum width of text container

## Browser Support
- Chrome (Recommended)
- Firefox
- Safari
- Edge

## Tips for Use
1. Test your Bluetooth presenter before a live session
2. Adjust scroll speed to match your natural reading pace
3. Use full screen mode for best visibility
4. Practice with the timing markers for smooth delivery

## Troubleshooting

### Common Issues
1. **Text not loading**
   - Verify both files are in the same directory
   - Check transcript.txt file permissions
   - Ensure proper file encoding (UTF-8)

2. **Presenter not working**
   - Check presenter battery
   - Verify presenter is paired with device
   - Test keyboard controls as fallback

3. **Scroll issues**
   - Clear browser cache
   - Try a different browser
   - Check for JavaScript errors in console

## License

This is free and unencumbered software released into the public domain. See the UNLICENSE file for more details.