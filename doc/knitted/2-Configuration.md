Configuration
=============

The first step of working with OpenML should be to register yourself at the [OpenML website](http://openml.liacs.nl). Most of the package's functions require a session hash which is only accessible with a (free) account.

After the registration you should create a configuration file under `~/.openml/config`. This file may contain the following information:
* username
    * the e-mail address you used to register at the website
* password
* server
    * default: http://www.openml.org 
* verbosity:
    * 0: normal output
    * 1: info output (default)
    * 2: debug output
* cachedir:
    * default: $HOME/.openml/cache

The configuration file is not mandatory. Filling out username and password is recommended, because then you will not have to type it in each time you need a new session hash. Note however, that basically everybody who has access to your computer can read the configuration file and see your password, so please use this password ONLY for OpenML.

If you have done these two steps, you are ready to go. Have fun!

----------------------------------------------------------------------------------------------------
Jump to:    
[Introduction](1-Introduction.md)  
Configuration  
[Stage 0 - Listing](3-Stage-0-Listing.md)  
[Stage 1 - Downloading](4-Stage-1-Downloading.md)  
[Stage 2 - Running models on tasks](5-Stage-2-Running.md)  
[Stage 3 - Uploading](6-Stage-3-Uploading.md)  
[Example workflow with mlr](8-Example-workflow-with-mlr.md)