# IPv4 Address Classes

IPv4 (Internet Protocol version 4) is the fourth version of the Internet Protocol, used for identifying devices on a network. An IPv4 address is a 32-bit address, divided into four octets, each consisting of 8 bits. It is typically written in decimal form as `xxx.xxx.xxx.xxx`, where each `xxx` is a number between 0 and 255.

## IPv4 Address Structure

- **IPv4 Address Format**: 32 bits (4 octets)
- **Example**: `192.168.1.1`

## IPv4 Address Classes

IPv4 addresses are divided into five main classes based on their first few bits and their intended use. These classes are as follows:

### 1. **Class A**
- **First Octet Range**: `0 to 127` (binary: `00000000` to `01111111`)
- **Address Range**: `0.0.0.0` to `127.255.255.255`
- **Default Subnet Mask**: `255.0.0.0` or `/8`
- **Usage**: Large networks (e.g., large corporations, ISPs)
- **Example**: `10.0.0.1`

#### Key Characteristics:
- The first bit is `0`, indicating Class A.
- Can support up to 16 million hosts per network.

### 2. **Class B**
- **First Octet Range**: `128 to 191` (binary: `10000000` to `10111111`)
- **Address Range**: `128.0.0.0` to `191.255.255.255`
- **Default Subnet Mask**: `255.255.0.0` or `/16`
- **Usage**: Medium-sized networks (e.g., universities, large businesses)
- **Example**: `172.16.0.1`

#### Key Characteristics:
- The first two bits are `10`, indicating Class B.
- Can support up to 65,000 hosts per network.

### 3. **Class C**
- **First Octet Range**: `192 to 223` (binary: `11000000` to `11011111`)
- **Address Range**: `192.0.0.0` to `223.255.255.255`
- **Default Subnet Mask**: `255.255.255.0` or `/24`
- **Usage**: Small networks (e.g., home networks, small businesses)
- **Example**: `192.168.1.1`

#### Key Characteristics:
- The first three bits are `110`, indicating Class C.
- Can support up to 254 hosts per network.

### 4. **Class D** (Multicast)
- **First Octet Range**: `224 to 239` (binary: `11100000` to `11101111`)
- **Address Range**: `224.0.0.0` to `239.255.255.255`
- **Usage**: Reserved for multicast addressing (one-to-many communications)
- **Example**: `224.0.0.1`

#### Key Characteristics:
- The first four bits are `1110`, indicating Class D.
- Used for multicast traffic, such as video streaming and group communication.

### 5. **Class E** (Reserved for Experimental Use)
- **First Octet Range**: `240 to 255` (binary: `11110000` to `11111111`)
- **Address Range**: `240.0.0.0` to `255.255.255.255`
- **Usage**: Reserved for future and experimental use (not for general use)
- **Example**: `250.0.0.1`

#### Key Characteristics:
- The first four bits are `1111`, indicating Class E.
- Reserved for research, testing, and experimentation.

### Special Addresses

- **Loopback Address**: `127.0.0.1` (Class A), used for testing network connectivity on the local machine.
- **Private Addresses**: Used for private networks (not routable on the public internet).
  - Class A: `10.0.0.0` to `10.255.255.255`
  - Class B: `172.16.0.0` to `172.31.255.255`
  - Class C: `192.168.0.0` to `192.168.255.255`

## Real-World Use Cases for IPv4 Address Classes

- **Class A**: Used by large organizations, Internet Service Providers (ISPs), or multinational companies that need a large number of IP addresses.
  - Example: An ISP using a range of Class A addresses to allocate to its customers.
  
- **Class B**: Suitable for medium-sized businesses, universities, or organizations with a moderate number of devices.
  - Example: A university with several departments using a Class B address range for its campus network.

- **Class C**: Commonly used in smaller networks, like home or small business networks.
  - Example: A small office network using private Class C addresses for internal devices.

- **Class D**: Used for applications involving multicast communication, such as streaming, conferencing, and group communications.
  - Example: Streaming services or video conferencing applications using multicast IP addresses.

- **Class E**: Reserved for research and future use, not generally used in practical networking.
  - Example: Research projects or experimental protocols may use Class E addresses.

## IPv4 Classes in a Table

| **Class**  | **First Octet Range** | **Address Range**         | **Default Subnet Mask** | **Usage**                                      | **Example**          |
|------------|-----------------------|---------------------------|-------------------------|------------------------------------------------|----------------------|
| Class A    | 0 to 127              | 0.0.0.0 to 127.255.255.255 | 255.0.0.0 or `/8`       | Large networks (e.g., ISPs, multinational companies) | 10.0.0.1             |
| Class B    | 128 to 191            | 128.0.0.0 to 191.255.255.255 | 255.255.0.0 or `/16`    | Medium-sized networks (e.g., universities, large businesses) | 172.16.0.1           |
| Class C    | 192 to 223            | 192.0.0.0 to 223.255.255.255 | 255.255.255.0 or `/24`  | Small networks (e.g., home networks, small businesses) | 192.168.1.1         |
| Class D    | 224 to 239            | 224.0.0.0 to 239.255.255.255 | N/A                     | Multicast addressing (e.g., video streaming)  | 224.0.0.1            |
| Class E    | 240 to 255            | 240.0.0.0 to 255.255.255.255 | N/A                     | Experimental use (e.g., research, testing)     | 250.0.0.1            |

