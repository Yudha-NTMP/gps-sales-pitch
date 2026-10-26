# IntelliTrac Sales Pitch Engine

Internal sales tool for the IntelliTrac Indonesia team: a pitch matrix, pitch simulator, objection answers, and sensor reference for GPS tracking and fleet telematics across 8 industry sectors.

## Live app

[https://yudha-ntmp.github.io/gps-sales-pitch/](https://yudha-ntmp.github.io/gps-sales-pitch/)

Built for phones first, since the team opens it in front of clients. Light theme by default, with a Solarized Dark toggle.

---

## What's inside (v7)

1. **Matriks Sektor:** 8 sectors, each walked through 3 stages.
   - Tahap 1: fleet qualification, with the question to ask the client.
   - Tahap 2: problem diagnosis (23 client problems in total).
   - Tahap 3: recommended device, sensors, reports, and two pitch scripts.
2. **Simulasi Pitch:** practice the same flow step by step, from sector to problem to pitch.
3. **Jawab Keberatan:** answers to common client objections (price, cabin cameras, blank spots, dealer GPS, trials, insurance, existing vendors, warranty).
4. **Spesifikasi Sensor:** 13 sensors and features, each listing the devices that support it.
5. **Tanya Cepat:** a keyword lookup over the app's own content. It is not an AI model.

Sectors: Mining, Oil & Gas; Agriculture & Plantation; Retail & Cold Chain Logistics; Construction & Infrastructure; Manufacturing & Warehouse; Public Transportation; Amusement Park & Tourism; Personal & Rental Vehicle Safety.

Device and sensor claims follow the IntelliTrac 2026 product catalogue.

---

## Tech

- One self-contained HTML file (`index.html`): HTML, CSS, and vanilla JavaScript, with no build step and no framework.
- All pitch content lives in a single data block inside the script, so every view reads from the same source.
- The only external resource is Google Fonts (Poppins and Roboto).
- Hosted on GitHub Pages.

---

## License

Copyright © 2026 IntelliTrac Indonesia. All rights reserved.

This repository is public only so the app can be served through GitHub Pages. The code, pitch scripts, and product content are proprietary and may not be copied, modified, redistributed, or reused without written permission from IntelliTrac Indonesia. See [LICENSE](LICENSE).
