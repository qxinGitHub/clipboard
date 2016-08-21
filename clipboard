function clipboard(text){
    var node = document.createElement("textarea");
    node.value = text;
    document.body.appendChild(node);
    node.select();
    document.execCommand("Copy");
    document.body.removeChild(node);
}
