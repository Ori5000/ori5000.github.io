## **Full DDL to Google Drive Guide**



That guide will show you how to import files from mega.nz for example, to your google drive! 



**(1)** Go to <https://rclone.org/downloads/> and download the version you need, depends your OS.

**(2)** Once the file is downloaded, extract the file to a new folder with software like 7-zip or WinRAR (7-zip is recommended).

**(3)** Once extracting is done open the CMD from the rclone directory (`C:\Downloads\rclone` for example). Type `rclone config` in the CMD.

**(4)** After you typed `rclone config` type `n`, then it will ask you for a name, call it `Drive`, now type `15` and click enter, now press Enter twice, type `1`, then press Enter 4 times, a window will open, select the account you want to use his Google Drive, and click Ok, come back to the CMD and type `n`, then `y`. lastly click `q` to quit rclone. now type `rclone config file` and go to the directory of the rclone config file.

**(5)** Go to <https://my.jdownloader.org> and follow the register instructions.

**(6)** Go to your Google Drive and make a folder called Downloads.

**(7)** Open <https://colab.research.google.com/github/cheems/Any-file-to-Google-Drive/blob/master/Any_file_to_Google_Drive.ipynb> & Click on Connect, click on the play button near `Mount Google Drive with Rclone`, it will ask you for the rclone config file from previously, upload it to the colab script by dragging it to the button.

Click on `Click Here to Install JDownloader` and login with the account you created recently. in `Save Path:` type `/content/Downloads`, then click on Login. go back to <https://my.jdownloader.org> and click on `Refresh` click on the big button, It will loading the Web Interface.

**(8)** Come back to the colab script and expand the RcloneLab section, in `Destination:` enter `Drive:Downloads`

**(9)** Open the console in the colab page and paste this script:

```
function ConnectButton(){

    console.log("Connect pushed"); 

    document.querySelector("#top-toolbar > colab-connect-button").shadowRoot.querySelector("#connect").click() 

}

setInterval(ConnectButton,20000);
```

now you can close the console.

**(10)** Come back to <https://my.jdownloader.org/> and click **__Add Links__**, paste your DDL Links there. And click Continue, now right click on the link and choose `Add to Downloads`, go to the Downloads section & wait until the download is completed.

**(11)** Go back to the colab page and run the RcloneLab. after it will say "✅ Operation has been successfully completed." go to your Google Drive and the Downloads folder you created recently & refresh it.



And that's it! The file you added in JDownloader will be in the Google Drive!



Credits: Esoterica Avenue, <https://discord.gg/enMG8bXUbn>, it has more guides about piracy & cracked software.

**If one of the links is dead, or the guide has outdated content feel free to kindly ping or DM me, Ori#4448**
