# dcs-get

A tool for managing packages in DCS as Warwick University, may be useful for anyone in an environment with multiple users 
without root access needing specific linux applications.

## Files

**dcs-get**: Main script

**dcs-get-client**: Node.js implementation of the script

**dcs-get-api**: Api between the client and the server

**dcs-get-server**: Server for managing multiple/parallel downloads.

**dcs-get-install**: Install script

**index.php**: Webpage containing installation 
instructions

**bashrc**: Code to add to a .bashrc file to install dcs-get

**tabcomplete**: Code to add to a .bashrc file to add tab completion

**package.php**: Webpage which outputs all packages in the repository

**uploader.php**: Script for handling uploads

## Todo list

* Server persistance.
* Handle multiple versions of same package.

## License

All code written as part of this project falls under an MIT license, included libraries are licensed as described.
