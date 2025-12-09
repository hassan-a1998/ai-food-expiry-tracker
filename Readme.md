# AI Food Expiry Tracker

## Product Overview
Mobile app that scans product photos with OCR/ML to extract expiry dates, maintains searchable inventory, and notifies users of items expiring in 30 days. Targets busy households reducing food waste by 25% via proactive alerts.

## Problem & Market
30% of food wasted due to forgotten expiry dates (FAO data). Existing apps lack seamless scan-to-notify ML flows.

## User Personas
- Primary: Urban professionals (e.g., you, managing groceries).
- Metrics: Retention via daily scans, 80% open rate on notifications.

## Key Features & ML Pipeline
| Feature | ML Component | Success Metric |
|---------|--------------|----------------|
| Photo Scan | OCR (Tesseract/EasyOCR) + Date Parser | 95% accuracy on labels |
| Inventory List | SQLite/Vector Search | <1s query time |
| Expiry Alerts | Cron Job + Threshold ML | 90% user action rate |

## Tech Stack
- Frontend: Flutter/React Native
- ML: Google ML Kit OCR
- Backend: Firebase for notifications
- Deployment: Vercel/Heroku

## Go-to-Market
MVP in 2 weeks: Launch on app stores, monetize via premium alerts ($1.99/mo).

## Next Steps
Prototype wireframes attached. Open to PM collaboration!

![Architecture Diagram] (add simple draw.io image via GitHub)
