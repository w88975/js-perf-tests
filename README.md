Javascript Performence Tests
=============

- [for (...) {}](http://jsperf.com/i-vs-i-jare)
- [array copy](http://jsperf.com/copy-loop-vs-array-slice/13): new Array(len) and copy in loop is fastest
- [Visitor](http://jsperf.com/visitor)(eval seems no performence degradation)
- [Cache](http://jsperf.com/cache-in-loop/3): no difference, but cached faster in IE 11 (except array item cache)
- [Enumerate Object Properties](http://jsperf.com/enumerate-object-properties-vs-array-items/4)
- [apply arguments](http://jsperf.com/calling-function-vs-apply-with-arguments/5)
- [create object: (new Object() vs {})](http://jsperf.com/new-array-vs-literal/26)
- [create array: (new Array() vs [])](http://jsperf.com/new-array-vs-literal/24)
- [init object: (new Object() vs {})](http://jsperf.com/new-object/2/)
- [get value from object: (new Object() vs {})](http://jsperf.com/get-value-from-object-vs-hashtable): not stable, seems almost no difference.
- [flag operation](http://jsperf.com/flag-op): no difference, but !! and ! faster in IE 11
- [check reference nil vs check another flag](http://jsperf.com/nullable): check flag is faster
- [check property exists](http://jsperf.com/hasownproperty-vs-in-vs-undefined/12)

References
------------

 - [Let’s get those Javascript Arrays to work fast](http://gamealchemist.wordpress.com/2013/05/01/lets-get-those-javascript-arrays-to-work-fast/)
 - [Google Closure: How not to write JavaScript](http://www.sitepoint.com/google-closure-how-not-to-write-javascript/)
 - [node.js背后的引擎V8及优化技术](https://github.com/xiecc/game-server-development/blob/master/node/node.js-V8%E5%BC%95%E6%93%8E%E7%9B%B8%E5%85%B3%E7%9A%84%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96.md)
 - [Breaking the JavaScript Speed Limit with V8 (Youtube)](http://www.youtube.com/watch?v=UJPdhx5zTaw)
 - [Optimization killers](https://github.com/petkaantonov/bluebird/wiki/Optimization-killers)
 - [Writing Fast, Memory-Efficient JavaScript (EN_US)](http://www.smashingmagazine.com/2012/11/05/writing-fast-memory-efficient-javascript/)
 - [Writing Fast, Memory-Efficient JavaScript (ZH_CN)](http://www.alloyteam.com/2012/11/performance-writing-efficient-javascript/)
