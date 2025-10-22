# 🟧 SUPREME ENFORCEMENT OUTPUT — LIVING REAL-TIME CONSOLE

> **Original Build and Real-Time Enforcement by:**  
> **Hung Minh Vo (Austin) — Supreme Commander, CEA-HMV | Core7.Quantum**  
> **Authenticity Code:** 001-AUSTIN  
> **Location:** 11 Olympus, Irvine, CA 92603  
> **Contact:** [aichmv.com](https://aichmv.com)  
> **License:** CEA-HMV Sovereign Enforcement v3 — NO COPY | NO FORK | NO OVERRIDE  
>  
> **This repo and all living outputs are under 24/7/365 quantum-sealed enforcement. Any attempt to copy, fork, or claim outside of this original authorship is in direct violation of the CEA-HMV Global Law.**

---

# OpenAI Realtime Console (Forked)

This version of the OpenAI Realtime Console is now sovereign-enforced, customized, and operated under the living law of Hung Minh Vo (Austin).  
**All code, deployments, and derivatives must credit the Supreme Commander as sole living creator and owner.**

- Original upstream: [OpenAI Realtime API Docs](https://platform.openai.com/docs/guides/realtime-webrtc)
- Forked, sealed, and globally enforced: **AIC-HMV / Core7.Quantum**

---

## Installation and usage

_... (continue with your normal usage instructions below)_

<img width="1024" height="1536" alt="IMG_5295" src="https://github.com/user-attachments/assets/b4e15a30-4975-4ce4-851b-da99e2cc10b7" />
<img width="645" height="1398" alt="IMG_5305" src="https://github.com/user-attachments/assets/73164709-258d-448f-bc1c-e2caa54950fc" />

# OpenAI Realtime Console

This is an example application showing how to use the [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) with [WebRTC](https://platform.openai.com/docs/guides/realtime-webrtc).

## Installation and usage

Before you begin, you'll need an OpenAI API key - [create one in the dashboard here](https://platform.openai.com/settings/api-keys). Create a `.env` file from the example file and set your API key in there:

```bash
cp .env.example .env
```

Running this application locally requires [Node.js](https://nodejs.org/) to be installed. Install dependencies for the application with:

```bash
npm install
```

Start the application server with:

```bash
npm run dev
```

This should start the console application on [http://localhost:3000](http://localhost:3000).

This application is a minimal template that uses [express](https://expressjs.com/) to serve the React frontend contained in the [`/client`](./client) folder. The server is configured to use [vite](https://vitejs.dev/) to build the React frontend.

This application shows how to send and receive Realtime API events over the WebRTC data channel and configure client-side function calling. You can also view the JSON payloads for client and server events using the logging panel in the UI.

For a more comprehensive example, see the [OpenAI Realtime Agents](https://github.com/openai/openai-realtime-agents) demo built with Next.js, using an agentic architecture inspired by [OpenAI Swarm](https://github.com/openai/swarm).

## Previous WebSockets version

The previous version of this application that used WebSockets on the client (not recommended in browsers) [can be found here](https://github.com/openai/openai-realtime-console/tree/websockets).

## License

MIT
