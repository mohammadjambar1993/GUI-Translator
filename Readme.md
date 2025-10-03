Step 1: Create a virtual environment

Open a terminal in VS Code (`Ctrl+``).

Run:
''
python -m venv venv
''

Activate the virtual environment:
''
.\venv\Scripts\activate
''

You should now see (venv) at the start of your terminal prompt.

Step 2: Install required packages

Run:
''
pip install --upgrade pip
pip install PyQt5 googletrans==4.0.0-rc1
''

googletrans==4.0.0-rc1 is required because the stable version is broken.

Step 3: Verify packages
''
python -m pip show PyQt5
python -m pip show googletrans
''

You should see details about each package.

Step 4: Run your app

Make sure you are in the folder with main.py and run:
''
python main.py
''

Your PyQt5 GUI should launch!