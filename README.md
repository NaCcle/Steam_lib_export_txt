# Steam_lib_export_txt
This repo give you acces to a tamper mokey script who allow you to get all your steam game (from steamDB) into a .txt files.


# Utilisation

## Step 1: Install Tampermonkey Extension
Go to https://www.tampermonkey.net/.

Download and install the Tampermonkey extension for your browser (Chrome, Firefox, Edge, etc.).

Once installed, you will see the Tampermonkey icon in the top-right corner of your browser.


## Step 2: Create a New Script
Click on the Tampermonkey icon.

Select "Create a new script…" from the dropdown menu.

Delete all the default code that appears.

Paste the custom script in the editor.


## Step 3: Enable the Script
Make sure the script is enabled in your Tampermonkey dashboard.


## Step 4: Use the Script
Go to [SteaDB](https://steamdb.info/), use your steam account to login, go to "Your Games" in the top right icons.

Once the page is fully loaded, a green button should appear at the top-right corner of the page (The button is a bit buggy, it sometimes goes behind the profile icon but you can still click on it)

Click the button.

A .txt file containing all the extracted games will automatically be downloaded.


# How It Works

This Tampermonkey script automatically adds a custom "Exporter" button to any web page. When the button is clicked, the script performs the following steps:

Scans the page and selects all elements with the class name .b.

Extracts the visible text from each of these elements.

Compiles the collected texts into a single plain text file.

Automatically downloads the file as extracted_texts_b.txt to your device.


#Key Features:

Does not require manual copying — everything is done with one click.

Works on pages that are already loaded — no need to reload the page.

Lightweight and easy to customize (you can change the class name, file name, or even remove the button if desired).
