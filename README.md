# Ganje cpanel Skeleton 🛠️

**Ganje Host cPanel Skeleton Directory Files**

Welcome to the official repository for Ganje Host's cPanel skeleton directory. This repository contains files that can be used as templates for newly created user accounts on a cPanel server. By placing these files in the skeleton directory, all new accounts will automatically inherit these files in their `public_html` folder.

---

## 📄 Overview

The cPanel skeleton directory (`/root/cpanel3-skel/`) allows hosting providers to define default files and folders that are automatically included in new cPanel accounts when they are created. This is useful for setting up a default web page or providing important resources such as readme files, terms of service, or other essential assets.

In this repository, the `public_html` folder contains the files that will be copied to the `public_html` directory of new cPanel users by default.

For more information about cPanel skeleton directories, visit the [cPanel Documentation](https://docs.cpanel.net/).

---

## ⚙️ Installation

To install these skeleton directory files on your server, follow the steps below:

### Using Bash

1. Open your terminal.
2. Navigate to the `/tmp` directory.
3. Clone this repository.
4. Move the `public_html` folder to the skeleton directory.
5. Clean up by removing the cloned repository.

```bash
cd /tmp
git clone https://github.com/Ganjehost/Ganje-cpSkel
mv Ganje-cpSkel/public_html /root/cpanel3-skel/
rm -rf Ganje-cpSkel
```

---

By following these steps, all new cPanel accounts on your server will automatically have the files from this repository in their `public_html` folder.