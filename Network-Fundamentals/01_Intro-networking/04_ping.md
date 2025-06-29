## 📶 Ping (ICMP) Internet Control Message Protocol
**Ping** is a network utility used to test if a device is reachable over a network.

It works by sending a special message called an **ICMP Echo Request** to a target IP, and waits for an **ICMP Echo Reply**.

###  Key Points:
- Uses **ICMP** (Internet Control Message Protocol)
- Helps check **connectivity** and **response time**
- Measures **latency** (delay between request and reply)
- If no reply is received, the device may be **offline**, **blocked**, or **unreachable**

### Example:
```bash
ping 8.8.8.8
