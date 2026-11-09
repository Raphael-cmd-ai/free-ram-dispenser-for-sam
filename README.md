# 🎰 Free RAM Dispenser for Sam

> *"Your RAM is being used maybe 5% of the time. Keeping the world's limited supply of DRAM in your own computer is quite terrible."*  
> — **Sam Altman**

Welcome to the **Free RAM Dispenser for Sam**, a satirical yet fully functional Linux monitoring and reporting tool built to resolve Sam Altman's deepest hardware concerns.

If your machine has more than 10% available memory doing absolutely nothing, this script automatically drafts and dispatches a daily memory census to Sam Altman. Each dispatch is picked from a pseudo-randomized bag system so the joke ages at a carefully regulated pace.

---

## 🎁 Features

- **Automated DRAM Census:** Monitors `/proc/meminfo` and calculates exact unallocated capacity.
- **The Altman Lottery:** Rotates through 15 handcrafted satirical messages, ranging from holiday greetings to old dual-Xeon basement servers and soldered motherboard warnings.
- **OpenAI Consolation Prize:** Since Sam cannot physically take your desktop memory, every email politely provides a link to [DownloadMoreRAM.com](https://downloadmoreram.com) so OpenAI can satisfy its compute appetite for free.
- **Zero Cloud Footprint:** Runs locally via a lightweight bash script and a cron job. No telemetry, no venture capital required.
- **Memory-Safe:** Distinguishes reclaimable page cache from actually locked RAM.

---

## 🚀 Quick Start

### 1. Clone & Setup
```bash
git clone [https://github.com/Raphael-cmd-ai/free-ram-dispenser-for-sam.git](https://github.com/Raphael-cmd-ai/free-ram-dispenser-for-sam.git)
cd free-ram-dispenser-for-sam
chmod +x ram-altman.sh test-ram-altman.sh
