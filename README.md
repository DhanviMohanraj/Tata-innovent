# PulseDrive - Edge AI Vehicle Health & Predictive Maintenance

PulseDrive is a cinematic, futuristic vehicle operating system and predictive maintenance prototype. It is designed to demonstrate high-fidelity telemetry monitoring, predictive failure detection, and an interactive digital twin layout.

## Design Inspiration
PulseDrive combines the spatial grid styling of **Apple Vision Pro**, the clean, minimalist telemetry of **Tesla's UI**, the responsive tracking of **Formula 1 telemetry**, and the deep control interfaces of **NASA Mission Control**.

## Technical Architecture
To ensure high portability and zero-installation launch directly from your local filesystem (`file://` protocol):
- **Core**: React 18 & ReactDOM loaded via ESM/UMD.
- **Transpiler**: Babel Standalone (runs JSX compilation inside the browser, eliminating node compilation builds).
- **Styling**: Tailwind CSS v3 loaded dynamically via CDN, configured with custom colors and glassmorphic box shadows.
- **Graphics & Visualizations**: High-tech SVG vehicle wireframes with custom canvas particle engines for deep glowing background textures.
- **Charts**: Custom-drawn animated SVG graphs that feed off the real-time simulation tick.

## Features
1. **Unified Health Gauge**: Large circular gauge showing vehicle state.
2. **Interactive Digital Twin**: Interactive 3D vector vehicle model. Click on the Front Motor, Battery Floor, Front Radiator, Brake Hubs, or tires to view live temperatures and diagnostic statistics.
3. **Automated Anomaly Simulator**: Located in the Topbar and Settings page. Switch between **Normal Mode**, **Warning Flow** (Coolant leak starts, risk increases), and **Critical Overheat** (Engine temperature spikes, emergency mode overrides color palette to red warnings).
4. **Co-Pilot AI Mechanic**: Ask questions about overheating, battery degradation, mileage, and safe distance limits. Prompt responses dynamically update based on the simulator phase!
5. **Additional Widgets**: Driving Behavior tracking, Carbon CO₂ Savings index, and Journey Readiness parameters.

## How to Run
1. Navigate to the project directory:
   `C:\Users\DELL\.gemini\antigravity\scratch\pulsedrive`
2. Double-click the `index.html` file or open it in Google Chrome, Microsoft Edge, Safari, or Mozilla Firefox.
3. Use the **Demo Controls** in the Top Bar to trigger warnings and showcase the Edge AI response!
