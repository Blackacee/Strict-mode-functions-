# Strict-mode-functions-

function strict() {
 "use strict";
 // strict mode now applies to the rest of this function
 var innerFunction = function () {
 // strict mode also applies here
 };
}
function notStrict() {
 // but not here
}
