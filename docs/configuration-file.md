# Configuration File

The Smart Warehouse Migrator offers a flexible and efficient setup process through two main configuration methods:

  1. **Using the Smart API**: A guided, streamlined approach for quick and easy setup.

  <div style="text-align: left;">
  <img src="./.attachments/smartapi.png"
       alt="EditServers"
       style="height: 200px; margin: auto; display: block; cursor: zoom-in;
              border: 2px solid #000000; border-radius: 4px;"
       onclick="this.style.height='400px'; this.style.cursor='zoom-out';"
       ondblclick="this.style.height='200px'; this.style.cursor='zoom-in';">
   </div>

  2. **Custom Configuration File**:
    This allows you to provide your own file for  Smart Configuration tab and then browse your file.
    
      1. Place your file in the following folder:
     `\SmartMOCAClient\config\swm\WhMigConfigFiles`

     2.  Open the **Smart Configuration** tab in Warehouse Migrator and browse to select your file.

  <div style="text-align: left;">
  <img src="./.attachments/custom.png"
       alt="EditServers"
       style="height: 200px; margin: auto; display: block; cursor: zoom-in;
              border: 2px solid #000000; border-radius: 4px;"
       onclick="this.style.height='400px'; this.style.cursor='zoom-out';"
       ondblclick="this.style.height='200px'; this.style.cursor='zoom-in';">
   </div>

- Once a configuration file is selected, users can securely connect to their source systems by providing credentials. 

The configuration defines the entire data migration workflow, including how data is extracted, mapped, transformed, and loaded into target systems.

These configuration files specify:

- How data is extracted from source systems.
- How data is loaded into target systems.
- Settings and parameters for:
  - Data extraction processes.
  - Mapping source data to target structures.
  - Applying necessary transformations.

---