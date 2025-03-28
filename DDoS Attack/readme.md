# Distributed Denial of Service (DDoS) Attack

## Introduction

A **Distributed Denial of Service (DDoS) attack** is a malicious attempt to disrupt the normal traffic of a targeted server, service, or network by overwhelming it with a flood of Internet traffic. These attacks originate from multiple sources, often through a botnet of compromised devices.

## How DDoS Attacks Work

DDoS attacks typically involve the following steps:

1. **Botnet Creation** – Attackers infect multiple devices with malware to form a botnet.
2. **Target Selection** – The attacker chooses a specific server or network to attack.
3. **Traffic Overload** – The botnet floods the target with excessive traffic, causing service disruption.

## Types of DDoS Attacks

DDoS attacks can be classified into three main types:

### 1️⃣ Volume-Based Attacks

These attacks flood the target with massive amounts of traffic, exhausting bandwidth.

- **UDP Flood** – Overloads the target with User Datagram Protocol (UDP) packets.
- **ICMP (Ping) Flood** – Sends continuous ping requests to overwhelm the system.
- **DNS Amplification** – Exploits DNS servers to amplify the attack traffic.

### 2️⃣ Protocol Attacks

These exploit weaknesses in network protocols to consume server resources.

- **SYN Flood** – Overloads a server by initiating multiple incomplete TCP connections.
- **Ping of Death** – Sends malformed packets to crash or freeze the target system.
- **Smurf Attack** – Uses ICMP requests to create traffic spikes.

### 3️⃣ Application-Layer Attacks

These attacks target the application layer (Layer 7), mimicking real users.

- **HTTP Flood** – Overloads web servers with excessive HTTP requests.
- **Slowloris** – Keeps multiple connections open by sending partial requests.
- **DNS Query Flood** – Overloads DNS servers with fake queries.

## Real-World DDoS Attack Examples

### 🔹 **GitHub (2018)** – Hit with a **1.35 Tbps** DDoS attack using Memcached amplification.

### 🔹 **Dyn DNS Attack (2016)** – The Mirai botnet took down Twitter, Netflix, and PayPal.

### 🔹 **Estonia (2007)** – Politically motivated DDoS attack disrupted government and banking services.

## Detecting a DDoS Attack

To detect a DDoS attack, monitor for:

- **Sudden Traffic Spikes** – Unusual traffic volume from multiple IPs.
- **Service Slowdowns** – Websites or applications becoming unresponsive.
- **Irregular Traffic Patterns** – High requests per second from a single source.

## How to Prevent and Mitigate DDoS Attacks

### ✅ **Network Security Measures**

- Deploy **Web Application Firewalls (WAFs)** to filter traffic.
- Use **rate limiting** to restrict excessive requests.
- Implement **geo-blocking** to block suspicious regions.

### ✅ **Infrastructure Protection**

- Use **CDN and Load Balancers** to distribute traffic.
- Subscribe to **DDoS protection services** like Cloudflare, AWS Shield, or Akamai.
- Monitor **network traffic** for anomalies.

### ✅ **IoT & Endpoint Security**

- Secure **IoT devices** with strong passwords and firmware updates.
- Implement **Intrusion Detection Systems (IDS)** to detect compromised devices.

## Conclusion

DDoS attacks remain a major cybersecurity threat, causing service disruptions and financial losses. Organizations must implement **strong security measures** to detect, prevent, and mitigate such attacks effectively.
