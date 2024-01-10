# Installation Instructions for the January 2024 Cohort

To succeed in your first coding courses, installing any software locally is not a must. You can use cloud applications like [Replit](https://replit.com), [Google Colab](https://colab.research.google.com), or [Deepnote](https://deepnote.com). These platforms are free and allow you to download Python files to your local computer (and then submit them on Canvas if you need to).

[Google Colab](https://colab.research.google.com) is particularly effective at converting between `.ipynb` (Jupyter Notebook file format) and `.py`. Therefore, we recommend getting familiar with all three.

Towards the end of Year 1, you will likely want to code locally on your machine. We recommend the following installations:

- [Python](https://www.python.org/downloads/)
- [VSCode](https://code.visualstudio.com/)
- [Jupyter Notebook](https://jupyter.org/) or [Anaconda](https://www.anaconda.com/download)

If you have permission issues but are considering a software engineering pathway, you may also want to install Node JS, which is not covered in this session as it will not be needed till later.

## Installing 🐍 [Python](https://www.python.org/downloads/) 🐍

### Check for an Existing Installation

To find the command prompt (terminal), Windows users should type “cmd” in the search bar; ‘terminal” for Mac. Mac, Linux, and Windows users can check if there is already a version installed by running one of the following commands in the command prompt:

```bash
python --version
```

or

```bash
python3 --version
```

Here is what it looks like on a Mac with a custom terminal:

![python3 --version on a Mac says Python 3.11.4](python_version_mac.png)

For some people, only `python3 --version` will show the version, and for others, only `python --version`. Try both.

You need Python 3, a version later than 3.6.

### Downloading Python

#### Step 1. Visit the official [Python website](https://www.python.org/downloads).

The website should automatically suggest the best version for your Windows system. Click on the link to download the Python installer: Download Python 3.12.1 

#### Step 2. Run the Installer.

Go to your Downloads folder: click on the “python-3.12.1-amd64.exe”

Before you proceed, make sure to check the box at the bottom that says:

⚠️ **"Add python.exe to PATH". This step is crucial as it allows you to run Python from the Command Prompt, as shown in the figure below.**

!["Add python.exe to PATH" - box ticked](path_tick.png)

#### Step 3. After checking the box, click on “Install Now”.

#### Step 4. Verify the Installation

Go to Windows search: type "cmd" to open a new command prompt or open a terminal on a Mac.
Type in the command prompt:

```bash
python --version
```

or

```bash
python3 --version
```

![python --version](windows-version.png)
