# Configuration <a id="module-teamdashboards-configuration"></a>

## Module Configuration  <a id="module-teamdashboards-configuration"></a>

### Create a Mapping  <a id="module-teamdashboards-configuration-mapping-create"></a>
![mapping](img/create.png)


| Option                | Required | Description                              |
| --------------------- | -------- | -----------------------------------      |
| Dashboard Username    | **yes**  | The Username to fetch the dashboards from|
| Alias             | no  | Define an Alias that will be shown instead of the username as the menueitem|
| Priority             | **yes**  | Priority of the Dashboard in the menu |
| Enabled               | no       | Enable or disable this entry                    |

### List and update a Mapping  <a id="module-teamdashboards-configuration-mapping-list"></a>
![mapping](img/mappings.png)


## Role Configuration  <a id="module-teamdashboards-configuration-role"></a>
This module provides the following permissions:
![roles](img/roles.png)

If you want to restrict a users from accessing the dashboard mapping you can do this in the IcingaWeb2 Roles settings.
> teamdashboards/mapping

You will also see an entry for each available dashboard mapping and can allow groups or users to access this dashboard.
> teamdashboards/mapping/`<user>`

Every dashboard you are allowed to see is will be listed in the menu.
