routes:-\
- "/retrieve_all_items_details": To fetch a list of all items.\
        *Tabspace*Parameters:\
                *Tabspace**Tabspace*skip :\
                *Tabspace**Tabspace*limit :\
- "/add_new_item": To add a new item.\
        *Tabspace*Parameters:\
                *Tabspace*item(item_name, seller, category, quantity).\
- "/reduce_item_by_id": To reduce the quantity of any item in inventory.\
        *Tabspace*Parameters:\
                *Tabspace**Tabspace*r_quantity: Amount by which quantity is reduced.\
                *Tabspace**Tabspace*sl_id: pK of item.\
- "/update_item_details": To update the item.\
        *Tabspace*Parameters:\
                *Tabspace**Tabspace*update_param(item_name, seller, category, quantity).\
                *Tabspace**Tabspace*sl_id: pK of item.\
