eclipse-classic-php-formatter
=====================

Preview:

```xml
<?php

namespace test;

use test1;
use test2;
use test3;

/**
 * Blank Lines
 */
class Example {
	const CONST2 = 3;
	var $theInt = 1;

	public function foo($a, $b) {
		switch ($a) {
			case 0 :
				$Other->doFoo();
				break;
			default :
				$Other->doBaz();
		}
	}

	function bar($v) {
		for($i = 0; $i < 10; $i++) {
			$v->add($i);
		}
	}
}

namespace test1;

interface MyInterface {
}
?>
```
