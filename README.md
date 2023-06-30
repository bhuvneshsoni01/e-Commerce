# e-Commerce\n
routes :-\n
\t- "/retrieve_all_items_details" : To fetch list of all items.\n
\t\tParameters:\n
\t\t\tskip : \n
\t\t\tlimit :\n
\t- "/add_new_item" : To add new item.\n
\t\tParameters:\n
\t\t\titem(item_name, seller, category, quantity)\n
\t- "/reduce_item_by_id" : To reduce the quantity of any item in inventory.\n
\t\tParameters:\n
\t\t\tr_quantity: Amount by which quantity is reduced.\n
\t\t\tsl_id: pK of item\n
\t- "/update_item_details" : To update the item\n
\t\tParameters:\n
\t\t\tupdate_param(item_name, seller, category, quantity)\n
\t\t\tsl_id: pK of item\n
