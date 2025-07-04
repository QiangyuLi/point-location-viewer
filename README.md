# Point Location Viewer

An interactive HTML tool for visualizing and managing coordinate point data with file import/export capabilities.

## Features

- **Interactive Point Visualization**: View coordinate points on a grid with customizable names
- **File Import**: Load data from TXT or CSV files with flexible format support
- **Data Export**: Save data to TXT files or copy to clipboard
- **Coordinate Transformation**: Flip X and Y coordinates with one click
- **Real-time Editing**: Edit point names directly in the interface
- **Responsive Design**: Works on desktop and mobile devices

## Usage

### Online Version
Visit: `https://yourusername.github.io/point-location-viewer/`

### Local Usage
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start visualizing your coordinate data!

### Supported File Formats

The tool supports various data formats:

**Comma-separated:**
```
0.5, 0.3, Point1
0.7, 0.8, Point2
```

**Tab-separated:**
```
0.5	0.3	Point1
0.7	0.8	Point2
```

**Space-separated:**
```
0.5 0.3 Point1
0.7 0.8 Point2
```

**CSV with headers:**
```
X,Y,Name
0.5,0.3,Point1
0.7,0.8,Point2
```

## Features in Detail

### Data Management
- Load TXT/CSV files with coordinate data
- Edit point names in real-time
- Export data in tab-separated format
- Copy data to clipboard
- Clear all data with confirmation

### Visualization
- Interactive grid display
- Automatic scaling to fit all points
- Coordinate axis labels
- Point labels with custom names
- Red circles with white borders for high visibility

### Coordinate Operations
- Flip X↔Y coordinates instantly
- Maintains point names during transformations
- Visual feedback for operations

## Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **Canvas-based Rendering**: Smooth and responsive visualization
- **File API**: Modern browser file handling
- **Responsive Design**: Works on various screen sizes

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Any modern browser with HTML5 Canvas support

## Contributing

Feel free to submit issues and pull requests to improve the tool!

## License

MIT License - Feel free to use and modify as needed.
