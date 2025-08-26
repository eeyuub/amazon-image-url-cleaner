Amazon Image URL Cleaner

A simple, single-page web tool to extract clean, high-resolution image URLs from complex, parameter-filled Amazon links.
🚀 About This Tool

Have you ever tried to save a product image from Amazon, only to get a URL that's hundreds of characters long, full of strange codes and resizing parameters? This tool solves that problem.

Amazon Image URL Cleaner takes those messy URLs and instantly extracts the core, high-quality image link. It's perfect for designers, marketers, or anyone who needs a clean link to an Amazon product image without any of the extra junk.
✨ Features

    Clean URLs Instantly: Paste a complex Amazon image URL and get the clean version in one click.

    Action Buttons:

        🔗 Open in New Tab: Quickly view the cleaned image.

        📋 Copy URL: Copy the clean link to your clipboard.

        💾 Download Image: Download the high-resolution image directly to your device.

    User-Friendly Interface: Simple, intuitive, and responsive design that works on any device.

    Error Handling: Clear feedback for invalid or malformed URLs.

    No Server Needed: Runs entirely in your browser. It's just one HTML file!

🛠️ How It Works

The tool's logic is straightforward. Complex Amazon image URLs often contain the primary image filename embedded within a larger string, separated by URL-encoded pipe characters (%7C).

This script identifies the base URL (https://.../images/I/), splits the remaining path by the separator, and extracts the third segment, which corresponds to the clean, high-resolution filename. It then reconstructs the final, clean URL.
▶️ How to Use

    Clone or download this repository.

    Open the index.html file in any modern web browser.

    Find an image on Amazon and copy its image address.

    Paste the URL into the input field.

    Click the "Clean URL" button.

    Use the "Open," "Copy," or "Download" buttons as needed!

💻 Technologies Used

    HTML: For the basic structure of the page.

    Tailwind CSS: For modern and responsive styling.

    Vanilla JavaScript: For all the logic, with no external libraries or frameworks needed.

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.