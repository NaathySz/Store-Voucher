# Store-Voucher
Voucher module for Store: Create vouchers to give credits and redeem them to receive credits. The module handles voucher generation, storage, and redemption, with customizable commands and permissions.

# Config
Config will be auto generated. Default:
```json
{
  "generate_voucher_admin_only": false,
  "generate_voucher_admin_flag": "@css/generic",
  "skip_credit_check_flag_enabled": false,
  "skip_credit_check_flag": "@css/slay",
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
