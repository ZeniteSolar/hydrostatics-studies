

1. Install Python 3.8
``` yay -S python38 ```

2. Create a [Python Virtual Environment](https://docs.python.org/3.8/library/venv.html) called `env` using the installed Python:
``` python38 -m venv env ```

3. Activate the environement:
``` source env/bin/activate ``` (bash/zsh)
``` source env\Scripts\activate.bat ``` (cmd.exe)
``` source env\Scripts\Activate.ps1 ``` (PowerShell)

4. Upgrade the [pip](https://pip.pypa.io/en/stable/) module:
``` pip install pip --upgrade ```

5. Install the requirements from `requirements.txt`:
``` pip install -r requirements.txt ```