# Test Plan — Garibook Driver App (Bidding Smoke, Appium)
ISO/IEC/IEEE 29119 / IEEE 829 aligned.
Objectives: fast smoke of core driver flow; capture timings.
Env: Real Android + Windows host; TZ Asia/Dhaka; staging build.
Entry: installable build, ADB device, test driver, GPS on. Exit: E2E green; no Sev-1; video/screens.
Risks: GPS variance; delayed notifications; map render stalls; state sync.
