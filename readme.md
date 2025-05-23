
<h1 align="center">UBSIxGEMINIai</h1>
<p align="center"><i>AI for everything</i></p>
<p align="center">
  <img src="https://github.com/ashraprjct/BSIxGEMINIai/blob/main/package/logo/tes.gif?raw=true" alt="Video Demo" width="600" />
</p>
<p align="center">
  <img src="https://github.com/ashraprjct/BSIxGEMINIai/blob/main/package/logo/nilai.png?raw=true" alt="Video Demo" width="600" />
</p>
<p align="center">
  <a href="https://www.youtube.com/watch?v=j9VRcVIxbDE" target="_blank">
  watch on youtube
  </a>
</p>

## Features

- **Auto Collect Cookie Gemini AI**: Automatically collects cookies from Gemini AI (Google login required).
- **Answer Accuracy**: Provides answers with 90% accuracy.

## How To Use

1. **Install Microsoft Edge**:
   - Download and install Microsoft Edge from the [official website](https://www.microsoft.com/edge).

2. **Install Python**:
   - Download and install Python from the [official website](https://www.python.org/downloads/).

3. **Clone the Repository**:
   - Open a terminal and run:
     ```sh
     git clone https://github.com/ashraprjct/BSIxGEMINIai
     ```

4. **Install Requirements**:
   - Navigate to the project directory:
     ```sh
     cd BSIxGEMINIai
     ```
   - Run the following command to install the required Python packages:
     ```sh
     pip install -r requirements.txt
     ```

5. **Run the Script**:
   - Execute the main script:
     ```sh
     python Main.py
     ```

6. **Login with Google**:
   - Login with Google to receive the cookie.

7. **Handling Selenium Detection**:
   - If Google detects Selenium, try changing the port, delete the "ujang shelby" folder, and run it again.
   - Wait 10 seconds.

8. **Get Answers**:
   - Use `/` to get the answer.

## For Windows Users (if crash occurs)

- Download the Edge WebDriver.
- Change `service=EdgeService(EdgeChromiumDriverManager().install())` to `service=PATH TO EDGEWEBDRIVER`.

## For Fedora Linux Users

If you're using **Fedora** (or any distro with Python 3.13 as default), you must install **Python 3.11** manually and make it the default version for this project:

### 1. Install Dependencies

```sh
sudo dnf groupinstall "Development Tools"
sudo dnf install gcc openssl-devel bzip2-devel libffi-devel wget make zlib-devel
```
### 2. Install Python3.11

```sh
sudo dnf install python3.11 python3.11-pip
```
### 2. Create virtual env and start
```sh
python3.11 -m venv env
source env/bin/activate
pip3.11 install -r requirements.txt
python3.11 Main.py
```

## Tested On

- Kali Linux
- Windows 10
- Fedora 41


Thanks
