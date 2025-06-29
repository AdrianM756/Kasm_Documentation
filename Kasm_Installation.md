## Kasm

[Kasm](https://kasmweb.com/) is a workspace streaming platform for delivering browsers, desktops and applications to the web browser.
<br>

![image](https://kasmweb.com/assets/images/logo.svg)
<br>

## Installation

On this demo, we will be installing Kasm on a Ubuntu machine.

First, navigate to the ```/tmp``` directory.
```
cd /tmp
```
<br>

Next, use the ```curl``` command to download the kasm image file from it's official website.
```
curl -O https://kasm-static-content.s3.amazonaws.com/kasm_release_1.17.0.7f020d.tar.gz
```
<br>

After dowloading the file, use the ```tar``` command to decompressed the file.
```
tar -xf kasm_release_1.17.0.7f020d.tar.gz
```
<br>

Once done, run the installation script.
```
bash kasm_release/install.sh
```
<br>

Once the installation is complete, go to your browser and navigate to the IP Address of the machine where Kasm is installed.

For the credential, use the ```username``` and ```password``` under the ```Kasm UI Login Credentials``` that was provided at of the installation.





