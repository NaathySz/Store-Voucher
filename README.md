# [Store module] Voucher
Voucher module for Store: Create vouchers to give credits and redeem them to receive credits. The module handles voucher generation, storage, and redemption, with customizable commands and permissions.

# Config
Config will be auto generated. Default:
```json
{
  "max_vouchers_per_command": 20, // Maximum number of vouchers that can be generated per command
  "generate_voucher_admin_only": false, // If true, only admins can generate vouchers
  "generate_voucher_admin_flag": "@css/generic", // Flag required for admins to generate vouchers if the above is true
  "skip_credit_check_flag_enabled": false, // If true, the person generating vouchers will not be charged
  "skip_credit_check_flag": "@css/slay", // Flag required to bypass credit charges if the above is true
  "print_to_server_console": false, // If true, prints voucher codes to the server console
  "print_to_client_console": true // If true, prints voucher codes to the client console
  "generate_voucher_commands": [
    "generate_voucher"
  ],
  "use_voucher_commands": [
    "use_voucher",
    "voucher"
  ],
  "database_host": "localhost",
  "database_port": 3306,
  "database_name": "name",
  "database_user": "root",
  "database_password": "password"
}
```
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/L4L611665R)
