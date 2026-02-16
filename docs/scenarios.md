# Migration Scenarios

Warehouse Migrator supports multiple migration scenarios to accommodate different business and technical requirements. 

Whether upgrading system versions, promoting changes across environments, or cloning warehouse configurations, the tool provides a structured and controlled migration process.

## Environment-to-Environment Migration

This scenario ensures that configurations validated in lower environments are promoted to production without manual re-entry.

- **Primary Path:** Development (DEV) → Quality Assurance (TEST) → Production (PROD).

- **Supported Versions**
    - Direct migration between environments on the same version.
    - Migration from v2017 to any higher supported version.

## Version Upgrade Migration

Migrate warehouse configuration and supported data from an older Blue Yonder WMS version to a newer release.

This scenario is particularly useful during system upgrades where schema changes and structural differences must be carefully managed.

**Supported Cases:**

- Migration from version 8.2 to any higher supported version  

## Warehouse-to-Warehouse Migration Within the Same Instance

Clone or replicate configuration and supported data from one warehouse to another within the same server instance.

This scenario is commonly used for:

- New warehouse setup  
- Multi-site deployments  
- Standardized configuration rollout  

## Module-Specific Migration

Migrate selected modules instead of the entire warehouse configuration. This allows targeted changes without impacting unrelated configurations.

**Examples include:**

- Location setup only   
- Inventory-related configuration 

## Selective Table Exclusion

Exclude specific tables from migration based on business or technical requirements.

This capability provides greater control over what is migrated, allowing organizations to:

- Prevent unnecessary data transfer  
- Avoid overwriting environment-specific configurations  
- Maintain controlled and phased rollouts  

---