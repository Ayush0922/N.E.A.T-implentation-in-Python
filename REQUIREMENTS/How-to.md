# How to Install the Requirements

## Step 1: Download the `requirements.txt` File

Ensure you have the `requirements.txt` file downloaded to your local machine. This file contains a list of all the necessary libraries and dependencies for your project.

## Step 2: Install the Requirements

### For Python Versions Before 3.10

1. **Open Terminal:**
   Open your terminal application.

2. **Change Directory:**
   Navigate to the directory where your `requirements.txt` file is located.
   ```sh
   cd path/to/your/project
   ```

3. **Install Dependencies:**
   Run the following command to install the requirements.
   ```sh
   pip install -r requirements.txt
   ```

### For Python 3.10 and Later

#### Step 1: Install `venv`

- **Ubuntu:**
  ```sh
  sudo apt-get update
  sudo apt-get install python3-venv
  ```

- **macOS:**
  `venv` is included with Python 3.10 and later. If you don't have Python installed, you can install it using [Homebrew](https://brew.sh/):
  ```sh
  brew install python
  ```

- **Windows:**
  `venv` is included with Python 3.10 and later. No additional installation is required.

#### Step 2: Create a Virtual Environment

1. **Create an Environment:**
   ```sh
   python3 -m venv myenv
   ```

2. **Activate the Virtual Environment:**

   - **Ubuntu/macOS:**
     ```sh
     source myenv/bin/activate
     ```

   - **Windows:**
     ```sh
     .\myenv\Scripts\activate
     ```

#### Step 3: Install Dependencies

With the virtual environment activated, run:
```sh
pip install -r requirements.txt
```

## Additional Setup

### If You Do Not Have Python Installed

- **For Ubuntu Users:**
  Follow this [guide to install Python on Ubuntu](https://www.geeksforgeeks.org/how-to-install-python-in-ubuntu/).

- **For macOS Users:**
  Follow this [guide to install Python on macOS](https://docs.python-guide.org/starting/install3/osx/).

- **For Windows Users:**
  Follow this [guide to install Python on Windows](https://www.digitalocean.com/community/tutorials/install-python-windows-10).

---

With these steps, you should have all your project dependencies installed and ready to go. Happy coding! 🎉
