# Features Overview

Smart Migrator simplifies data migration with key functionalities:


## Extract
Extract Tab allows users to customize what they extract from entire warehouses to specific modules or tables. Options include setting paths, excluding tables or columns, running test extracts, and generating logs, ensuring precise and efficient data extraction.

### Key Components:

- **Tailored Extraction**: Select specific warehouses, modules, or tables and exclude unwanted data.
- **Custom Preferences**: Hide IDs, skip non-essential columns, and set custom paths.
- **Test & Logs**: Preview data with test extracts and use logs for validation.

For detailed instructions, please refer to the [Extract](./extract.md) section.

---

## Load
The Load Tab allows data import via Direct Load for quick transfers or Create Rollout for controlled, script-based setups. It offers options to filter data, exclude tables, and perform test loads, supporting both simple and complex deployments.

### Key Components:

- **Two Load Methods:** Choose Direct Load for quick transfers or Create Rollout for flexible, script-based setups.
- **Customizable Options**: Filter modules, exclude tables, and configure load operations and destination settings.
- **Test & Remote Loading**: Validate with Test Load and enable remote data transfers for flexibility.

For detailed instructions, please refer to the [Load](./load.md) section.

---

## Validate Load
The Validate Load feature compares data in the destination server with the extracted data to ensure accuracy. It highlights discrepancies, provides error logs for troubleshooting, and allows users to save validation results in CSV format for further analysis.

### Key Components:

- **Accurate Comparison**: Validates data in the destination server against the extracted data.
- **Discrepancy Detection**: Highlights mismatches and provides error logs for troubleshooting.
- **Result Management**: Saves validation results in CSV format for analysis and documentation.

For detailed instructions, please refer to the [Validate Load](./validate-load.md) section.

## Remove Warehouse 
The Remove Warehouse feature provides a secure and controlled way to delete an entire warehouse or specific data from a selected server.

 It includes authentication, selective removal options, and backup capabilities to ensure safe operations.

 For detailed instructions, please refer to the [Remove Warehouse](./remove-warehouse.md) section.

## Options

This feature allows Download XML.This feature allows users to retrieve version-specific XML files directly from the cloud. Users can select the required source and destination versions, choose the download type (Load, Extract, or both), and specify the save location.

This functionality ensures that the correct XML versions are available for migration and configuration processes.

For step-by-step instructions and detailed field descriptions, please refer to the [Download XML Files](./download-xml-files.md) section.

---