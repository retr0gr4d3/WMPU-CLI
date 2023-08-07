<div align="center">
  <h1>WM Pro Unlocker - CLI</h1>
  <h4>This program patches the WM app to think you're a pro subscriber.</h4>
  
#### [Back to the main page](../README.md)

<br/>
</div>

## ⬇️ Installation
Installation is handled by [Cargo](https://rustup.rs/).
+ Install Cargo.
+ Clone this github repo.
+ Move the project somewhere easy to access.
+ Open CMD/Powershell.
+ Write ```cargo install --path``` followed by the whole path, i.e. ```C:\Users\Username\Documents\WMPU-CLI\cli```
+ Once it has finished, simply run ```wemod-pro-unlocker``` in CMD/Powershell.

<br/>

## ⚙️ Configuration
| Argument                  	| Description                                                                                                                           	| Example
|---------------------------	|---------------------------------------------------------------------------------------------------------------------------------------	|----------------------------------
| --wemod-dir <dir>         	 	 	 	 	 	 	          	  | Path to your WeMod dir. By default, this is "%localappdata%/WeMod".                                         	| C:\WeMod
| --wemod-version <version> 	 	 	 	 	 	 	          	  | The version to patch. By default, this will be the latest version installed. 	                                | 1.2.3
| --account <json>            	 	 	 	              	  | Overwrites the account data. You can find all available options by searching for /v3/account in the dev tools | username:'myaccount',email:'test'
| -no-update / -offline            	 	              	  | Doesn't check for/install updates                                                                             | ---
| -v                          	 	 	 	 	            	  | Prints out the version info. Will cancel everything else                                                      | ---

<br/>
