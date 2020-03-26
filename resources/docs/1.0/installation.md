# Installation

Anofie Pro comes with an installer that makes the installation process fully automated and smooth as 🍻

---

![Anofie Pro Installer](https://anofie-pro-docs.classiebit.com/images/pro-installer-1.jpg "Anofie Pro Installer")


> {info.fa-youtube} A complete video tutorial guide for getting started quickly is **Coming Soon**

---

- [Server Requirements](#Server-Requirements)
- [Remember](#Remember)
- [Install](#Install)
- [Purchased From Codecanyon](#Purchased-From-Codecanyon)


<a name="Server-Requirements"></a>
## Server Requirements

* PHP version **7.1** or newer is recommended.
* Make sure **.htaccess** is enabled.
* Required PHP Extensions - `Mbstring`, `BC Math`, `GMP`


<a name="Remember"></a>
## Remember

* If installing on the local system, please do not create a database, just enter localhost database credentials & installer will auto-create the new database.
* Anofie Pro can also be installed on `subdomain.example.com` or `example.com/subfolder/`
* The `captcha` & `upload` directory must be **writable**
* After installation if you see something like `Error number: 1146 Table settings don't exist` or a `blank page`, **just hit refresh**.


<a name="Install"></a>
## Install

1. Download & Unzip the package.
2. Copy all from the **Anofie Pro package** folder and paste it into your website directory.
3. Your website directory should look like this.

    ```bash

    example.com
    │
    ├── application
    ├── captcha
    ├── install
    ├── system
    ├── themes
    ├── upload
    │
    ├── .htaccess
    └── index.php

    ```

4. Visit `example.com/install` to run the installer. 
5. Enter database credentials.
6. Enter the license key or purchase code.
6. Choose if you wish to install **with** or **without** dummy data.
7. Click Install to start the installation process.
8. After the installation successful, **PLEASE DELETE THE INSTALL FOLDER**


>{warning} Make sure **.htaccess** files exist and not hidden.


<a name="Purchased-From-Codecanyon"></a>
## Purchased From Codecanyon

If you've purchased Anofie Pro from Codecanyon `codecanyon.net` then follow these simple steps-

1. Enter `Purchase-code` as License key in Anofie Pro installer.
2. Visit [classiebit.com](https://classiebit.com), signup as new user and go to [Downloads](https://classiebit.com/downloads)
3. Click on <larecipe-button radius="half" type="black">Purchased from Codecanyon?</larecipe-button>
4. In the popup, enter the Purchase-code and submit. You'll see the product in the downloads list.
5. At last, add the authorize domain. And you're good to go. 👍


---

> {danger} DO NOT FORGET TO DELETE THE **INSTALL** FOLDER