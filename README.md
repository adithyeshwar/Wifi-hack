
# 🚀 Wifi-Hack 🖧  
### Discover the password of a WiFi network you're already connected to!

> **Note:**  
To reveal the WiFi password of a network at your college, home, or anywhere else, you'll need access to a **PC or laptop** that is **already connected** to that network.  

---

### Steps to Reveal the Password:

1. **Open Command Prompt**:  
   - Press `Win + R`, type `cmd`, and hit Enter.

2. **Turn on the Hacker Mode** 🤖:  
   - In the command prompt, type:  
     ```bash
     color 0a
     ```
     This will turn the text **green** to give that cool hacker vibe! 🟢

3. **Run the Magic Command**:  
   - Now, type the following:  
     ```bash
     netsh wlan show profiles "NetworkName" key=clear
     ```
   - Replace `"NetworkName"` with the name of the WiFi network you’re connected to.

4. **Find the Password**:  
   - Scroll down, and under **Key Content**, you’ll find the WiFi password. 🔑

---

### Pro Tip 🧠:  
- If you're unsure about the network name, just run this command to list all available networks:  
   ```bash
   netsh wlan show profiles
   ```


Enjoy your new skills and stay secure! 😎🔐
