# serverstatus
##Server Status Monitor Desklet Description

The Server Status Monitor is a desklet for the Cinnamon desktop environment, designed for real-time monitoring of your server statuses. It provides a quick way to check the availability and operational health of remote hosts using various verification methods.

##Key Features:

* __Flexible Server Configuration:__ Add, edit, and remove servers from the monitoring list directly through the desklet's settings.

* Multiple Check Types Supported: The desklet can monitor servers using three primary protocols:

  ** Ping: Checks basic network reachability of the server.

  ** HTTP/HTTPS: Monitors the availability of web servers and web resources.

* Customizable Update Interval: Set your own interval (in seconds) for periodic server status checks.

* Real-time Status Display: Each server is shown on a separate line, indicating its name and current status (OK, WARN, ERR, Checking, Timeout).

* Customizable Appearance:

  ** Color Schemes: Adjust text colors for different statuses (basic, OK, warning, error), as well as background colors for the desklet container and individual server elements.

  ** Server Visibility: Temporarily disable the display of specific servers within the desklet without removing them from the settings list.

* Timeout Limits: Ping, HTTP/S, and SSH checks include built-in timeout limits (5 seconds by default), preventing the desklet from freezing due to unresponsive servers.

* Localization: The desklet supports multiple languages, ensuring ease of use for users with different linguistic preferences.

The Server Status Monitor is ideal for developers, system administrators, or anyone who needs a quick and convenient way to track the status of essential network resources directly from their Cinnamon desktop.
