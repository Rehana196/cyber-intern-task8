# cyber-intern-task8
The objective of this task was to understand the role of Virtual Private Networks (VPNs) in protecting online privacy and securing internet communications. This was achieved through the hands-on setup and testing of a free VPN client.
## 🎯 Objective
The objective of this task was to understand the role of Virtual Private Networks (VPNs) in protecting online privacy and securing internet communications. This report details the 8-step process I followed, from setup to analysis.

## 🛠️ Tools Used
* **VPN Client:** ProtonVPN (Free Tier)
* **Verification Tool:** `whatismyipaddress.com`
* 
## 1. Task Walkthrough 

Here is a breakdown of the exact steps I took to complete the task:

**Step 1: Choose a reputable free VPN service and sign up.**
* **What I did:** I chose **ProtonVPN**, one of the reputable services suggested in the task materials. I went to their official website and signed up for their free tier.

**Step 2: Download and install the VPN client.**
* **What I did:** I downloaded the official ProtonVPN client for Windows and installed it on my computer.

**Step 3: Connect to a VPN server (choose closest or any location).**
* **What I did:** I launched the ProtonVPN app and logged in. I used the "Fastest free server" option, which automatically connected me to a server in the United States (`US-FREE#155`), as shown in `Screenshot (02)`.

**Step 4: Verify your IP address has changed (use whatismyipaddress.com).**
* **What I did:** This was the key verification step.
    * **Before Connecting:** I checked `whatismyipaddress.com` and confirmed my real public IP was `106.200.27.49`, located in Vijayawada, India (see `Screenshot (01)`).
    * **After Connecting:** I refreshed the same website. It now showed my IP as `37.19.199.153`, located in New York City, USA (see `Screenshot (03)`). This confirmed the VPN was working.
      
**Step 5: Browse a website to confirm traffic is encrypted.**
* **What I did:** By successfully loading `whatismyipaddress.com` twice (before and after), I confirmed that my internet traffic was flowing correctly through the VPN's encrypted tunnel. The ProtonVPN app also showed active traffic (see `Screenshot (02)`).

**Step 6: Disconnect VPN and compare browsing speed and IP.**
* **What I did:** I compared my "before" (`Screenshot (01)`) and "after" (`Screenshot (03)`) screenshots. The IP and location change was the most obvious comparison. I also noted that browsing while on the VPN felt slightly slower, which is a known limitation due to the encryption and distance the data has to travel.

**Step 7: Research VPN encryption and privacy features.**
* **What I did:** I researched the key concepts from the task PDF. I learned that VPNs use **tunneling protocols** (like `WireGuard`, which my client used [see `Screenshot (02)`]) and **encryption** (like AES-256) to scramble data and make it unreadable to my ISP or anyone on a public network.

**Step 8: Write a summary on VPN benefits and limitations.**
* **What I did:** I used my research from Step 7 and my practical experience from the steps above to write the summary in Section 3 of this report.

 ## 2. Deliverables: Connection Status Screenshots

Here is the visual proof of the verification steps.

### Screenshot 1: Before VPN (Original IP)
This screenshot shows my original public IP address (`106.200.27.49`) and location (Vijayawada, India) before activating the VPN.

<img width="1504" height="786" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/8d2b71a6-73d0-4665-a542-e5d9f0df96c5" />


### Screenshot 2: ProtonVPN Client Connected
This screenshot shows the ProtonVPN application dashboard. It confirms a successful connection to a US server (`US-FREE#155`), displaying the new VPN IP (`37.19.199.153`) and the secure `WireGuard` protocol being used.
<img width="1261" height="833" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/1333f463-7cc2-4d2a-b1df-fc48822dbcf4" />


### Screenshot 3: After VPN (New IP Verified)
This screenshot from `whatismyipaddress.com` confirms that my public-facing IP has changed. The site now detects my IP as `37.19.199.153` in New York and correctly identifies that I am using a VPN server.

<img width="1504" height="589" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/e551929c-9863-44b3-9bb8-a7221210fd37" />

## 3. Summary on VPN Benefits and Limitations (Step 8)

### 🟢 Benefits
* **Privacy:** The primary benefit is hiding your real IP address from websites, trackers, and your ISP. As shown in my screenshots, my IP changed from India to the USA.
* **Security & Encryption:** A VPN creates an "encrypted tunnel." This is vital on public Wi-Fi (like at an airport or café) because it prevents hackers from "eavesdropping" and stealing passwords or personal data.
* **Bypass Geo-Restrictions:** By connecting to a server in another country, I can access websites and streaming content that might be blocked in my own region.

### 🔴 Limitations
* **Slower Speeds:** Because your traffic is being encrypted and sent to a distant server, a drop in internet speed is a common limitation.
* **Not 1TA0% Anonymous:** A VPN does not guarantee complete anonymity. The VPN provider *can* still see your real IP and your traffic. This is why it's essential to use a "reputable" service with a strict **no-logs policy**.
* **Free Version Restrictions:** Free VPNs (like the one I used) are limited. They offer fewer server locations, may have data caps, and are often slower than their paid counterparts.
