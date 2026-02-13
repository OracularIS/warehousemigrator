# Migration Scenarios

Warehouse Migrator supports multiple migration scenarios to accommodate different business and technical requirements. 

Whether upgrading system versions, promoting changes across environments, or cloning warehouse configurations, the tool provides a structured and controlled migration process.

## Environment-to-Environment Migration

Migrate a warehouse configuration from a lower environment (e.g., Development) to a higher environment (e.g., Production).

- **Supported Versions**
    - Migration from version 2017 to production environment.
    - Migration between environments running the same version.

## Version Upgrade Migration

Migrate warehouse configuration and supported data from an older BlueYonder WMS version to a newer version.

- **Supported Versions**
    - Migrating from version 8.2 to any higher version.

## Warehouse-to-Warehouse Migration Within the Same Instance

Migrate configuration and data from one warehouse to another within the same server instance.

## Module-Specific Migration

Migrate only selected modules instead of the entire warehouse configuration.

- **Supported Versions**
    - Migrating only location setup.
    - Migrating only user roles or inventory configuration.

## Selective Table Exclusion

Exclude specific tables from migration based on business or technical requirements.

---