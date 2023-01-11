# To Do

* Install UFW as dependency not as a separate task (should not be in a
task list for a service / package)
* Configure backups
* Add backupmx role in a separate environment
* Refactor large roles to better separate concerns by splitting up the roles
* Check ansible-galaxy for potentially useful roles
* Clean up variable usage
* Make roles usable standalone
* What to do about encrypting data?
	* The problem is autorestarting in the case OVH needs to intervene (for
	example of the monitoring indicates non-responsiveness), which at least at
	first is a reboot.
