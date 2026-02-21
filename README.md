# VR Blocklist

My personal blocklist for blocking some unwanted domains.
Automatically generated and deployed via GitHub Actions. 

---

## ✅ Features

- **Automated generation:** `adblock.txt` and `hosts.txt` are updated whenever `domains.txt` changes.  
- **Sorted and validated:** AdBlock and Hosts lists are alphabetically sorted and syntax-checked.  
- **Changelog generated:** Automatic diff of domain changes.  
- **Versioning:** Tags/releases created for every update.  
- **Direct access:** GitHub Pages hosts the latest blocklists for easy subscription.  

---

## 📂 Files

| File | Description |
|------|-------------|
| `domains.txt` | Original list of domains you want to block (editable). |
| `adblock.txt` | AdBlock-compatible blocklist (sorted, validated). |
| `hosts.txt` | Hosts file compatible with Pi-hole or system-level blocking. |
| `CHANGELOG.txt` | Auto-generated changelog of changes in `domains.txt`. |

---

## 🌐 Direct Links

- AdBlock list: [adblock.txt](https://virajrana73.github.io/vr-blocklist/adblock.txt)  
- Hosts list: [hosts.txt](https://virajrana73.github.io/vr-blocklist/hosts.txt)

---

## ⚡ Workflow Overview

**Visual Diagram:**  [Update domains.txt] → [Trigger GitHub Actions] → [Generate adblock.txt & hosts.txt] → [Validate syntax] → [Commit & Tag Release] → [Deploy to GitHub Pages] → [Users access blocklists]


**Step-by-step Explanation:**  

- **Update domains.txt:** Add or remove domains you want to block.  
- **Trigger GitHub Actions:** Workflow runs automatically on push to main (or can be manually triggered).  
- **Generate adblock.txt & hosts.txt:** Creates sorted, validated blocklists from domains.txt.  
- **Validate syntax:** Checks AdBlock and Hosts formats to prevent broken lists.  
- **Commit & Tag Release:** Saves changes, generates changelog, and creates a version tag.  
- **Deploy to GitHub Pages:** Makes blocklists available via direct URLs.  
- **Users access blocklists:** Users can subscribe to the lists or use them in DNS/blocking tools.

---

## 📝 How to Contribute

1. Add or remove domains in `domains.txt`.  
2. Push changes to the `main` branch.  
3. GitHub Actions workflow automatically updates `adblock.txt` and `hosts.txt`.  

*No manual intervention needed for list generation or deployment.*  

---

## ⚠️ Disclaimer

- Use this list at your own risk.  
- This list may block domains that are used for legitimate services.  
- Check before using in production or system-level blocking.
