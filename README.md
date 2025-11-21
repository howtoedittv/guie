🌟 Guie - A Simple Wrapper for BSD's `ee` File Editor  
Guie is a lightweight editor wrapper around `ee` (the Easy Editor), a terminal-based editor commonly found in BSD systems. It provides a clean and user-friendly interface for quick file edits directly from your terminal.  

🧩 Supported Environments  
Shell      | Supported  
------------|-----------  
bash       | Yes  
zsh        | Yes  

🚀 Installation  
You can install Guie in two simple ways. Choose the method that works best for you:  

1. **Clone the Repository**  
If you prefer cloning the repository, follow these steps:  
git clone https://github.com/howtoedittv/guie.git  
cd guie  
mv guie.tar.gz ~/  
cd ~  
tar -xvf guie.tar.gz  
cd guie  

2. **Download the Release Tarball (Recommended for Simplicity)**  
To download the release tarball, make sure you’re in your home directory before running the following commands:  
cd ~  
wget https://github.com/howtoedittv/guie/releases/download/1.0/guie.tar.gz  
tar -xvf guie.tar.gz  
cd guie  

⚙️ Setup & Configuration  
After downloading and extracting Guie, follow these steps to complete the setup.  

**Step 1:** Run the configuration scripts  
First, configure Alacritty by running:  
./termconfig  
Next, run the installer script:  
./installscript  

**Step 2:** Apply shell configuration  
Choose the shell you’re using (`bash` or `zsh`) and run the appropriate script.  
For **bash**:  
./bashconfig  
For **zsh**:  
./zshconfig  

**Step 3:** Finalize folder setup  
Create the necessary directories for Guie by running:  
./mkdirconfig  

▶️ Usage  
After installation, you can easily launch Guie from the terminal:  
guie  
For single-file editing, simply use `ee` with the desired filename:  
ee "filename"  

⚠️ Important Notes  
- **Do not** run `ee.sh` or `ee.desktop` directly. These are automatically handled by the `installscript` for you.  
- Supported shells: **bash** and **zsh** (with more coming soon).  
- Always run the **wget** method from your **home directory** for proper setup.  

📜 License  
MIT License
