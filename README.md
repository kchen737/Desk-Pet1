# Desk Pet
 The file ending in py is a python file that creates a desk pet that will appear on the desktop.
 In order to compile and run the python file, you will need to install PyQt5 either using pip install or create a virtual environment.

 # Virtual environment
 - In the terminal type python3 -m venv env
 - To activate the virtual environment use: source env/bin/activate
 - Install pyqt5 using the virtual environemnt: python3 - pip install PyQt5
 - In order to use the plugins of pyqt5: echo 'export QT_QPA_PLATFORM_PLUGIN_PATH="path/to/plugin/platforms"'>> ~/.zshrc
 - Finalize the changes: source ~/.zshrc
 - Check if it is there: echo $QT_QPA_PLATFORM_PLUGIN_PATH
   
