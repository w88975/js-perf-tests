Javascript Performence Tests
=============

- [for (...) {}](http://jsperf.com/i-vs-i-jare)
- [array copy](http://jsperf.com/copy-loop-vs-array-slice/13): new Array(len) and copy in loop is fastest
- [Visitor](http://jsperf.com/visitor)
- [Cache](http://jsperf.com/cache-in-loop/3): no difference, but cached faster in IE 11 (except array item cache)
- [Enumerate Object Properties](http://jsperf.com/enumerate-object-properties-vs-array-items/4)
- [apply arguments](http://jsperf.com/calling-function-vs-apply-with-arguments/5)
- [create object: (new Object() vs {})](http://jsperf.com/new-array-vs-literal/26)
- [create array: (new Array() vs [])](http://jsperf.com/new-array-vs-literal/24)
- [init object: (new Object() vs {})](http://jsperf.com/new-object/2/)
- [get value from object: (new Object() vs {})](http://jsperf.com/get-value-from-object-vs-hashtable): not stable, seems almost no any difference.
- [flag operation](http://jsperf.com/flag-op): no difference, but !! and ! faster in IE 11
- [check reference nil vs check another flag](http://jsperf.com/nullable): check flag is faster
- [check property exists](http://jsperf.com/hasownproperty-vs-in-vs-undefined/12)
