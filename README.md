Programming-tips
================

1. Sort string of arraylist
---------------------------

Collections are used for sorting the string of arraylist

ArrayList<String> list = new ArrayList<String>();

Collections.sort(contactnamesList, new Comparator<String>() {
@Override
public int compare(String o1, String o2) {              
    return o1.compareToIgnoreCase(o2);
}
});
