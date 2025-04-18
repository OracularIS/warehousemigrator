# Features Overview

Smart Migrator simplifies data migration with key functionalities:

## Configuration File
The Configuration File Tab lets users upload through Smart API or a custom file to define how data is extracted, mapped, transformed, and loaded. After selecting the file, users connect to the source server securely with credentials. This setup offers flexibility and control over the data migration process.

### Key Components:

- **Flexible Configuration**: Choose between Smart API setup or custom file.
- **Source Server Authentication**: Authenticate with your source server using a username and password.
- **Customizable Data Migration Flow**: Configure extraction, transformation, and loading processes tailored to your needs.

 For detailed instructions, please refer to the [Configuration File](./configuration-file.md) section.

---

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



