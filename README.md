# Jersey Shop UI Kit

> 👨‍💻 Developed by **[Suresh Kumar Meesala](https://github.com/SureshKumarMeesala)** · 🎨 UI design by **Arotec** (credits below)

A mobile app built with **React Native (0.88+)**, **Expo SDK 58+** and **Expo Router**, using **JavaScript and JSX (`.js`, `.jsx`)**. Every screen is built from the original Sketch design `Jersey Shop UI Kit - By Arotec Digital.sketch` by **Arotec**: one route per artboard, with the artboard's layout, colours, images and text.

![Jersey Shop UI Kit screens](./showcase.jpg)

## 📱 Screens (7 design artboards)

Listed in the order of the app's flow. "Taps" is the number of tap targets wired on the screen (buttons, tabs, back arrows, list rows).

| # | Screen (artboard) | Route | Size | Taps |
|---|---|---|---|---|
| 1 | **Home** · start screen | `src/app/home.jsx` | 414 × 896 | 5 |
| 2 | **Category - women's** | `src/app/category-women-s.jsx` | 414 × 896 | 3 |
| 3 | **product description** | `src/app/product-description.jsx` | 414 × 896 | 3 |
| 4 | **Mennu** | `src/app/mennu.jsx` | 414 × 896 | 2 |
| 5 | **Search** | `src/app/search.jsx` | 414 × 896 | 2 |
| 6 | **cart** | `src/app/cart.jsx` | 414 × 896 | 2 |
| 7 | **checkout** | `src/app/checkout.jsx` | 414 × 896 | 2 |

Screenshots of every screen are in [`screenshots/`](./screenshots).

## 🧩 How it's built

- `src/screens/*.json`: each design artboard converted to screen data (vector shapes, gradients, image fills, masks, shadows, blurs and rich text, positioned as in the design), plus its tap targets
- `src/sketch/SketchScreen.jsx`: draws a screen at the device's width with `react-native-svg`, native `Text`/`TextInput` and `expo-blur`, and handles navigation between screens
- `src/app/`: Expo Router routes, one per artboard (`index.jsx` opens the start screen)
- `assets/images/`: images used by the design

## 🛠️ Tech Stack

- **Framework**: React Native 0.88+ / Expo SDK 58+
- **Navigation**: Expo Router (file-based routing)
- **Language**: JavaScript & JSX (`.js`, `.jsx`)
- **Rendering**: `react-native-svg`, `expo-blur`
- **Fonts**: Google Fonts via `@expo-google-fonts` (Barlow), standing in for the design's original fonts where those aren't free

<!-- run-locally:start -->

## ▶️ Run locally

```bash
npm install
npx expo start
```

Then press `i` for the iOS simulator, `a` for Android, or `w` for the web, or scan the QR code with Expo Go.

<!-- run-locally:end -->

<!-- developer:start -->

## 👨‍💻 Developer

This React Native app was developed by **Suresh Kumar Meesala**.

| | |
|---|---|
| Developer | [Suresh Kumar Meesala](https://github.com/SureshKumarMeesala) |
| GitHub | [@SureshKumarMeesala](https://github.com/SureshKumarMeesala) |
| Organization | [FreeAppSource](https://github.com/FreeAppSource) |
| Repository | <https://github.com/FreeAppSource/jersey-shop-ui-kit> |

<!-- developer:end -->

---

<!-- design-credits:start -->

## 🎨 Design Credits

This app is based on the free **Jersey Shop UI Kit** design by **Arotec**, downloaded from Sketch App Sources. All visual design credit goes to the designer. The screens are reproduced from the original Sketch file; fonts that aren't free are replaced with similar Google Fonts, so some details may differ slightly from the original.

| | |
|---|---|
| Designer | [Arotec](https://www.sketchappsources.com/contributor/Arotec) |
| Original design | [Jersey Shop UI Kit](https://arotecdigital.com/2020/07/11/jersey-shop-free-ui-kit/) |
| Downloaded from | [Sketch App Sources](https://www.sketchappsources.com/free-source/4533-jersey-shop-ui-kit-sketch-freebie-resource.html) |
| Dribbble | <http://www.dribbble.com/arotec> |
| Website | <https://www.behance.net/toluenegabb635> |
| Original file | `Jersey Shop UI Kit - By Arotec Digital.sketch` |
| License / usage | CC BY 4.0 (Creative Commons Attribution 4.0 International), stated in the included Readme.rtf. Commercial use allowed with credit. |

**Attribution:**

> UI design: "Jersey Shop UI Kit" by Arotec (https://arotecdigital.com/2020/07/11/jersey-shop-free-ui-kit/), downloaded from Sketch App Sources (https://www.sketchappsources.com/free-source/4533-jersey-shop-ui-kit-sketch-freebie-resource.html).

The original design source files are not included in this repository; get them from the links above. This app's **code** is released under the [MIT License](./LICENSE); the visual design remains the designer's (see [NOTICE](./NOTICE)).

Photos, brand logos and avatars inside the design may belong to third parties and are not covered by the designer's permission.

<!-- design-credits:end -->
