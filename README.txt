# Volley Rotation Quest

Volley Rotation Quest is a lightweight progressive web app that helps young volleyball players learn court rotations and serve-receive formations through an interactive game.

## Usage

Clone the repository and start a local web server from its root:

```bash
git clone https://github.com/sc1ll1/volley-rotation-quest.git
cd volley-rotation-quest
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser and use the game on a desktop or mobile device. The app is designed for touch-friendly mobile play and can work offline after its first successful load.

The app consists of static HTML, CSS, and JavaScript files, so no package installation or build step is required. Use `localhost` or HTTPS when testing; opening `index.html` directly with `file://` does not enable the service worker.
