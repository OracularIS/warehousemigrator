# Remove Warehouse
Remove Warehouse feature can be accessed from the tools tab. 

  <div style="text-align: left;">
     <img src="./.attachments/toolp.png"
        alt="EditServers"
          style="height: 200px; margin: auto; display: block; cursor: zoom-in;
          border: 2px solid #000000; border-radius: 4px;"
          onclick="this.style.height='400px'; this.style.cursor='zoom-out';"
          ondblclick="this.style.height='200px'; this.style.cursor='zoom-in';">
    </div>

This interface provides secure and customizable options for managing warehouse removal while allowing for data-specific actions and backups.

  <div style="text-align: left;">
     <img src="./.attachments/remove_warehouse.png"
        alt="EditServers"
          style="height: 200px; margin: auto; display: block; cursor: zoom-in;
          border: 2px solid #000000; border-radius: 4px;"
          onclick="this.style.height='400px'; this.style.cursor='zoom-out';"
          ondblclick="this.style.height='200px'; this.style.cursor='zoom-in';">
    </div>


  - **Server (Required)**
    - Dropdown to select the server where the warehouse resides.

  - **Connect**
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

⚠️ *Note: Warehouse removal is irreversible unless a backup is created.*

  ---