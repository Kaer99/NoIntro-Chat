# NOINTRO-CHAT – Full Copy-Paste Project (Telegram/WhatsApp Style)

## 1. Project Name & Logo (ready to use)
App name: **Nointro-Chat**  
Tagline: "No intro needed. Just chat."

Logo text: NoIntrotz (gold 3D version you already have from previous sessions)

## 2. Color Palette (exact hex – copy-paste ready)
--primary: #0088cc          // Telegram-style blue
--primary-dark: #0066aa
--accent: #ff9500           // Orange highlight (your vibe)
--bg: #0f0f0f               // Dark mode default
--chat-bubble-me: #0088cc
--chat-bubble-other: #1e1e1e
--text-primary: #ffffff
--text-secondary: #aaaaaa

## 3. Flutter Project Setup (run once)
```bash
flutter create nointro_chat
cd nointro_chat
flutter pub add firebase_core firebase_auth cloud_firestore firebase_storage
flutter pub add flutter_local_notifications flutter_contacts
flutter pub add provider get_it crypto intl
flutter pub add image_picker video_player cached_network_image
