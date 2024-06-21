Project Name
============

Setup Instructions
==================

Step 1: Clone the Repository
----------------------------
First, clone the repository to your local machine::

    git clone https://github.com/nirans2002/python_robot_sim.git
    cd python_robot_sim

Step 2: Create a Virtual Environment
------------------------------------
Create a virtual environment in the project directory::

    python -m venv venv

Step 3: Activate the Virtual Environment
----------------------------------------
Activate the virtual environment using the appropriate command for your operating system:

**On Windows:**

    venv\Scripts\activate

**On macOS/Linux:**

    source venv/bin/activate

Step 4: Install Dependencies
----------------------------
Install the required dependencies from the `requirements.txt` file::

    pip install -r requirements.txt

Step 5: Run Your Project
------------------------
Your virtual environment is now set up. Run your project as usual.

Updating Dependencies
=====================
Whenever you add new dependencies to your project, make sure to update the `requirements.txt` file::

    pip freeze > requirements.txt

Deactivating the Virtual Environment
====================================
When you are done working on your project, you can deactivate the virtual environment::

    deactivate

Additional Information
======================
For more information on using virtual environments in Python, refer to the `official documentation <https://docs.python.org/3/tutorial/venv.html>`_.
