# Hi, I'm e46dream 👋

I build privacy-first web utilities and developer APIs focused on transparency, client-side execution, and zero IP logging.

---

### 🛡️ Featured Project: [ScanMyPrivacy](https://scanmyprivacy.com)

**ScanMyPrivacy** is a free browser-based privacy, leak-testing, and online safety toolkit—paired with a lightweight **IP & Network Lookup API**—designed to show what connections expose without logging visitor IP addresses.

#### ⚡ Quick API Example
```bash
curl -s "https://scanmyprivacy.com"
```

```json
{
  "ip": "8.8.8.8",
  "country": "United States",
  "city": "Mountain View",
  "asn": "AS15169",
  "org": "Google LLC",
  "is_vpn_or_hosting": true
}
```

#### 🔍 Core Tools
* **Privacy & Leak Diagnostics:** Weighted **Full Privacy Scan** alongside standalone checks for **DNS leaks**, **WebRTC leaks**, **browser fingerprinting**, **VPN/hosting detection**, **open TCP ports**, **HTTP headers**, and **User-Agent / Client Hints**.
* **Online Safety Assistant:** Client-side analyzers for **suspicious links**, **scam/phishing messages**, **mobile app permissions**, and **website TLS/HTTPS certificates, security headers, and RDAP domain age**.
* **Pre-Consent Cookie & Tracker Scanner:** Audits third-party trackers and cookies loaded before user consent, **Google Consent Mode (`gcs`)** state, first-layer reject options, and **Global Privacy Control (GPC)** compliance.
* **IP & Network Lookups:** Fast **IPv4/IPv6**, **geolocation**, **RDAP**, **DNS**, and **Reverse DNS (PTR)** lookups powered by our JSON API.

#### 🔒 Privacy-by-Design Architecture
* **Client-Side First:** Fingerprint, WebRTC, link, scam-message, and security checkup analyses run directly in the user's browser with zero server uploads.
* **Zero IP Logging:** Visitor IP addresses are never written to logs or databases; ephemeral DNS test tokens expire automatically after 10 minutes.
* **Transparent Scoring:** Every check reports explicit confidence levels, methodology limits, and third-party network calls.

🔗 **[Live Site](https://scanmyprivacy.com)** · **[IP API Docs & Pricing](https://scanmyprivacy.com)** · **[Methodology & Data Handling](https://scanmyprivacy.com)**
