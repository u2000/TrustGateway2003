Welcome to VeriSign's Trust Gateway Early Access 1.0

Startup
-------

Windows: 
  The installer places five icons under the Trust 
  Gateway heading in your Start menu:

  * README.txt
  * Start TrustGateway
  * Stop TrustGateway
  * Trust Gateway Administration
  * Uninstall Trust Gateway

  Select Start TrustGateway to initialize the Gateway.
  If you installed as a Service, the Trust Gateway 
  is started automatically when you restart your machine.

Solaris and Linux:
  
  Run startup.sh found in the /bin directory of the 
  installation. You must run as root to install and 
  deploy the Trust Gateway on Solaris and Linux.

Console Login
-------------

Give the Trust Gateway a few moments to initialize.

Once the Trust Gateway has started:

On Windows, select the Trust Gateway Administration
icon under the Start Menu.

On Solaris and Linux, open a browser window.
 
Enter the following URL in your browser:

  http://localhost:8776/console/

(Note that if you set a different administration
port number during installation, you should
substitute that number for the default value, 8776,
in the URL above.)

Once you have configured SSL, always use your
fully qualified host name (rather than localhost)
to log into the  Administration console.

The Console Login page displays.

Enter the username and password you 
configured during installation.

To change your password, select the ADMIN tab once
you have logged into the Administration Console.

For guidelines on configuring the Trust Gateway through
the console, please refer to the Trust Gateway 
Administrator's Guide, found in the /docs directory
of the Trust Gateway CD.

Setup
-----

This Early Access of the Trust Gateway release ships 
with a sample certificate to use as a default credential.
Therefore, you are not required to register for a 
default key to run the Early Access version.

If you would like to test registration, and you require
a keyname/passcode, please contact:
 
trustgateway@verisign.com

Distribution Contents
--------

If you selected the full install, you will find the 
following contents under the Trust Gateway installation 
directory.

apache_license.txt    The apache license
RELEASE_NOTES.txt     Updates/Known Issues
README.txt            This document
version.txt           Trust Gateway version
log.txt               Installer log

_uninst
  The uninstallation application

/bin
  Commands for running the Trust Gateway

/common
  UI resources

/conf
  Server configuration files

/docs
  Documentation and licenses

/jvm1.4.1.2
  The version of Java which is automatically installed 
  with the Trust Gateway

/server
  Server files

/temp
  Temporary files

/toolkit
  Trust Services Integration Kit (TSIK), sample 
  Trust Gateway components, and testing resources

/webapps
  The Trust Gateway and Administration Console servlets 
  and resources. 

/ws-security
  VeriSign's implementation of the WS-Security specification

Toolkit
-----

The /toolkit directory contains resources for 
testing and development, including the Trust Services 
Integration Kit (TSIK). 

The TSIK provides Java APIs for 
securing Web services. Please see the README
file in the /toolkit directory for details.

Troubleshooting
---------------

Refer to the Web help pages within the console for
troubleshooting tips.

If you are encountering problems while running the
Trust Gateway, be sure to check the logs, found 
under the /logs directory.

Contact
---------------

To provide feedback or to obtain more information, 

please contact:

trustgateway@verisign.com

Or visit:

http://www.verisign.com/products/trustgateway

-------------

The Trust Gateway Team

