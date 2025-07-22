# Installation <a id="module-teamdashboards-installation"></a>

## Requirements <a id="module-teamdashboards-installation-requirements"></a>

* Icinga Web 2 (&gt;= 2.12.2)
* PHP (&gt;= 7.3)

## Installation from .tar.gz <a id="module-teamdashboards-installation-manual"></a>

Download the latest version and extract it to a folder named `teamdashboards`
in one of your Icinga Web 2 module path directories.

## Enable the newly installed module <a id="module-teamdashboards-installation-enable"></a>

Enable the `teamdashboards` module either on the CLI by running

```sh
icingacli module enable teamdashboards
```

Or go to your Icinga Web 2 frontend, choose `Configuration` -&gt; `Modules`, chose the `teamdashboards` module and `enable` it.

It might afterwards be necessary to refresh your web browser to be sure that
newly provided styling is loaded.