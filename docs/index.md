This API enables external control of ProDVX panels with built-in LED lights.  
To see these installation instructions, open a browser on your ProDVX panel and go to [tiny.cc/prodvxapi](https://avdistributors.github.io/prodvx-api/).

## Installation Steps
1. Download APKs for Termux and Termux:Boot using the buttons at the top of this page.
2. Install both apps by either clicking on the download in the notification bar, or using the "ApkInstaller" app.
3. Run Termux:Boot, then close.
4. Run Termux. Leave Termux open.
5. Click the code snippet below to copy the command for your device, then paste and run it inside Termux.
6. Allow the code to run and install the API. The panel will reboot itself, after which the API will be functional.
7. Usage details can be found on the GitHub page (button at top left of this page).

### SLB
```
pkg install curl -y && bash <(curl https://raw.githubusercontent.com/avdistributors/prodvx-api/master/install_slb.sh)
```
  
### DSKPL/DSQPL
```
pkg install curl -y && bash <(curl https://raw.githubusercontent.com/avdistributors/prodvx-api/master/install_dskpl.sh)
```