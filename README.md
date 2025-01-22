# Lottie Animation Example

[**Live Demo**](https://rafabeznos.com.br/fx/lottie/door/index.html)

## Overview
This project demonstrates the use of Lottie animations combined with audio and dynamic visual effects. A door animation (`door.json`) plays upon user interaction, followed by an eye animation (`eye.json`) layered over the door. The animations are enriched with transitions, background color changes, and synchronized audio effects (`door.mp3`) for a captivating experience.

---

## Features
- **Interactive Animation**: The door animation starts when clicked.
- **Audio Synchronization**: Audio (`door.mp3`) is delayed to sync with the animation.
- **Layered Animations**: An eye animation appears after the door animation completes.
- **Dynamic Background**: Background color transitions from black to white.
- **Smooth Transitions**: Includes fade-in and color transitions for a polished look.

---

## Technologies Used
- **Lottie Player**: For rendering and managing animations.
- **HTML**: For structure and embedding animations.
- **JavaScript**: For interaction logic, animation control, and audio synchronization.

---

## Installation
### Prerequisites
- A modern web browser (Google Chrome, Firefox, or Edge recommended).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/rafabez/lottie_animation_example.git
   ```
2. Navigate to the project folder:
   ```bash
   cd lottie_animation_example
   ```
3. Ensure the following files are in the project folder:
   - `index.html`
   - `door.json` (Lottie animation for the door)
   - `eye.json` (Lottie animation for the eye)
   - `door.mp3` (Audio file for the door sound)
4. Open `index.html` in your browser.

---

## Usage
1. Open the `index.html` file in your browser.
2. Click on the door animation to:
   - Play the door animation.
   - Trigger synchronized audio playback.
   - Display the eye animation after the door completes.
3. Observe the background transitioning from black to white after the animations.

---

## File Structure
```
lottie_animation_example/
├── index.html       # Main HTML file
├── door.json        # Lottie animation file for the door
├── eye.json         # Lottie animation file for the eye
├── door.mp3         # Audio file for door sound
└── README.md        # Project documentation
```

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- [LottieFiles](https://lottiefiles.com/) for providing the animation library and assets.
- Inspiration from interactive web animations and creative coding projects.

---

## Contact
For questions or feedback, please reach out to:
- **GitHub**: [Rafael Beznos](https://github.com/rafabez)

