# Prowlnotify

Little cli tool to let you push notifications to your phone. Modelled after `growlnotify` for growl.

	Julius:prowlnotify(master) caius$ ./bin/prowlnotify --help
	Usage: prowlnotify [options] MESSAGE

	Message can be either a string or "-" to read from stdin

	    -k, --api-key [KEY]              Prowl API Key [optional]
	                                     If this isn't specified then ~/.prowl is read
	    -p, --priority [VALUE]           Priority of notification. [optional]
	                                     Defaults to "Normal"
	                                     Value between -2 and 2, or a string:
	                                     	 -2. Very Low
	                                     	 -1. Moderate
	                                     	  0. Normal
	                                     	  1. High
	                                     	  2. Emergency

	    -a, --application [NAME]         Name of application sending notification. [optional]
	                                     Defaults to "prowlnotify"
	    -s, --subject [STRING]           Subject line. [optional]
	    -r, --provider-key [KEY]         Provider API key. [optional]
