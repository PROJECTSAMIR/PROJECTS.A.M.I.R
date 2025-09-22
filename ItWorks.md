# 🖥️ Project S.A.M.I.R — Chapter 3: It Works  

With the hardware revived (Chapter 1) and the workspace ready (Chapter 2), it was finally time to see if this machine could really come to life.  

---

## ⚙️ BIOS & OS Installation  

- Focused on stability — no overclocks.  
- Updated BIOS to the latest available (2014 release).  
- Created a clean **Windows 10 Pro** installer on a **SanDisk 128 GB USB 3.0**, using my Samsung Galaxy Book 360.  
- Installed onto a **1 TB Crucial SSD** (best option available without M.2 support).  
- Let Windows run all updates after years offline.  
- Installed latest NVIDIA drivers for the Palit GTX 970 GPUs.  

---

## 🌐 Getting Online Without Ethernet  

The PC had no Wi-Fi card and the router was downstairs.  
My solution:  
- Connected a USB-C hub to my Samsung Note 20 Ultra.  
- Plugged Ethernet into the hub, enabled Ethernet tethering on the phone.  
- Achieved ~200 Mbps download — quick, stable, and no extra hardware needed.  

---

## 📊 First Benchmarks  

- Ran **Unigine Heaven** on normal and extreme settings — stable performance.  
- GTA V Story Mode hit ~80 FPS after removing the frame cap — surreal seeing a childhood favourite running on a PC I built myself.  
- At this point, my Samsung Galaxy Book was retired for daily use — the build officially took over.  

---

## 🛠️ GPU & SLI Troubleshooting  

After stress testing, the second monitor went black.  
Steps I took to diagnose:  
1. Tested different Mini DisplayPort outputs.  
2. Swapped GPUs between PCIe slots.  
3. Checked and reseated the SLI bridge.  
4. Verified fan spin and temps.  

**Result:**  
- One Mini DP port failed, others worked fine.  
- SLI bridge restored function.  
- Dual-GPU setup back online.  

---

## 📂 Folder Structure Setup  

Once Windows was stable, I built my workspace using Command Prompt:  
## 💾 External Drive Scare  

While transferring files, my external HDD began showing signs of failure — slow reads, disconnects, and the dreaded clicking noises.  
It held ~800 GB of irreplaceable data, so losing it wasn’t an option.  

To protect the data:  
- Stopped all non-essential writes immediately  
- Used `chkdsk /f /r` to scan for bad sectors  
- Prioritised copying critical files first  
- Transferred everything to a **Crucial 1 TB SSD** — a process that took **4½ days** due to the degraded state  
- Retired the HDD once the transfer was complete  

When the dust settled, I had a total of **6 TB of storage pooled together** across drives — far more than I’d ever had before. For someone just starting out, it felt like a data vault, a foundation to build labs, backups, and experiments without worrying about space.  


