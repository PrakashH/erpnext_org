
    cur_frm.cscript.custom_validate = function(doc) {
        if (doc.from_date < get_today()) {
            msgprint("You can not select past date in From Date");
            validated = false;
        }
    }
    

