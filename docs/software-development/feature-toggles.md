Feature Toggle is a powerful technique, allowing teams to modify system behavior without changing code.

We use it to give control to turn on or off the feature that is under development, it solve following problems:

* Bug fixing report during feature development.
* Disabling the new feature on production due to the bug/error detection.
* To asynchronize the different team's work, the team that finishes the work pushes their work to production and turns off the feature switch until it is permitted to be published.
  
## <span style="font-weight:400;">Application</span>
We create a configuration file in an environment that is not compiled on the main source code containing switches for turning on/off the system features.

We follow the below process to implement Feature Toogle:  
 
!!! info "Configuration File"
	* We select a place to setup configuration such as (Firebase Remote Config, Settings.dat for website, GrowthBook or any other sources).
	* Configure the variables to act as switch with selecting the default value.
	* Publish initial configuration.
	* Toggle on/off when requested.
 

!!! info "Source Code Configuration"
	* Import configuration environment on the system.
	* Fetch the latest configuration file ro the system and activate it.
	* Access the configuration using SystemSwitch class.
	* Implement the feature and make it visible when the configuration is turned on.
 