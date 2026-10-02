Westworld Attribute Matrix
====

Interactive radar chart based on the host attribute matrix from Westworld Season 1 Episode 6 “The Adversary.”

![Demo](README/demo.gif)

A series of archived configurations tells Maeve’s story over the course of the season, while sliders show what it might feel like to configure host attributes directly through the radar chart.

[**Live Demo ›**](http://epassi.co/lab/westworld)

[**About the Project ›**](https://medium.com/@epassi/recreating-the-westworld-attribute-matrix-3e72d9d419df)

## Getting Started

**Prerequisites:** [Node.js](https://nodejs.org/) (npm comes bundled with it). Ruby/Sass is **not** required — this project builds with Dart Sass via npm.

```bash
# Clone the repo
git clone https://github.com/steven-lyles/westworld-attribute-matrix.git
cd westworld-attribute-matrix

# Install dependencies
npm install

# Build and start a local dev server with live-reload
grunt
```

`grunt` (same as `grunt dev`) compiles the Sass, lints and transpiles the JS, bundles everything into `builds/dev`, and serves it at `http://localhost:3000` with live-reload via BrowserSync. Press `Ctrl+C` to stop the watch task when you're done.