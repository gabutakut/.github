# 🚀 Welcome to Gabut Akut

We are an open-source organization based in Indonesia, born out of a passion for building high-quality, native Linux software. **Gabut Akut** is dedicated to developing next-generation multimedia and utility applications that are completely free, open-source, and crafted beautifully for the modern GTK4 / GNOME desktop ecosystem.

Our core focus is delivering lightweight, memory-efficient, and performance-driven applications using native technologies.

---

## 🛠️ Our Philosophy & Tech Stack

We believe desktop applications should feel lightweight yet powerful. To achieve this, we leverage a modern, native tech stack:

* **Programming Language:** Core applications are fully compiled using `valac` (Vala Compiler) and C++. This gives us C-level performance with a modern, highly productive syntax.
* **User Interface:** Built strictly with **GTK4** and **Libadwaita**. We strictly follow the latest GNOME design patterns to deliver clean, minimalist, adaptive layouts with smooth animations.
* **Asynchronous & Efficient:** Utilizing modern asynchronous mechanisms to handle heavy network loads and media parsing without ever blocking the user interface.

---

## 📦 Our Flagship Projects

### 1. 📥 [gabutdm](https://github.com/gabutakut/gabutdm) (Gabut Download Manager)
A simple, fast, and powerful multi-protocol download manager designed as a native, Linux-first experience.
* **Key Features:** Multi-threaded download progress, Torrent file selection, HLS/M3U8 fetch mode, and integrated YouTube stream selection.
* **Tech Stack:** Vala (96%+), C++, GTK4.
* **Ecosystem Add-ons:** 
  * [gabutextentionsGC](https://github.com/gabutakut/gabutextentionsGC) - Official integration extension for Google Chrome.
  * [gabutextentionsFF](https://github.com/gabutakut/gabutextentionsFF) - Official integration extension for Mozilla Firefox.

### 2. 🎬 [gabutplayx](https://github.com/gabutakut/gabutplayx)
A modern, high-performance video player designed to deliver butter-smooth multimedia playback with native Linux hardware acceleration support.
* **Key Features:** Clean, non-obsolete minimalist UI, advanced playback control, and full integration with the desktop environment.
* **Tech Stack:** Vala, GTK4.

### 🔧 Backend & Companion Utilities
* **[gabutytb](https://github.com/gabutakut/gabutytb):** A specialized Python-based RPC server designed for YouTube parsing. It serves as a backend frontend extractor for `yt-dlp` to fetch media streams dynamically.

---

## 🤝 Contributing

We love community contributions! Whether you are a Vala developer, a Python backend enthusiast, a UI/UX designer, or someone looking to report bugs, your help is highly appreciated.

### How to Get Started:
1. Fork the repository you want to contribute to.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Write your code (please ensure clean code and proper GObject memory management).
4. Open a *Pull Request*.

> ⚠️ **Technical Note for Contributors:** 
> To maintain strict code clarity and prevent namespace or function naming collisions across our projects, we **do not use** global `using` directives in our Vala source code. Please explicitly prefix namespaces (e.g., use `Gtk.Application` or `Soup.Message`).

---

## 🛡️ License

Our projects are completely Free and Open Source software, distributed under open-source licenses such as the **LGPL-2.1** (for `gabutdm`) and **GPL-3.0** (for `gabutplayx`).

---

## 🌐 Support & Connect With Us

If you love what we do and want to support the development of GabutDM and other applications, feel free to connect or buy us a coffee:

* **Email:** torik.habib@gmail.com
* **Donations (IDN):** [Saweria GabutDM](https://saweria.co/Gabutdm)
* **International Support:** [PayPal](https://paypal.me/TorikulHabib)

---
<p align="center">Built with ❤️ using Vala, Python, and GTK4 for a better Linux desktop experience.</p>
