#cool-typescript

##Class

###typescript

```
class abc{
	attr:string;
	constructor(public arg){};
	methods(arg1){

	};
};

class def extends abc{}
```

###javascript

```
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var abc = (function () {
    function abc(arg) {
        this.arg = arg;
    }
    ;
    abc.prototype.methods = function (arg1) {
    };
    ;
    return abc;
}());
;
var def = (function (_super) {
    __extends(def, _super);
    function def() {
        _super.apply(this, arguments);
    }
    return def;
}(abc));
;
```