# Password_Security_PCFG_Attack_Simulator

### INSTRUCTIONS FOR RUNNING THE CODE:

The code consists of a single .IPYNB file, and can be run in either a local Jupyter Notebook environment, or via the Google Colab link below.

Google Colab Notebook Online Link:
https://colab.research.google.com/drive/1UjRmw23g8707qupQPpmApiibLFHN1F5S


To run the code:
- Download the PHPBB password dataset as a text file: (https://github.com/danielmiessler/SecLists/blob/master/Passwords/Leaked-Databases/phpbb.txt)
- Rename it to "phpbb_passwords.txt", and upload it to the Google Colab environment. If running this notebook locally, then move the file into the same directory as the notebook.
- Click "Run All" (or Kernel -> "Run All Cells") at the top of the page.


Required Libraries:
- requests
- numpy
- matplotlib
- pytextrank
- spacy (en_core_web_sm)

Note that the code should automatically download/install these when it is run.
