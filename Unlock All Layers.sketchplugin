
var doc = context.document;
var page = doc.currentPage();
var layers = page.children();

for (var i=0; i<[layers count]; i++) {
	var layer = layers[i];
	if (layer.isLocked()) {
		layer.setIsLocked(false);
	}
}