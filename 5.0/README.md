## Directory Description
This directory contains all of the subdirectories that include files unique to the RDA TDS 5.0 instance running on Tomcat8.
Typically $CATALINA_HOME=/usr/share/tomcat on a linux system.


| File                                   |          Description  |
|:--------------------------------------|:----------------------|
|`conf/Catalina/localhost/thredds.xml`   | RDA TDS specific DB access config to support RDA user access recording |
|`content/tdm/` | Contains script to run tdm which is used to index metadata in support of feature collections |
|`content/thredds/` | Contains RDA TDS threddds catalogs | 
|`content/thredds/public/` | contains RDA specific user interface specs (RDA banner,etc) |
|`jarfiles/` | contains jarfiles used to support RDA TDS role access.  Copy into $CATALINA_HOME/lib |
|`RDA_RealmSourceCode/` | contains source code and build instructions for edu.ucar.rda.RDARealms.jar |
|`WEB-INF/web.xml` | contains RDA dataset lockdown configuration.  Copy into $CATALINA_HOME/webapps/thredds/WEB-INF |

