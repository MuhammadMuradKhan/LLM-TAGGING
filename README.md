# Project Setup Instructions

## Required Tools / Files

1. [RapidMiner](https://my.rapidminer.com/nexus/account/index.html#downloads)
2. RapidMiner Python extension
3. [Anaconda](https://www.anaconda.com/download/success)
4. OpenAI key for GPT-4
5. Workflow and Exercise files

## Step 1: Install RapidMiner Studio

1. Download RapidMiner Studio from the provided link.
2. Install RapidMiner Studio with default settings.
3. Once installed, download the Python extension from the RapidMiner extension marketplace.

## Step 2: Install Anaconda

1. Download Anaconda for Python using the provided link.
2. Install Anaconda with default settings.

## Step 3: Add Anaconda to the PATH Environment Variable in Windows

### Open System Properties

1. Press `Win + R` to open the Run dialog.
2. Type `sysdm.cpl` and press Enter to open the System Properties window.

### Open Environment Variables

1. In the System Properties window, go to the `Advanced` tab.
2. Click on the `Environment Variables` button at the bottom.

### Edit the PATH Variable

1. In the Environment Variables window, find the `Path` variable in the `System variables` section.
2. Select the `Path` variable and click `Edit`.

### Add Anaconda to the PATH

1. In the Edit Environment Variable window, click `New`.
2. Add the following paths one by one:
    - `C:\ProgramData\anaconda3`
    - `C:\ProgramData\anaconda3\Scripts`
    - `C:\ProgramData\anaconda3\Library\bin`
3. Click `OK` after adding each path.

### Apply the Changes

1. After adding the paths, click `OK` to close the Edit Environment Variable window.
2. Click `OK` again to close the Environment Variables window.
3. Click `OK` to close the System Properties window.

### Verify the PATH Variable

1. Open a new Command Prompt window by pressing `Win + R`, typing `cmd`, and pressing Enter.
2. Type `conda --version` and press Enter.
3. If Anaconda has been added to the PATH correctly, the version of Anaconda will be displayed.

## Step 4: Configure and Test Python Inside RapidMiner

1. Open RapidMiner and place the `Execute Python` operator into the process window.
2. Click on the `Execute Python` operator to see its parameter options on the right side of the screen.
3. In the parameter window, uncheck the `Use default Python` option.
4. Inside the Package Manager dropdown list, click on `conda(anaconda)`.
5. Finally, press the `Test` button in front of the text `Conda Environment`. It should show a `Success` message.

## Step 5: Obtain an OpenAI API Key for GPT-4

### Create an OpenAI Account

1. Visit [OpenAI Platform](https://platform.openai.com).
2. Click on the "Sign Up" button and follow the instructions to create a new account if you don't have one.
3. If you already have an account, click "Log In" and enter your credentials.

### Access the API Key Section

1. Once logged in, go to the OpenAI Dashboard. You can typically find this by clicking on your account profile and selecting "API" or "API Keys" from the dropdown menu.

### Create an API Key

1. In the API Keys section, you will see an option to create a new API key. Click on the `Create API Key` button.
2. You may be prompted to give a name or description for the key for easier identification later. Enter the details as needed and confirm the creation of the key.

### Retrieve Your API Key

1. After creating the key, it will be displayed on the screen. Copy the API key and store it in a secure place.
2. Note that for security reasons, this is usually the only time the full API key will be displayed.

### Store Your API Key Securely

1. Store your API key in a secure location.
2. Do not share it publicly or expose it in your code repositories.
3. It’s best practice to use environment variables or secret management tools to manage your API keys securely.

## Step 6: Download and Run Workflow and Exercise Files

1. Download the workflow and exercise files as shown in the accompanying video.
2. Follow the instructions in the video to run the files.

---

This README file provides a step-by-step guide for setting up the required tools and configuring the environment for your project. Follow each step carefully to ensure a smooth setup process.