# Film Photography Exposure Calculator

A simple yet powerful web application for film photographers to calculate proper exposure settings in different lighting conditions. Built with Vue.js and pure HTML/CSS.

**[Try the Live Demo](https://stephenlawson.github.io/Film-Photography-Exposure/)**

## Features

- **Comprehensive Lighting Scenarios**: Choose from various pre-defined lighting conditions, each with its corresponding Exposure Value (EV)
  - Sunny Daylight (EV15)
  - Cloudy (EV13)
  - Golden Hour (EV12)
  - Overcast (EV11)
  - Sunset/Sunrise (EV10)
  - Deep Shade (EV9)
  - Indoors - varying brightness (EV4-8)
  - Night scenes (EV0-3)

- **Complete Exposure Controls**:
  - Film ISO: 25-3200
  - Aperture: f/1.0-f/32 with third-stop increments
  - Shutter Speed: 1/8000s to 60s
  - ND Filters: None to ND1000 (10-stop)

- **Real-time Exposure Feedback**:
  - Visual indicators for proper exposure, underexposure, and overexposure
  - Shows exact number of stops adjustment needed
  - Calculates and displays current Exposure Value (EV)

- **User-Friendly Interface**:
  - Intuitive controls
  - Mobile-responsive design
  - Camera-style settings display

## How to Use

### Basic Operation

1. Select a lighting scenario (e.g., "Sunny Daylight", "Golden Hour", "Indoors")
2. Choose your film's ISO value
3. Adjust aperture and shutter speed to achieve proper exposure
4. Add ND filters if needed (for bright conditions or creative effects)
5. Check the exposure indicator at the bottom:
   - Green: Good exposure
   - Red: Underexposed (shows stops)
   - Yellow: Overexposed (shows stops)

### Advanced Tips

- **Understanding EV (Exposure Value)**: The EV number represents the amount of light in the scene at ISO 100. Higher numbers mean brighter conditions.

- **Exposure Triangle**: Remember that ISO, aperture, and shutter speed all affect exposure:
  - Higher ISO = More light sensitivity = Brighter image
  - Larger aperture (smaller f-number) = More light = Brighter image
  - Slower shutter speed = More light = Brighter image

- **ND Filters**: Use these to reduce light in very bright conditions or to achieve creative effects (like motion blur in daylight).

## Technical Details

- **Built with**: Vue.js 3 (no build step required)
- **Dependencies**: None (Vue.js loaded via CDN)
- **Browser Compatibility**: Works on all modern browsers
- **Offline Capable**: Can be used without internet once loaded

## Deployment

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/stephenlawson/Film-Photography-Exposure.git
   cd Film-Photography-Exposure
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server
   ```

3. Navigate to `http://localhost:8000` in your browser


## License

MIT License - Feel free to use, modify, and distribute this project.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests if you have suggestions for improvements.

## Acknowledgments

- Inspired by traditional light meters and film photography techniques
- Created for photographers transitioning from digital to film
- Developed with love for the analog photography community
