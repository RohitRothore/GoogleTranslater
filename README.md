# 🌐 Google Translate Integration

This project demonstrates how to integrate **Google Translate** into a static HTML page to support multilingual translations, especially for Indian regional languages.

## 📋 Features

- Integrates [Google Translate Element](https://cloud.google.com/translate/docs/element).
- Language selector dropdown with basic custom styling.
- Supports 13 Indian languages: Hindi, Kannada, Malayalam, Marathi, Tamil, Telugu, Bengali, Gujarati, Punjabi, Urdu, Assamese, Odia.
- Clean UI integration by hiding the Google Translate banner and frame.
- Print-safe: hides translation widget in print mode.

## 🛠️ Setup Instructions

1. Clone or download this HTML file.
2. Open the file in a browser — it will show a language dropdown.
3. Select a language from the dropdown to see live translation of the page content.

## 💻 Code Structure

- The widget is rendered inside a `<div id="google_element">`.
- The Google Translate script is loaded via:

  ```html
  <script src="http://translate.google.com/translate_a/element.js?cb=loadGoogleTranslate"></script>
