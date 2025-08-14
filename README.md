# Thrive: Your Daily Three

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg) ![Made with](https://img.shields.io/badge/Made%20with-HTML%2C%20CSS%2C%20JS-1f425f.svg)

A minimalist, single-page web application designed to help you focus on your three most important tasks each day. Build habits, track your progress, and stay motivated with a clean, relaxing interface.



## ✨ Live Demo

A live version can be easily hosted. You can deploy this single `index.html` file to services like [GitHub Pages](https://pages.github.com/), [Netlify](https://www.netlify.com/), or [Vercel](https://vercel.com/).

## 🚀 Core Features

*   ✅ **The Daily Three:** A simple, focused list for your top 3 priorities of the day.
*   🔥 **Streak Counter:** Stay motivated by building a streak of completed days.
*   📊 **Statistics Page:** Get insights into your progress with metrics like Current Streak, Longest Streak, Total Days Completed, and overall Task Completion %.
*   📅 **Calendar History:** Visualize your successful days over time with a simple, clean calendar.
*   ☀️/🌙 **Light & Dark Themes:** Switch between a light and dark mode for your comfort, day or night.
*   💪 **Daily Motivational Quotes:** Get a small dose of inspiration every day.
*   💾 **100% Client-Side:** All data is saved directly in your browser's `localStorage`. No accounts, no sign-ups, and it works offline.
*   📱 **Responsive Design:** Looks and works great on both desktop and mobile devices.

## 🛠️ Tech Stack

This project is intentionally simple and self-contained.

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
*   **Dependencies (CDN):**
    *   [Font Awesome](https://fontawesome.com/) for icons.
    *   [Google Fonts](https://fonts.google.com/) for the 'Nunito' typeface.
*   **Storage:** Browser `localStorage` API.

## ⚙️ How to Use

There are two ways to use this application:

1.  **Locally:**
    *   Clone this repository or download the `index.html` file.
    *   Open the `index.html` file in your favorite web browser (like Chrome, Firefox, or Safari).

2.  **Deploy it:**
    *   Fork this repository.
    *   Go to your new repository's settings and enable GitHub Pages for the `main` branch.
    *   You'll have your own live, personal version of the app in minutes!

## 🎨 Customization

Since everything is in a single file, customization is straightforward.

*   **Colors & Fonts:** Open `index.html` and find the `<style>` tag. All colors are defined as CSS variables inside the `:root` and `body.dark-theme` selectors. You can change these values to create your own theme.
*   **Quotes:** The motivational quotes are stored in a JavaScript array called `QUOTES`. You can add, remove, or change them as you like.
*   **Number of Tasks:** While designed for three, the app can be modified to handle a different number of tasks by adjusting the initial `appData.tasks` array in the JavaScript.

## 🤝 Contributing

Pull requests are welcome! For major changes or new features, please open an issue first to discuss what you would like to change.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📜 License

This project is licensed under the MIT License.

> **MIT License**
>
> Copyright (c) 2023
>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.
