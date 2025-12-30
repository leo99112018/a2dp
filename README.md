
# 🌐 **[Landing Page / Dashboard Website](zxcvresque.github.io/a2dp/)**

## Alternative A2DP Driver for Windows

This repository serves as a mirror and host for the **Alternative A2DP Driver (v1.6.0.1)** and the necessary **DSE Patcher** tools required for installation on modern Windows systems.

### 🚀 Full Installation Guide
For the complete, step-by-step walkthrough, troubleshooting, and community-sourced fixes, please visit our main documentation page:

👉 **[https://rentry.org/a2dp](https://rentry.org/a2dp)**

---

### 🛠 Project Workflow
Because this driver is unsigned, the installation requires a specific sequence to bypass Windows Driver Signature Enforcement (DSE).

```mermaid
graph TD
    A[Download Driver & Patcher] --> B{DSE Status}
    B -- DSE Enabled --> C[Run DSE Patcher]
    B -- DSE Disabled --> D[Install A2DP Driver]
    C --> E[Restart with Test Mode]
    E --> D
    D --> F[Configure Bluetooth A2DP Sink]
    F --> G[Enjoy High Quality Audio]
    
    style C fill:#f96,stroke:#333,stroke-width:2px
    style D fill:#bbf,stroke:#333,stroke-width:2px
