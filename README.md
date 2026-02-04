# Google Drive Magnet Flow

<!-- Badges Section -->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-mate/google-drive-magnet-flow/blob/main/google_drive_magnet_flow.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.x](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/downloads/)

**Google Drive Magnet Flow** is a powerful and privacy-focused Google Colab notebook designed to streamline the process of downloading magnet links, optionally encrypting the content, and securely uploading it directly to your Google Drive. This project ensures efficient management of your downloads with enhanced security and automatic cleanup.

### Features:

*   **Magnet Link Downloading:** Supports downloading multiple magnet links.
*   **Optional Encryption:** Encrypt your downloaded content using password-protected ZIP or 7-Zip archives for enhanced privacy.
*   **Secure Password Handling:** Implements `getpass` for hidden password input and retry mechanisms for confirmation.
*   **Direct Google Drive Upload:** Seamlessly uploads encrypted archives (or raw downloads) to your mounted Google Drive using `shutil`.
*   **Automated Local Cleanup:** Ensures that all local temporary files and download directories are cleaned up after the process, regardless of upload success.
*   **No Rclone Dependency:** Optimized for direct Google Drive integration without the need for `rclone` configuration.
*   **Privacy-First Archiving:** Encrypted archives are named with a timestamp, ensuring no descriptive words are publicly exposed.
*   **Clean Archive Structure:** Encrypted ZIP files do not include parent folders (`/content/downloads`), placing content directly at the archive's root.

### How it Works:

1.  **Input Magnet Links:** Provide one or more magnet links.
2.  **Choose Encryption (Optional):** Decide whether to encrypt your downloads and select between ZIP or 7-Zip compression.
3.  **Set Encryption Password:** Enter and confirm a strong password (input is hidden).
4.  **Specify Google Drive Destination:** Define the subfolder in your Google Drive where files will be uploaded.
5.  **Automated Processing:** The notebook handles the download, encryption (if chosen), upload, and local cleanup.

---

## Legal Notice

This project is provided for educational and research purposes only. The developer does not support or endorse any illegal use of this tool. Users are solely responsible for their actions and for complying with all applicable laws and regulations in their respective jurisdictions. Use this tool at your own risk.

---

## Author

*   **Augusto Mate** — *Early Development*
*   [@augusto-mate](https://github.com/augusto-mate)

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

### Inspiration

> "And whatsoever ye do, do *it* heartily, as to the Lord, and not unto men." (Colossians 3:23)
