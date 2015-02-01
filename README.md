## BeyondCompare Chocolatey Package

###Forked from https://github.com/shiftkey/chocolatey-beyondcompare
Updated to seek out the latest Version 3 download, for those who haven't upgrade their license to Version 4. Perhaps it would have been easier to just upgrade the license, eh? 

*Original ReadMe by @ShiftKey...* but with a 3 at the end of the name in step 4.

This is the code I use to publish the BeyondCompare package to Chocolatey. 

It's actually really easy. 

 1. Follow the instructions on [chocolatey.org](http://chocolatey.org/) to setup Chocolatey
 2. Clone this repository and navigate to the folder in Powershell
 3. `cpack` to create the package
 4. `cinst beyondcompare3 -Source *"full-directory-path"*` to install it locally

And you're done!

## BeyondCompare3 has been updated! Help!

When a new release of BeyondCompare is out in the wild, there's two different ways you can help out:

 1. Raise an issue so I can track it in my GitHub notifications
 2. Submit a pull request with the necessary changes

It's not a hard task to update, just repetitive. So if you want to see it happen quicker, you can get involved!