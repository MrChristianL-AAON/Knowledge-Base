This repository hosts the **Data Knowledge Base**, built using **Obsidian**. It serves as a centralized collection of technical concepts, project documentation, goals, and research notes. The vault is version-controlled with **GitHub** to ensure regular backups and maintain a structured knowledge management system.

---

## **🔹 Purpose**

This vault contains key areas of work and learning, as well as a walkthrough of how to get up and running using the various programs, languages, and packages of our current tech stack.

This knowledge base is intended to keep critical information organized, easily accessible, and up-to-date.

---

## **🔹 Obsidian Git Setup**

This vault is synced with GitHub using the **Obsidian Git** plugin. Follow these steps to set up **Obsidian Git** for your vault:

1. Install **Obsidian** to your machine. Once installed, set up your Obsidian account and be sure to sign in.
    
2. Clone the Knowledge Base to your local machine. Within Obsidian, open the Knowledge Base as a vault.
    
3. Within Obsidian, enable **Community Plugins** within your settings (the gear icon in the bottom left). Install the **Obsidian Git plugin** (listed only as *Git*) from the Community Plugins section.
    
4. Within your Obsidian Git plugin settings, enable **auto commit and sync** for regular backups. The standard window is 10 minutes for commit-and-sync.
    

For more detailed Obsidian Git setup instructions, visit the [Obsidian Git setup guide](https://publish.obsidian.md/git-doc/Start+here).

---

## **🔹 Setting Up Your Environment with Python**

### Python Virtual Environment (venv)
1. Create your project folder (`mkdir project_folder`)
   
2. Create the virtual environment (`python -m venv .venv`). 
	   In this instance, our virtual environment is named .venv, but you can name it anything.
   
3.  Activate the virtual environment (`source .venv/Scripts/activate`)
	   If done correctly, you should now see the name of your virtual environment in your terminal (e.g. `(.venv) user@yourmachine ~/project_folder`) 
   
4. Install the necessary python packages (`pip install -r C:/Users/christian.leonard/requirements.txt`)
   
5. Verify installation (`pip list`) 
	   This will show all the python packages and dependencies that are now installed within your virtual environment.
   
6. When ready, deactivate your virtual environment by performing the `deactivate` command in your terminal.

#### Jupyter Notebook
To launch Jupyter Notebook: `python -m notebook`
Note: it may be helpful to alias this command to something like **notebook** (`alias notebook='python -m notebook'`)

##### Standard Notebook Imports
The following imports are standard at the top of all notebooks, for convenience
```python 
import math
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
```

---
## **🔹 Setting Up Your Application Development Environment**

### Node.js and npm
To install Node.js, visit the official [Node.js](https://nodejs.org/) website.
Here, you will find a Node.js installer. This will install both Node.js and npm.

To test that each has been installed, utilize the following commands:
```bash
node --version
npm --version
```
### TypeScript
To install TypeScript, utilize the following command:
```bash
npm install -g typescript
```
This will install TypeScript globally. To test that TS has been correctly installed, run the following command: `tsc --version`

### Vite
To install Vite, we will use the following command:
```bash
npm install -g vite
```
To test, run the following: `vite --version` or `npm run dev`

From here, we can now utilize React and Preact using Vite and the npm package manager.
### React
The npm package manager should now handle React commands, such as creating a React application. This can be done with the following command:
```bash
npm create vite@latest my-react-app -- --template react
```

To test: `npm run dev`

This will build your React application, allowing for the application to be viewed locally in your web browser.

### Preact
Similarly to React, Preact applications can be created via the following command:
```bash
npm create vite@latest my-preact-app -- --template preact
```

To test: `npm run dev`

This will build your Preact application, allowing for it to be viewed locally in your web browser.

### Rust
To install Rust, utilize the rustup installer, found at [rustup.rc](https://rustup.rs/)

Follow the on-screen instructions to install Rust and the Rust package manager, Cargo.

To test: 
```bash
rustc --version
cargo --version
```

Additionally, you can now create Rust applications using the following Cargo commands:
```bash
cargo new hello-rust
cd hellow rust
cargo run
```
### Tauri
To install Tauri, you must have the following prerequisites met:
- [-] Rust installed
- [-] Node.js installed

Once these prerequisites have been met, Tauri can be installed using Cargo. To install, run the following command:
```bash
cargo install create-tauri-app
```
To create a Tauri application, run the following:
```bash
npm create-tauri-app
cd my-tauri-app
npm install
npm run tauri dev
```
### Electron
Following a similar installation to React and Preact, Electron applications can be created with the following commands:
```bash
npx create-electron-app my-electron-app
cd my-electron-app
npm start
```

### MQTT Explorer
To install the MQTT Explorer, download the installer from [the official MQTT website](https://mqtt-explorer.com/) and follow the necessary on-screen instructions.