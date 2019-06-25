# StationaryMailFiles
The macOS Sierra (10.12) files required for https://apple.stackexchange.com/a/327301/263848


-----

**You must have a copy of the following files from a computer running High Sierra (10.13) or lower** In this example I used files from Sierra (10.12)

  

 - `/Applications/Mail/Contents/Resources/ComposeWindow.toolbar`
   
 - `/Library/Application Support/Apple/Mail`

If you would like the stationery in the original mail application then skip step 1, disable **SIP**, and continue with the original application, **SIP** can be reenabled after. **Make copies of everything**. Instead of "replace" add a `.orig` to the file extension.

1. Duplicate the Mail Application

2. Right click on the new Mail Application and go to `/Contents/Resources/`

3. Replace the `ComposeWindow.toolbar` with the `ComposeWindow.toolbar` from the copied files

4. Go to Finder>Go To Folder>`/Library/Application Support/Apple/`

5. Copy the `Mail` folder from the copied files to this folder

6. Open the Mail application and compose a new email

7. Right Click on the Toolbar and select `Customize Toolbar`

8. Drag the icon labeled `Show Stationery` to your toolbar and hit done

9. Click the `Show Stationery` button in your toolbar 

**Note:**  The toolbar item **DOES** work with dark mode but the Stationery Panel **does not**.
