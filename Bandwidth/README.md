## What is Bandwidth?

Bandwidth refers to the amount of **data transferred** or the **capacity
of a channel** (network, system, or signal) within a given time. It is
typically measured in **bits per second (bps)** for speed or **bytes
transferred (GB/TB)** for data usage.

Think of bandwidth like a highway - the more lanes it has, the more cars (data) can travel on it simultaneously.
A higher bandwidth connection allows more information to flow through at once,
resulting in faster downloads, smoother streaming, and better overall network performance.

------------------------------------------------------------------------

## Types of Bandwidth

### 1. Network / Internet Bandwidth

-   **Download Bandwidth**: Speed of receiving data from the internet to
    your device/server.\
    Example: Streaming a movie, downloading files.\
-   **Upload Bandwidth**: Speed of sending data from your device/server
    to the internet.\
    Example: Uploading files, video calls, sending emails with
    attachments.\
-   **Symmetric Bandwidth**: Equal upload and download speeds (common in
    fiber internet).\
-   **Asymmetric Bandwidth**: Unequal speeds, usually higher download
    and lower upload (common in DSL, cable internet).

------------------------------------------------------------------------

### 2. System / Computer Bandwidth

-   **Memory Bandwidth**: The rate at which data is transferred between
    RAM and CPU.\
    Higher memory bandwidth = faster system performance.\
-   **Bus Bandwidth**: Capacity of system buses (PCIe, USB, etc.) to
    transfer data between components.\
-   **Storage Bandwidth**: Read/write speeds of storage devices (HDDs,
    SSDs, NVMe).\
-   **Graphics Bandwidth**: Data transfer rate between GPU and video
    memory (VRAM). Important for gaming, 3D rendering, and AI workloads.

------------------------------------------------------------------------

### 3. Signal / Frequency Bandwidth

-   **RF Bandwidth**: The range of radio frequencies a device can handle
    (e.g., Wi-Fi, 4G, 5G).\
-   **Audio Bandwidth**: Frequency range of audio signals (20Hz--20kHz
    for human hearing).\
-   **Video Bandwidth**: Frequency range required to transmit video
    signals. Higher resolution = higher bandwidth.\
-   **Optical Bandwidth**: Range of light frequencies in fiber optic
    communication systems.

------------------------------------------------------------------------

### 4. Network Technology Types

-   **Baseband**: Uses the entire channel bandwidth for a single signal
    (e.g., Ethernet).\
-   **Broadband**: Divides bandwidth into multiple channels to carry
    multiple signals (e.g., cable TV, cable internet).\
-   **Narrowband**: Very limited bandwidth channels (e.g., dial-up
    modems, some IoT communication).

------------------------------------------------------------------------

### 5. Measurement Classifications

-   **Theoretical Bandwidth**: Maximum possible speed or capacity under
    ideal lab conditions.\
-   **Effective Bandwidth**: Real-world usable capacity after
    considering delays, errors, and overhead.\
-   **Available Bandwidth**: The portion of total capacity that is
    currently unused and available.

------------------------------------------------------------------------

## How Hosting Providers Count Bandwidth

-   **Inbound Bandwidth**: Data flowing **into the server** from the
    internet (usually free).\
-   **Outbound Bandwidth**: Data flowing **out of the server** to the
    internet (usually billed).

Example:\
- Plan includes **5 TB outbound** per month.\
- **Inbound (downloads/uploads to server)** = 12 GB (not billed).\
- **Outbound (users accessing your site)** = 1.5 TB (counts toward
quota).

------------------------------------------------------------------------

## Exceeding Bandwidth Quota

-   No downtime --- your server continues working.\
-   Extra usage is billed (e.g., Vultr = \$0.01/GB → \$10 per extra TB).

Example:\
- Quota = 5 TB outbound.\
- Actual usage = 7.2 TB outbound.\
- Extra = 2.2 TB → \$22 additional charges.

------------------------------------------------------------------------

## Tips to Optimize Bandwidth

-   **Use a CDN (e.g., Cloudflare)**: Cache static files (images, CSS,
    JS).\
-   **Enable Compression (Gzip/Brotli)**: Reduce web asset sizes.\
-   **Optimize Media Files**: Use efficient formats (WebP, HEVC, etc.).\
-   **Monitor Usage**: Use tools like `vnstat`, `iftop`, or provider
    dashboards.\
-   **Upgrade Plan**: If usage always exceeds quota, a larger plan may
    be more cost-effective.

------------------------------------------------------------------------

## Summary

-   **Bandwidth** = data capacity or transfer rate.\
-   **Inbound** = data into server (usually free).\
-   **Outbound** = data out of server (usually billed).\
-   Different contexts (network, computer, signal, etc.) have their own
    bandwidth definitions.\
-   Exceeding quotas costs money, but doesn't stop service.
