# ECO-Report

Product item type will be set at the item attribute level.
These custom attributes are set at EGO attribute tables.
Query:
  SELECT product_type
    FROM ego_custom_attribute_table
   WHERE INVENTORY_ITEM_ID = <To be passed from the base query>

To be joined with the original report query.
