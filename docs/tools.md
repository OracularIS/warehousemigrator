# Tools
  **Tools** provides two key options for managing your warehouse operations:
  1. **Remove Warehouse**
  2. **Options**

  ![](./.attachments/tool.png)

## Remove Warehouse

This interface provides secure and customizable options for managing warehouse removal while allowing for data-specific actions and backups.


![](./.attachments/remove_warehouse.png)


  - **Server (Required)**
    - Dropdown to select the server where the warehouse resides.

  - **Connect**as
    - Establishes a connection to the selected server.

  - **User Authentication**
    - Fields for entering **Username** and **Password** to authenticate access to the server.

  - **Login**
    - Logs the user into the selected server.

  - **Warehouse Selection (Required)**
    - Dropdown to choose the specific warehouse for removal.

  - **Specific Data**: Checkbox to remove specific data from the warehouse.
  - Radio buttons to choose the type of data to remove:
    - **Transaction**: Removes transaction-related data.
    - **Configuration**: Removes configuration-related data.

  - **Backup**: Creates a backup of the warehouse data before initiating removal.
  - **Remove**: Executes the warehouse removal process based on the specified options.
  - **Cancel**: Discards changes and exits the interface.
 
   **NOTE:** This feature is currently unavailable 

  

  ---

## Options Submenu
![](./.attachments/option.png)

This section outlines the various options available when downloading XML files from the cloud.

**Source Version:**

This dropdown menu allows you to select the specific source version of the XML files you wish to download.

**Destination Version:**

This dropdown menu allows you to select the specific destination version of the XML files you wish to download.

**File Location:**

This field displays the default location where the downloaded XML files will be saved. You can modify this path by clicking the **Browse...** button and selecting a new destination folder.

**Download Options:**

* **All:** Selecting this option will download both the load and extract versions of the XML files.
* **Load:** Selecting this option will download only the load version of the XML files.
* **Extract:** Selecting this option will download only the extract version of the XML files.

**Download Button:**

Once you have selected your desired options, click the **Download** button to initiate the download process.
