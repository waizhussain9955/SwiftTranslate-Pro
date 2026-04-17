# SwiftTranslate Pro 🌍

**SwiftTranslate Pro** is a high-performance, premium translation solution for WordPress designed to make global reach effortless. Unlike standard translation plugins, it focuses on **SEO-friendly URL structures**, high-speed delivery, and a clean, brand-free user experience.

---

## 🚀 Key Features

- **SEO-Optimized URL Structures**: Fully supports sub-directory based paths (e.g., `/ur/`, `/hi/`, `/fr/`) which helps in indexing translated pages on search engines.
- **Instant Translation Engine**: Leverages a custom-tuned Google Translate Cloud integration for near-instant content switching.
- **Premium UI / UX**: 
  - Hidden Google branding and toolbars for a native look.
  - Smooth floating and dropdown widgets.
  - Mobile-responsive design.
- **Localized Flag Mapping**: Custom mapping for specific regions (e.g., automatically showing the **Pakistan Flag** for Urdu instead of generic symbols).
- **Persistent Sessions**: Uses intelligent cookie handling to remember user language preferences across the whole site.
- **High Performance**: Optimized `curl` fetch logic in the backend to ensure translated pages load without significant latency.

---

## 🛠️ Technology Stack

- **Backend**: PHP (WordPress Hook API)
- **Frontend**: JavaScript (ES6+), Vanilla CSS
- **API**: Google Translate Cloud Element API
- **Networking**: PHP cURL with custom User-Agent handling for reliable content scraping.

---

## 📂 Project Structure

- `gtranslate.php`: Main plugin entry point with custom activation logic and settings management.
- `url_addon/`: The core engine for handling sub-directory redirects and on-the-fly translation.
- `js/`: Modular JavaScript handlers for different widget styles (Floating, Dropdown, Flags).
- `flags/`: High-quality SVG flag assets with custom regional mappings.

---

## 🚀 Installation & Setup

1. **Clone the Repo**:
   ```bash
   git clone https://github.com/Waiz-Hussain/SwiftTranslate-Pro.git
   ```
2. **Upload**: Zip the folder and upload it to your WordPress `wp-content/plugins/` directory.
3. **Configure**: Go to `SwiftTranslate Pro` settings in your WordPress dashboard.
4. **Choose Structure**: Set the URL structure to **Sub-directory** for maximum SEO benefit.
5. **Shortcode**: Use `[swifttranslate]` to place the switcher anywhere in your header or footer.

---

## 👨‍💻 Author

**Waiz Hussain**  
*Full Stack Developer & WordPress Specialist*
- [Portfolio](https://waizhussain.com)
- [LinkedIn Profile](https://linkedin.com/in/waiz-hussain)

---

## 📄 License

Distributed under the GPL v2 or later License. Perfect for both personal and commercial use.
