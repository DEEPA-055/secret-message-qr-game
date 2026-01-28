# 📱 Simple QR Code Generator

A clean, lightweight, and interactive web application that generates QR codes instantly in your browser. Designed with a focus on user experience, the interface automatically declutters itself to showcase your generated code.

## 🚀 Live Demo
**Try it here:** [https://deepa-055.github.io/secret-message-qr-game/](https://deepa-055.github.io/secret-message-qr-game/)

## ✨ Features
* **Instant Generation:** Converts text or URLs into QR codes immediately.
* **Smart UI:** The input box automatically hides after generation to keep the focus on the QR code.
* **Reset Function:** A "Create New Code" button appears to easily reset the app for the next user.
* **Privacy Focused:** Runs entirely in the browser (Client-Side). No data is sent to any server.
* **High Contrast Design:** Uses a vibrant yellow background (`#fff700`) and teal accents for a modern look.

## 🛠️ Technologies Used
* **HTML5:** Semantic structure of the application.
* **CSS3:** Flexbox layout and responsive styling.
* **JavaScript (Vanilla):** Logic for DOM manipulation and state management.
* **Library:** `qrcode.js` (via CDN) for rendering the QR matrix.

## 📂 How to Run Locally
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/DEEPA-055/secret-message-qr-game.git](https://github.com/DEEPA-055/secret-message-qr-game.git)
    ```
2.  **Open the file:**
    Navigate to the folder and double-click `index.html` to open it in your default browser.
3.  **Enjoy:** No installation or local server required!

## 🧩 Code Snippet (Logic)
The app uses a toggle mechanism to switch between the "Input View" and "Result View":

```javascript
// Hides input and shows reset button
inputGroup.style.display = "none";
resetBtn.style.display = "block";

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.

📄 License
This project is licensed under the MIT License.

🙏 Credits
QR Code generation logic powered by the qrcode.js library.

Created with ❤️ by Deepa-055
