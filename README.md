# DbD_From Data to Information
![dbd-fromdatatoinfomation](https://user-images.githubusercontent.com/50297074/145735112-2aa14714-b428-4ee7-91ed-6da0f3c96a39.png)

This repository is produced within the ENPC Design by Data - From Data to Information seminar

## Requirements
- [Rhinoceros](https://www.rhino3d.com/download/) (7)
- [Python 3](https://www.python.org/downloads/) (ideally 3.7 +)

## to run the Python script
## Installation
1. **[create a repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)**
  - open a Terminal (mac) or run PowerShell (win)
  - change directory to access the repository `example: cd /Users/xxx/Desktop/city-dna`
2. **[virtual environment](https://docs.python.org/3/tutorial/venv.html)**
  - with only Python3 installed `python -m venv env_DATAtoINF`
  - if Python2 and Python3 installed `python3 -m venv env_DATAtoINF`
  -  mac: `source /env_DATAtoINF/bin/activate`
  -  win: `.\env_DATAtoINF\Scripts\activate`
3. **install dependencies**
  - `pip install -r requirements.txt`

## Usage
- Change directory in the Terminal/PowerShell to repository folder
- Activate your virtual environment (as explained above)
- Run the script

## Troubleshooting
- if `.\env_DATAtoINF\Scripts\activate` fails to run in Windows
  - make sure you run Powershell as Administrator 
  - `Set-ExecutionPolicy RemoteSigned`
  - `y`
  - `.\env_DATAtoINF\Scripts\activate`
