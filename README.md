This repository hosts the **Data Knowledge Base**, built using **Obsidian**. It serves as a centralized collection of technical concepts, project documentation, goals, and research notes. The vault is version-controlled with **GitHub** to ensure regular backups and maintain a structured knowledge management system.

---

## **🔹 Purpose**

This vault contains key areas of work and learning.

It is intended to keep critical information organized, easily accessible, and up-to-date.

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

### Jupyter Notebook
To launch Jupyter Notebook: `python -m notebook`
Note: it may be helpful to alias this command to something like **notebook** (`alias notebook='python -m notebook'`)