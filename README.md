# SHADOWNET

SHADOWNET is a lightweight, single-page web interface that visualizes a global network layer using a 3D interactive Earth. It is designed as a conceptual representation of distributed connectivity, routing, and secure data flow across a global infrastructure.

The project combines WebGL-based rendering with animated network arcs to simulate real-time communication paths between nodes around the world. It is optimized for fast loading, minimal dependencies, and CDN deployment.

---

## What SHADOWNET is

SHADOWNET is a KUBIK service, a "network" layer for faster deployment.
It is inspired by:
- global networking infrastructure
- DNS and routing systems
- distributed edge computing
- cybersecurity visualization concepts

---

## Features

- 3D interactive rotating Earth
- Animated global connection arcs
- Randomized node distribution across the globe
- Minimal dark UI with futuristic styling
- Boot/loading animation sequence
- Mobile-responsive layout
- Auto-rotating camera system
- CDN-ready static deployment

---

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Globe.gl (Three.js-based WebGL engine)
- Google Fonts (Orbitron)

---

## How it works

- A 3D globe is rendered using WebGL
- Random points are generated across the globe
- Animated arcs connect random nodes to simulate traffic flow
- The globe continuously rotates to create a dynamic network visualization
- A loading screen initializes before rendering begins

---

## Performance

SHADOWNET is optimized for fast delivery and can be hosted as a static file. For best performance:

- Uses Cloudflare or any CDN for caching
- Serves as a static HTML page
- Avoid unnecessary JavaScript splitting

---

## Important note

SHADOWNET is a visual simulation only. It does not process real network traffic, DNS requests, or routing operations.

---

## Credits

- Globe.gl for 3D globe rendering
- Three.js ecosystem
- Public domain Earth textures
- Custom UI and visualization design
