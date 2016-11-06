# domeasy

Easily add elements to the DOM in a natural JS way

__Examples:__

    var div = document.getElementById("main").$div({id: "myDiv", cn: "myClass"});

    var table = div.$table();
    var row   = table.$thead().$tr();

