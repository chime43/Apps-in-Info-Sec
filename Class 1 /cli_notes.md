# Web Application Setup and HTML File Creation

This document outlines the steps to create and view an HTML file on a Kali Linux virtual machine.

### Prerequisites

* **Operating System:** Kali Linux Virtual Machine
* **Web Server:** Apache (often pre-installed or can be installed with `sudo apt-get install apache2`)

---

### Step-by-Step Guide

1.  **Log in as Root User:**
    Log into your Kali Linux virtual machine. A terminal will automatically open with `root` as the host name.

2.  **Open a Text Editor:**
    Use the `mousepad` text editor to create a new file.

    ```bash
    sudo mousepad /var/www/html/cis59_schedule.html
    ```

    *Once you press Enter, a new window for the `mousepad` text editor will open.*

3.  **Add HTML Content:**
    Inside the text editor, create your HTML file. Below is an example of the basic HTML structure you can use.

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CIS 59</title>
    </head>
    <body>
        <h1>Merritt College</h1>
        <h2>CIS 59</h2>
        <h3>Fall 2020</h3>
        <hr>
        <h2>Class Topics</h2>
        <p>This is where you would list your topics.</p>
    </body>
    </html>
    ```

4.  **Save and Exit:**
    * Save the file by pressing `Ctrl + o`, then `Enter`.
    * Exit the text editor by pressing `Ctrl + x`.

5.  **View the HTML File in a Browser:**
    Open your web browser, navigate to the address bar, and type the following URL to view the file you just created.

    ```
    http://localhost/cis59_schedule.html
    ```

6.  **Optional: List the File:**
    You can verify that the file was created in the correct directory by listing the files within the `/var/www/html/` folder.

    ```bash
    ls /var/www/html/
    ```

---
