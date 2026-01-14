# Evolum

Evolum is a strongly typed, WebSocket-first platform for building web applications using your preferred language. It brings the desktop development mental model to the web with compile-time safety, predictable UI state, and a server-as-source-of-truth architecture.

## Why Evolum

- Strong typing end-to-end, from UI to logic.
- WebSocket-based, real-time updates by default.
- Server owns the UI state; the browser renders and reflects it.
- Compile-time safety for UI changes and refactors.
- Multi-language friendly architecture.

## Core Concepts

- **Server as the brain**: The server owns the UI state and logic.
- **Client as a renderer**: The browser is a smart renderer and event forwarder.
- **Live connection**: WebSocket keeps UI state in sync in real time.
- **Typed UI**: Components, properties, and events are strongly typed.

## How It Works (High-Level)

1. Browser connects via WebSocket.
2. Server sends UI structure, types, and initial state.
3. Browser renders the UI and binds events.
4. User actions are sent to the server as events.
5. Server updates state and sends only the delta.

## Status

Evolum is under active development. Public details, examples, and releases will be announced as they become available.

## Support

If you want to support the project:

- Sponsor: https://github.com/sponsors/talisjonatas
- Donate: https://www.paypal.com/donate/?hosted_button_id=7G2ZLHY3YVZG2
- Code: https://github.com/talisjonatas/evolum

## Community

- GitHub: https://github.com/talisjonatas/evolum
- Discord: https://discord.gg/hKY2wPc5
- WhatsApp: https://chat.whatsapp.com/HjQIM3lDbcx380zLvjLEPp

## License

LGPL
