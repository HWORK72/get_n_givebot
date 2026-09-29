🇷🇺 [Читать на русском](README_RU.md)

An event-driven algorithmic market intelligence assistant providing automated asset pricing, ByBit charting feeds, and macro session scheduling.

### Key Architectural Highlights:
* **ByBit Market Integration:** Low-latency polling of order book data, ticker prices, and visual chart rendering on demand.
* **Macro Session Scheduler:** Automated push notifications synchronized with peak liquidity windows, including the European Session open (08:00 UTC).
* **Forex Weekly Resumption Listener:** Deterministic alerts for global currency market open events (Sundays, 22:00 UTC).
* **Tunnel-Ready Architecture:** Designed for zero-trust deployment pipelines leveraging Cloudflare Tunnels for endpoint protection.

### Tech Stack:
* Python 3.12
* Aiogram 3.x / Aiohttp (High-concurrency networking)
* ByBit REST API (Exchange data feeds)
* Asyncio Scheduling primitives

### Quick Start:
```bash
pip install -r requirements.txt
python main12.py
