Last modified: 2023-05-01

Author: Clein Alexander Sarmiento, HSRW

# Chicken Database Workshop
This repository is created for the chicken database workshop held in the HSRW together with Universität Bonn 

# Requirements
## PostgreSQL installation
    - Installation tutorial Windows(has links for linux and osx on page)
    https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/

    - Installation video for Windows:
    https://www.youtube.com/watch?v=0n41UTkOBb0

    - Installation video for OSX
    https://www.youtube.com/watch?v=Z-iM7hUdBSg
## Anaconda installation
    - Installation tutorial:
    https://docs.anaconda.com/free/anaconda/install/index.html

    - Installation video for OSX:
    https://www.youtube.com/watch?v=2JeoNlCcLOM

    - Installation video for Windows, embedded in a tutorial:
    https://www.geeksforgeeks.org/how-to-install-anaconda-on-windows/

# Installation
1. Download or clone the repository: https://github.com/Clein2312/Datascience_database_chicken.git
2. Install Anaconda, see the tutorials above.
3. Open Anaconda Prompt Terminal and type: <code>cd "/your_folder_path/"</code>, mind that you should replace the text between the quotation marks with your own path.
4. Create a new environment using the .yml file. For this you should type:  
    <code>conda env create -f environment.yml</code>
5. Activate the new environment using: 
    <code>conda activate chicken</code>
6. Intall PostgreSQL, see the tutorials above.
7. Install ipython-sql using:
    <code>pip install ipython-sql</code>
8. Install sqlalchemy using:
    <code>pip install sqlalchemy</code>
9. Install psycopg2 using:
    <code>pip install psycopg2</code>
10. Run jupyterlab in a file explorer:
    <code>jupyter lab</code>
    



# To Do

- Populate anaconda notebook

# IMPORTANT!

- Do not push broken code.
- Make sure to describe a bit your changes when you commit.
- Let me know when you are done with something and you would like to merge it (I'll check it faster)
