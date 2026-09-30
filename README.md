# Shailu Bhai — Daily Collection APK (Clean Build)

## GitHub se APK banane ke liye
1. GitHub me **new private repository** banao.
2. Is folder ke **andar ki saari files/folders** upload karo; `.github` bhi upload hona chahiye. ZIP ko upload mat karo.
3. `Actions` → `Build APK` → `Run workflow`.
4. Green build ke baad `Artifacts` me `ShailuBhai-APK` se APK download karo.

## Important
- Existing app ID/signing key same rakhi gayi hai, isliye **purane APK ko uninstall kiye bina update** install karna hai.
- WhatsApp/external links Android ke native opener se khulte hain.
- JSON backup aur Excel export Downloads me save hote hain.
- JSON/Excel restore ke liye Android file picker enabled hai.
- Core data IndexedDB me local hai.
- Runtime par ad network nahi hai.
- Excel library GitHub build ke waqt APK ke andar bundle hoti hai, isliye Excel feature runtime internet par depend nahi karta.
- Chrome ka existing data automatically APK me nahi aata; Chrome se JSON backup lekar APK me Restore JSON karo.
- **APK update ke waqt uninstall mat karna**, warna local app data delete ho sakta hai.
