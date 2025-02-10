# Analog & Digital Clock

A responsive web-based clock featuring both analog and digital displays, built with HTML, CSS, and JavaScript.

## Features
- Real-time analog clock with hour, minute, and second hands
- Synchronized digital time display
- Gradient background with customizable clock face
- Responsive design that scales with viewport width
- Smooth hand rotations

## Setup
1. Clone the repository
2. Ensure `clock.jpg` is in the root directory
3. Open `analog.html` in a browser

## File Structure
```
Analog/
│── analog.html
│── analog.css
│── analog.js
│── clock.jpg
```

## Customization

### CSS Variables
Modify colors and dimensions in `analog.css`:
```css
.clock {
    height: 40vw;
    width: 40vw;
    background: linear-gradient(to right, yellow, pink);
}
```

### Hand Styles
Adjust hand dimensions and colors:
```css
#hour {
    height: 25%;
    width: 1.8%;
}
```

## Technical Details
- Uses CSS transforms for smooth hand rotation
- Time calculations: 
  - Hour hand: 30° × hours + minutes/2
  - Minute hand: 6° × minutes
  - Second hand: 6° × seconds

## License
MIT License

## Author
Lalitha kuppa

