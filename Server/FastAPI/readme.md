routes :-
- "/retrieve_all_items_details" : To fetch list of all items.<br\>
        Parameters:<br\>
            skip : <br\>
            limit :<br\>
    - "/add_new_item" : To add new item.<br\>
        Parameters:<br\>
            item(item_name, seller, category, quantity)<br\>
    - "/reduce_item_by_id" : To reduce the quantity of any item in inventory.<br\>
        Parameters:<br\>
            r_quantity: Amount by which quantity is reduced.<br\>
            sl_id: pK of item<br\>
    - "/update_item_details" : To update the item<br\>
        Parameters:<br\>
            update_param(item_name, seller, category, quantity)<br\>
            sl_id: pK of item<br\>
