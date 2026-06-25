# r/place 2 — Frontend

GitHub Pages site: https://r-place-2.github.io

This is the static frontend for the r/place 2 collaborative pixel canvas. It connects to a Python WebSocket backend via a tunnel (bore or cloudflared).

## Usage

1. Start the backend server and tunnel (see [r-place-2 repo](https://github.com/r-place-2/r-place-2))
2. Visit `https://r-place-2.github.io/canvas.html?backend=YOUR_TUNNEL_URL`
   - With cloudflared: `?backend=random-name.trycloudflare.com`
   - With bore (HTTP only): `?backend=bore.pub:12345&protocol=ws`

Or use the landing page at `https://r-place-2.github.io/` and enter the URL.
