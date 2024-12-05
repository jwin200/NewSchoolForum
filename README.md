# NewSchoolForum

The following is documentation for a local Flask server instance on macOS.

Before getting started, make sure that the latest version of Python is installed locally.

Open a terminal, create a folder and navigate to it with:
    `mkdir newschoolforum`
    `cd newschoolforum`

Clone the repository to this folder:
    `git clone https://github.com/jwin200/NewSchoolForum.git .`

Launch a python virtual environment:
    `python3 -m venv .venv`
    `. .venv/bin/activate`

Install Flask:
    `pip install --upgrade pip && pip install Flask`

To launch the server, run:
    `flask run`

Open a browser and navigate to "http://127.0.0.1:5000"