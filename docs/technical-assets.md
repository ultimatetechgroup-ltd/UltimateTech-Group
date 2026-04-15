# Technical Assets & Digital Ecosystem

This document provides a high‑level inventory of the publicly accessible digital assets and underlying technology stacks owned and operated by UltimateTech Group Ltd and its subsidiaries.

## 1. Corporate Web Presence

| Property | URL | Purpose |
|----------|-----|---------|
| **Group Hub** | [ultimatetechgroup.site](https://ultimatetechgroup.site) | Central corporate identity, news, and governance. |
| **Fintech Portal** | [ultimatetechent.site](https://ultimatetechent.site) | Client portal for IT services and XT‑Series hardware support. |
| **Capital Markets** | [ultimatetechcapital.site](https://ultimatetechcapital.site) | Secure login gateway for trading accounts and market analysis. |
| **FX Services** | [4reignxchange.site](https://4reignxchange.site) | Institutional interface for liquidity and settlement information. |

## 2. Proprietary Hardware (XT‑Series)

**Asset:** XT‑Series Payment Terminal
- **Description:** A custom‑engineered, Linux‑based payment terminal designed for high‑volume enterprise environments.
- **Key Feature:** **Hardware Root of Trust (HRoT)** – Cryptographic keys are sealed to the physical silicon, making remote extraction virtually impossible.
- **Status:** Deployed with select institutional partners. *(Public specifications not available due to security constraints).*

## 3. Financial Technology Stack

- **Trading Platforms:** Full integration with **MetaTrader 4 (MT4)** and **MetaTrader 5 (MT5)** . The Group maintains its own bridge and gateway infrastructure for both platforms, bypassing standard third‑party aggregators.
- **Web Interface:** Proprietary **WebTrader 2.0** (React/TypeScript frontend, connecting via secured WebSocket to our private Equinix NY4/LD4 infrastructure).
- **Mobile Connectivity:** Native iOS and Android applications utilizing certificate pinning to prevent man‑in‑the‑middle (MITM) attacks on public networks.

## 4. Security Infrastructure

- **Architecture:** Zero‑Trust Network Access (ZTNA).
- **Encryption Standard:** TLS 1.3 (Strict Mode) for all external traffic; internal communication utilizes **WireGuard** tunnels with post‑quantum cryptographic ciphers where applicable.
- **DNS Security:** Proprietary internal resolver with DNSSEC validation and blocklisting of newly registered malicious domains.

## 5. Intellectual Property

The UltimateTech Group logo, the term "XT‑Series," and the slogan *"Securing Tomorrow, Powering Payments"* are registered trademarks of UltimateTech Group Ltd. Unauthorized use of our branding is actively monitored and enforced.
