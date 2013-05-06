kindlesongs
===========

Not yet for what is this, but it will letme backup mi kindle ebooks...

cat ~/treeKindle.txt | sed  's/──//g' | sed "s/└ //g" | sed "s/├ //g" | sed "s/│   //g" | sed "s/    //g" | egrep  "(.pdf|.mobi|.azw)"
