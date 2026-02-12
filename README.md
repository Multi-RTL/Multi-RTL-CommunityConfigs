⬅️➡️ The first chrome extension that provides configurable Right-to-Left (RTL) text alignment support for ANY website!

תוסף הכרום הראשון המאפשר יישור טקסטים לימין לכל אתר, באופן דינאמי
ומשאיר את החלקים הרלוונטיים (דוגמאות קוד, משוואות מתמטיות) מיושרים לשמאל!

أول إضافة كروم تمكّن محاذاة النصوص لليمين، لأي موقع ويب، بشكل ديناميكي وتترك الأجزاء ذات الصلة (أمثلة الأكواد، المعادلات الرياضية) محاذاة لليسار!

Align Hebrew / Arabic / Persian text to Right-to-Left (while keeping non-RTL left-aligned, including code snippets and *math formulas* (KaTeX/LaTeX).

Comes pre-configured for ChatGPT, Gemini, Claude.ai, NotebookLM and Slack and enables you to
configure any DOM selectors in any web site to automatically detect and apply RTL alignment.

מגיע מוגדר מראש עבור אתרים כגון צ'אט ג'פיטי, ג'מיני, קלוד, נוטבוק, סלאק ועוד!
ומאפשר להגדיר אלמנטים ליישור לימין בכל אתר!

Struggling with reading Hebrew/Arabic on websites that don't support RTL properly?
Struggling with reading twisted Math Formulas in ChatGPT in Hebrew conversations?

Multi-RTL is here to fix that !!

מתקשים לקרוא עברית באתרים שלא תומכים ביישור טקסטים לימין כמו שצריך?
מתקשים לקרוא נוסחאות מתמטיות מסובכות בצ'אט ג'יפיטי או בקלוד בשיחות בעברית?
התוסף הזה בדיוק בשבילכם!


See demos and user guide on:
https://multi-rtl.interact-ed.online

- הדגמת שימוש והוראות שימוש כאן
https://multi-rtl.interact-ed.online

## ✨ Features

🌐 **Universal Support** - Works with any website!

🎯 **Auto-Detection** - Automatically detects Hebrew, Arabic, and Persian for auto-RTL using the Unicode BiDi first-strong-character algorithm

📐 **Math Formula Support** - Correctly aligns mathematical formulas (KaTeX/LaTeX) in RTL contexts

🔄 **Real-time Processing** - Works with streaming/dynamic content

⚙️ **Per-Domain Configuration** - Configure different selectors for each domain

🔍 **Element Picker** - Click an in-popup 🔍 to pick an element on the page and build a reliable selector easily.

🎛️ **Master Toggle** - Enable/disable all selectors for a domain with one switch

⌨️ **Keyboard Shortcut** - Press `Ctrl+Shift+H` to toggle Master switch

⌨️ **Customizable Shortcuts**: Set your own preferred keyboard shortcut for the Master Toggle

🔘 **Individual Selectors** - Enable/disable each selector independently

🎨 **Advanced Style Controls** - Control direction (dir) and text-align separately

⚡ **Force RTL Mode** - Skip content inspection and force RTL for specific selectors

👀 **Visual Highlight**: Hover over selectors in the list to instantly see which elements they match on the page

⏱️ **Load Delay** - Configure per-domain delay for late-loading content

💾 **Smart Import/Export**: Backup your settings or share configurations. Imports now merge with your existing settings!

⭐ **Premium Features** - Unlock advanced capabilities with an affordable lifetime subscription

✅ **Pre-configured** - The extension comes pre-configured for popular AI chat platforms and collaboration tools:

- **ChatGPT** (chatgpt.com)
- **Google Gemini** (gemini.google.com)
- **Claude.ai** (claude.ai)
- **Slack** (app.slack.com)
- **NotebookLM** (notebooklm.google.com)

Just visit these sites and RTL text will automatically align to the right!

### Configure it for any website:

1. **Visit the website** you want to configure
2. **Click the extension icon** in toolbar
3. **Click "➕ Add"** to add a new selector
4. **Click the 🔍 button** on the new selector row
   - The popup closes and Multi-RTL enters "pick" mode on the page
   - Click an element you want to target
5. An **in-page Selector Builder** opens (top-right):
   - Choose the best element/ancestor from the dropdown
   - Optionally add **classes/attributes** via the Properties dropdown (hovering previews highlight)
   - Click **Save** to update the selector you started from (or **Cancel** to discard)
6. Load Delay: Configure a delay (in milliseconds) before the initial processing runs on page load. (useful for sites with late-loading content)
7. The new configuration is saved automatically!

**Content-based**: When enabled, Multi-RTL detects whether the content starts with RTL text before applying styles. When disabled, Multi-RTL forces RTL for that selector.

**🎯 HOW IT WORKS:**

1. **Install & Go**: Pre-configured for popular sites - just visit Gemini, ChatGPT, Claude, NotebookLM, or Slack.
2. **Add Custom Sites**: Click the extension icon, click ➕ (Add), then click the 🔍 on the newly created selector to pick the target element in the page.
3. **Toggle Control**: Use the Master toggle or individual selector toggles for instant control
4. **Configure Options**: Fine-tune with style controls, force RTL, load delays, and more
5. **Share & Backup**: Export your configuration to share with others or keep as a backup.

**🔒 PRIVACY & SECURITY:**

Multi-RTL is designed with your privacy in mind:
*   **100% Local Processing**: All text analysis and RTL detection happens entirely on your device
*   **Zero Browsing Data Collection**: We never collect, store, or transmit your browsing data or page content
*   **No Tracking**: No analytics, no telemetry — the only external connection is to our payment provider (PayVia) for premium license validation
*   **Secure Identity**: The `identity` permission is used solely to associate your Google account with a premium license, so it works seamlessly across devices. Users without a Google account are assigned an anonymous ID instead
*   **Open Source Ready**: Transparent code you can inspect

**💡 PERFECT FOR:**
*   AI Chat Platforms (ChatGPT, Claude, Gemini, Perplexity)
*   Team Collaboration (Slack, Microsoft Teams, Discord)
*   Messaging Apps (WhatsApp Web, Telegram Web)
*   Project Management (Monday, Trello, Asana, Notion)
*   Social Media & Forums
*   Email Clients & Web Apps
*   Any website with Hebrew, Arabic, or Persian content

**🌍 LANGUAGE SUPPORT:**
*   Hebrew (עברית)
*   Arabic (العربية)
*   Persian/Farsi (فارسی)

*Made with ❤️ for the RTL community - Version 5.1.0*
See demos and user guide on https://multi-rtl.interact-ed.online

# Multi-RTL Release Notes

## v5.1.0

### Changed
- **Free Features**: Export Config and Add Selector are now free for all users. Only Import Config remains a premium feature.

## v5.0.1

### Improved
- **Smarter RTL Detection**: Now uses the Unicode BiDi "first strong character" algorithm instead of checking just the first character. Emojis, numbers, bullets, and punctuation are properly skipped.
- **Mixed Content Support**: Sentences starting with English but containing mostly Hebrew/Arabic (30%+ RTL letters) are now correctly detected as RTL (e.g. "Phase 1 - תשתית DB").
- **Mixed Inline Elements**: Fixed detection for elements with mixed inline children (e.g. `<li><strong>Phase 1</strong> - Hebrew text</li>`) where the first text wasn't in a child element.

### Fixed
- **List Bullet Visibility**: List markers (bullets/numbers) no longer disappear when `<li>` elements receive RTL direction. Applies `list-style-position: inside` automatically.

## v5.0.0

### Added
- **Premium Features**: Added subscriptions based (Annual & Lifetime) premium features (Import /Export config and Add Selector).
- **User Authentication**: Secure identification via Google Identity for cross-device license validation.

## v4.3.0

### Added
- **Major UI Improvements**:
  - Highlight elements on page when hovering over selectors in popup
  - Option to delete all selectors for the current domain
  - Option to customize the keyboard shortcut
- **Enhanced Configuration**:
  - Merge functionality when importing configuration (instead of overwrite)
  - Added more built-in selectors for ChatGPT, NotebookLM, Claude, Gemini and Slack
  - Add handling of mathematical formulas (KaTeX/LaTeX) in RTL contexts
- **Popup UI Overhaul**: Replaced footer with a new "Actions" dropdown menu in the header for cleaner navigation.
- **Tooltips**: Added detailed tooltips to Export/Import buttons for better user guidance.
- **User Guide**: Added a link to a detailed User Guide (in the "Actions" dropdown)

### Changed
- **Layout Refinement**: Improved Domain Settings layout using Flexbox for better alignment.
- **Bug Fixes**: Added missing "delete selector" icon.

## v4.0.2

### Added
- **Multi-language RTL support**: Now supports Arabic and Persian (Farsi) in addition to Hebrew
  - Expanded Unicode range detection to include Arabic script (\u0600-\u06FF, \u0750-\u077F)
  - All RTL languages now automatically detected and aligned correctly
  - Works seamlessly with mixed Hebrew/Arabic/Persian content

## v4.0.0

This release is a major UX and workflow upgrade focused on making selector setup faster, more accurate, and less error-prone.

### Highlights

- Added an element picker (🔍) to select page elements directly, with hover preview (outline + tooltip) and click-to-pick.
- Introduced an in-page Selector Builder overlay (top-right) that appears after picking an element, with Save/Cancel.
- Selector Builder supports building selectors from element ancestry and optionally refining with class/attribute matching.
- Improved persistence: inspector/builder state is stored and preserved through Import/Export.

### What's New (User-Facing)

- Inspector flow
  - Click 🔍 on a selector row in the popup.
  - The popup closes and the page enters pick mode.
  - Click the element you want to target.
  - The in-page overlay opens with the Selector Builder.
  - Save updates the same selector row you started from; Cancel discards.

- Selector Builder overlay
  - Dropdown browsing previews highlight on the page.
  - Dropdown menus use a "portal" positioning approach to avoid being clipped.

- Popup UI updates
  - Selector rows were redesigned to emphasize quick actions: enable checkbox, delete, and 🔍 inspector.
  - Import/Export continues to work, now including inspector builder state.

### Behavior / Configuration Notes

- Existing selector strings continue to work.
- v4 adds optional per-selector "builder" metadata used by the inspector Selector Builder.
- Some fields still exist in configuration for backward compatibility but are no longer shown in the popup UI.

### Known Differences vs v3.2

- The recommended way to create/adjust selectors is now the built-in 🔍 picker + in-page Selector Builder.
- The popup no longer relies on a "copy selector from DevTools" workflow as the primary path.

### Next (Planned)

- Show release notes to the user once after upgrading to v4.0.0 (first usage per version), using this document as the source.
- Scan current page to auto-generate selectors based on RTL content detection






