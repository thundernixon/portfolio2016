---
layout: post
title:  "Learning about Javascript"
date:   2016-08-02 20:33:32 -0400
categories: javascript
---

# It was time for an update.

```
var checkAttendanceFunc = function(nameArr) {
	var resultArr = [];
	for(var i = 0; i < nameArr.length; i++) {
		(function(index){
			resultArr.push(function(){
				console.log('Is', nameArr[index], 'present?')})
		})(i);
	}
	return resultArr;
};

var attendance = checkAttendanceFunc(["dan", "joseph", "alice", "rich" ]);

console.log(attendance);

for(var i = 0; i <attendance.length; i++) {
	attendance[i]();
}
```
