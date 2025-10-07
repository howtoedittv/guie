**guie** is a simple editor wrapper built around the ee file editor from the bsd bases opreting systems .  


---

# 🚀 Installation


You can download **guie** in two ways:



1.**Clone the repository**  


git clone https://github.com/howtoedittv/guie.git  


cd guie  


mv guie.tar.gz ~/  


cd ~  


tar -xvf guie.tar.gz  


cd guie  




2.**Download release tarball (from home directory)**  


⚠️ Make sure you are in your **home directory** before running these commands:  


cd ~  


wget https://github.com/howtoedittv/guie/releases/download/1.0/guie.tar.gz  


tar -xvf guie.tar.gz  


cd guie  



---

# ⚙️ Build & Install



**Step 1: Run the installer**  


./installscript  



**Step 2: Apply shell configuration**  


Run the file corresponding to your shell (currently **bash** and **zsh** are supported):  


./bashconfig  


or  


./zshconfig  



**Step 3: Finalize create folders**  


./mkdirconfig  



---

# ▶️ Usage


After installation, launch **guie** with:  


guie

or if you want to edit a single file just do:

ee "filename"



---

# ⚠️ Notes


- Do **not** run `ee.sh` or `ee.desktop` directly.  

  The `installscript` will handle them for you.  


- Supported shells: **bash** and **zsh** (more coming soon).  


- If using the **wget method**, always run it from your **home directory**.  



---

# 📜 License


MIT License
