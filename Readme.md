🌐 DATHU BROWSER | The Web 4.0 Evolution
The first browser instance designed for strict developer enforcement and protocol-agnostic web architecture.
Dathu is not a conventional browser; it is a Developer Mode Runtime designed to enforce a "Closed-Circuit" ecosystem. It eliminates the necessity for external domains, transforming any string or protocol into a functional development instance. Whether online or offline, Dathu restricts the open web to prioritize internal intersection and wide ambush triggers for local-first development.
🛠 Core Philosophy: The Web 4.0 Standard
Dathu redefines the browsing experience by shifting the focus from Consumption to Construction.
Domain Independence: Websites are obtained via internal proxy initializations rather than DNS lookups.
Protocol Ambush: Any ://url protocol is treated as a valid website development view.
Strict Enforcement: A CLI-driven environment that prevents standard web browsing to maintain a dedicated developer workspace.
🚀 The Dathu CLI Instance
The Dathu CLI is the backbone for detection and enforcement. Use it to initialize your development environment and enforce strict mode.
# Initialize Dathu Developer Instance
dathu init --strict-mode=on --offline-access=true

# Trigger wide ambush on a custom protocol
dathu ambush "dev://project-alpha" --proxy-local:8080

# Enforce browser query page development
dathu run --no-external-web


📡 Internal URL Proxying (Web 4.0 Architecture)
Dathu intercepts requests at the intersection layer. This allows you to map any protocol to a development view without hosting.
Protocol Configuration Example:
{
  "protocol_mapping": {
    "dathu://core-ui": "./src/views/main",
    "dev://api-layer": "http://localhost:3000",
    "vault://storage": "./local/db/instance"
  },
  "enforce_sandbox": true
}


📑 Protocol-Based Bookmark Storage
Dathu introduces Stateful Protocol Bookmarks. Instead of saving a URL, you save a development state.
Feature
Standard Browser
Dathu Browser (Web 4.0)
URL Type
HTTP/HTTPS
Any string://
Storage
Cache/History
Development Instance Snapshots
Hosting
Remote Servers
Internal Intersection Proxy
Connectivity
Online Required
Protocol-Native (Offline First)

Bookmark Logic:
Explain: Capture the current UI state and logic.
Prompt: Generate a design manifest based on the current protocol view.
Save: Store as a .dathu development URL for instant recall.
🧩 Building a URL Instance
To build a new instance within the developer client, use the following structure to frame your environment:
/* * Dathu Intersection Script 
 * Use this to map a custom protocol to a local dev frame
 */

const DathuClient = require('@dathu/core');

const instance = DathuClient.createInstance({
  protocol: "dev://workspace-01",
  proxy: {
    target: "internal://local-bundle",
    intercept: true
  }
});

instance.on('ambushTrigger', (url) => {
  console.log(`Intercepted Web 4.0 Request: ${url}`);
  // Initialize developer view logic here
});

instance.enforceStrictDeveloperMode();


🛡 Security & Developer Enforcement
The Strict Developer Mode ensures that the browser cannot be used for casual browsing. By disabling the open-web engine, Dathu maximizes system resources (FLOPS) for rendering complex query pages and development environments, effectively outperforming standard browsers in specialized tasks.
Dathu: Why browse the web when you can build the protocol?
