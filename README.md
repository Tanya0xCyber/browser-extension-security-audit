# Task 7: Identify and Remove Suspicious Browser Extensions

### Objective
Review, identify, and remove suspicious or unnecessary browser extensions to improve browser security and overall system hygiene.



## Tools Used
- **Mozilla Firefox** (any browser extension manager works)

---

## Steps Performed



### **1. Open the Browser Extension Manager**
Opened the Firefox extension page using:

```

Menu → Add-ons and Themes → Extensions

```

This shows all installed browser add-ons.

---


### **2. Review All Installed Extensions**
I went through each extension and checked:

- Do I recognize it?
- Do I use it regularly?
- Are the permissions reasonable?
- Does the developer look legitimate?
- Is it required for cybersecurity learning?

Most extensions were safe (Wappalyzer, Shodan, HackBar, Trufflehog, FoxyProxy, etc.)

**Screenshot 2: Full List of Installed Extensions**

<p align="center">
  <img src="https://github.com/Tanya0xCyber/browser-extension-security-audit/blob/main/screenshots/extension-manager.png" width="80%">
</p>

---

### **3. Identify Suspicious / Unnecessary Extensions**
While reviewing, I found **two extensions that were not needed** and required higher-than-normal permissions:

1. **KNOSSX Community**  
2. **Hunter – Email Finder Extension**

These extensions were not required for my workflow and had elevated access to website data.

So I marked them as “remove candidates.”

---



### **4. Check Their Permissions Before Removal**
Before removing, I checked their permissions to confirm they were unnecessary.

Typical red flags:
- "Read and change data on all sites"
- Tracking-related permissions

**Screenshot 4: Extension Permissions Page (Example)**

<p align="center">
  <img src="https://github.com/Tanya0xCyber/browser-extension-security-audit/blob/main/screenshots/suspicious-marked.png" width="80%">
</p>

---

### **5. Remove the Extensions**
I removed both suspicious/unnecessary extensions:

✅ **KNOSSX Community — Removed**  
✅ **Hunter Email Finder Extension — Removed**

This reduces browser attack surface and improves privacy.

**Screenshot 5**

<p align="center">
  <img src="https://github.com/Tanya0xCyber/browser-extension-security-audit/blob/main/screenshots/remove-extension.png" width="80%">
</p>

---

### **6. Restart the Browser**
Restarted the browser to complete the cleanup and checked for:

- Faster load times  
- No unwanted pop-ups  
- Improved privacy  

---


## Results 

| Extension Name | Action | Reason |
|----------------|--------|--------|
| **KNOSSX Community** | ✅ Removed | Not required; high permissions; optional tool |
| **Hunter – Email Finder Extension** | ✅ Removed | Not needed; broad data access |
| Remaining Extensions | ✅ Kept | All safe, widely used cybersecurity tools |

---

##  What I Learned About Malicious Extensions
Malicious or poorly maintained extensions can:

| Risk | Simple Explanation |
|------|--------------------|
| Track browsing activity | See what sites you visit |
| Steal cookies | Could access login sessions |
| Redirect pages | Send you to unwanted websites |
| Inject ads or scripts | Modify pages you visit |
| Slow the browser | Cause lag or high CPU |

Removing unnecessary extensions is a **key security best practice**.

---


