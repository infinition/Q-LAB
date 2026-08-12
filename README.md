<img width="336" height="328" alt="image-removebg-preview (6)" src="https://github.com/user-attachments/assets/d6b05f9e-fe8f-46be-a95c-a1ef2a858606" />

 
 # Q-LAB: Gridworld AI Simulator

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) [![Release](https://img.shields.io/github/v/release/infinition/Q-LAB?style=flat)](https://github.com/infinition/Q-LAB/releases) [![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/infinition)

A high-performance, zero-dependency visualization of Reinforcement Learning running entirely in the browser.

Watch an AI agent learn to navigate complex mazes using the Q-Learning algorithm. You can customize the environment layout, adjust hyperparameters in real time, or toggle Turbo Mode to train the agent at maximum computational speed.

[Live Demo](https://infinition.github.io/Q-LAB/)

<img width="905" height="592" alt="Gridworld simulator view" src="https://github.com/user-attachments/assets/de433138-55f0-4a3b-9049-b58bedf3f8b1" />

<img width="914" height="587" alt="Gridworld simulator training stats" src="https://github.com/user-attachments/assets/dd5d26d1-0a7a-4a2a-b863-53e2c3dc6466" />

## Features

- **Real-time Tuning**: Adjust learning rates, exploration rates (epsilon), and discount factors (gamma) dynamically via sliders.
- **Turbo Mode**: Speed up execution past 85% to disable rendering and train the agent at maximum speed.
- **Interactive Map Editor**: Draw custom grids with walls, mud (slow zones), ice (slippery zones), and portals for teleportation.
- **Visual Overlays**: Toggle visualization overlays including Policy Arrows, Heatmaps, and the optimal path layout.

## Quick Start

This project has no external build steps or dependency installation required.

1. Download the `index.html` file.
2. Open `index.html` directly in any modern web browser.
3. Use the control panel to customize parameters and start training.

## Technical Details

- **Single-File Architecture**: HTML, CSS, and JavaScript are bundled in a single standalone file.
- **HTML5 Canvas**: Used for high-frequency grid and path rendering.
- **Chart.js**: Handles live plotting of scores and training metrics.

## Star History

<a href="https://www.star-history.com/?repos=infinition%2FQ-LAB&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=infinition/Q-LAB&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=infinition/Q-LAB&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=infinition/Q-LAB&type=date&legend=top-left" />
 </picture>
</a>

## License

MIT. See [LICENSE](LICENSE).
