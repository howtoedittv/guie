# ✨ guie ✨
**guie** is a simple editor wrapper built around the [Easy Editor (ee)](https://github.com/howtoedittv/Easyeditor). It features an easy installation process and supports both **bash** and **zsh** shells.

---

# 🚀 Installation
You can install **guie** in two ways:

1. **Clone the repository**
git clone https://github.com/howtoedittv/guie.git
cd guie
mv guie.tar.gz ~/
cd ~
tar -xvf guie.tar.gz
cd guie

2. **Download release tarball (from home directory)**
⚠️ Make sure you are in your **home directory** before running these commands:
cd ~
wget https://github.com/howtoedittv/guie/releases/download/1.0/guie.tar.gz
tar -xvf guie.tar.gz
cd guie

---

# ⚙️ Build & Install
**Step 1: Build (only if you don’t already have `ee` installed)**
./eebuild
👉 **Arch & Arch-based distros**: skip `eebuild` and install `ee` directly:
yay -S ee-editor

**Step 2: Run the installer**
./installscript

**Step 3: Apply shell configuration**
Run the file corresponding to your shell (currently **bash** and **zsh** are supported):
./bashconfig
or
./zshconfig

**Step 4: Finalize setup**
./mkdirconfig

---

# ▶️ Usage
After installation, launch **guie** with:
guie

---

# ⚠️ Notes
- Do **not** run `ee.sh` or `ee.desktop` directly. The `installscript` will handle them for you.
- Supported shells: **bash** and **zsh** (more coming soon).
- If using the **wget method**, always run it from your **home directory**.

---

# 📜 License
MIT License
