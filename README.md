# 🚀 Discord Message Translator Release Notes

[简体中文](./README.zh-CN.md) | [Русский](./README.ru.md)

Automatically translates message lists and one-click translates messages in the input box to a specified language, serving as a fully functional bidirectional communication assistant.

> 💡 **Feedback**
>
> Encountering issues or have feature suggestions? Let us know in the [Issues](../../issues)!

---

## 📜 Version History

### v4.2.3 - Cleaner Emoji Messages

*   **✨ No Redundant Translation Boxes**
    *   Emoji-only messages no longer trigger translation requests or display a duplicate translation box, keeping active chats easier to read.
*   **💬 Mixed Messages Still Translate**
    *   Messages containing both text and emojis continue to translate normally while preserving their original emojis.

### v4.2.2 - Clearer Store Metadata

*   **📝 Concise Listing Copy**
    *   Shortened localized titles and summaries so they describe the extension without repetitive search terms.
*   **🛡️ Metadata Compliance**
    *   Removed standalone keyword lists from store copy; extension behavior and permissions are unchanged.

### v4.2.1 - Interface Language Control

*   **🌐 Manual Language Selection**
    *   Choose any of the 55 supported interface locales, or continue following the browser language automatically.
*   **⚡ Instant Interface Updates**
    *   Language and text direction changes apply immediately to both the popup and the Discord in-page controls.
*   **🛡️ Seamless Upgrade**
    *   Existing translation settings remain unchanged, and legacy English or Chinese interface preferences are preserved.

### v4.2.0 - Global Localization

*   **🌍 Localized for 55 Locales**
    *   The extension interface now follows the browser language, with English used as a reliable fallback.
*   **🔎 Localized Store Discovery**
    *   Added localized extension names and descriptions based on the real-time, bi-directional translation experience.
*   **🧭 Regional & RTL Support**
    *   Refined regional wording and added right-to-left layout support for Arabic, Hebrew, and Persian.
*   **🪶 Compatible & Lightweight**
    *   Existing reading and writing settings remain compatible, with no new permissions required.

### v4.1.1 - Experience Optimization

*   **🎨 Visual Update**
    *   New Discord-inspired design for a more modern and clean interface, with optimized card layouts and color schemes.
*   **🔔 Unsaved Changes Alert**
    *   Added a real-time unsaved changes indicator to ensure your settings are applied and to prevent missed saves.
*   **🔗 Quick Access**
    *   Added direct links to "Help Tutorial" and "Feedback" at the bottom of the popup for better accessibility.

### v4.1.0 - Feature Enhancement

*   **📋 List Translation Support**
    *   Added translation support for Ordered Lists (OL) and Unordered Lists (UL), preserving full HTML list structures for a better reading experience of complex messages.

### v4.0.0 - Bidirectional Communication

*   **✍️ Input Box Translation**
    *   A new translation button ("文" icon) has been added to the Discord chat toolbar. Type in your native language, click the button, and it will instantly translate your drafted text into the target language (e.g., English) ready for sending.

*   **🎨 Settings Panel**
    *   Independent Configuration: You can now set different target languages for "Reading" (Incoming messages) and "Writing" (Outgoing messages).
*   [📸 Effect Display](../../issues/1)

### v3.0.0 - Experience Upgrade

*   **⚡ Instant Response**
    *   Real-time monitoring for new messages; "instant" translation with zero waiting time.

*   **🧠 Persistent Memory**
    *   Previously translated messages are cached locally, ensuring faster loading and reduced data usage.

*   **🎯 More Accurate Restoration**
    *   Fixed issues where emojis, links, and special symbols might be misplaced or corrupted after translation.

*   **🌊 Seamless Experience**
    *   Greatly optimized performance, ensuring smooth operation even in highly active channels with thousands of members.

*   **🧹 Smart Management**
    *   Automatically cleans up expired cache data to keep your storage organized.

*   **📸 Screenshots**
    *   <img alt="v3-1.webp" src="images/v3-1.webp" width="300"/>
    *   <img alt="v3-2.webp" src="images/v3-2.webp" width="300"/>
    *   <img alt="v3-3.webp" src="images/v3-3.webp" width="300"/>


### v2.2.0

*   **🐛 Bug Fix**
    *   Fix invalid translation.

### v2.1.0

*   **💅 Display Optimization**
    *   Optimize the display of translated messages.

*   **🎨 Theme Adaptation**
    *   Adapt to custom themes.

### v2.0.0

*   **✨ UI Improvement**
    *   On the basis of v1, the UI display has been improved and made more natural. Can maintain good readability when translating complex message content.

### v1.0.0

*   **🌱 Basic Function**
    *   Automatically translate messages into the page language.
