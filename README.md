# edabit
[31. Boolean to String Conversion](https://edabit.com/challenge/KSTkFSnaYBJdo6PHx)

```js
function boolToString(flag) {
	if(flag == true){
		return "true"
	}else{
		return "false"
	}
}
```

[32. Using Arrow Functions](https://edabit.com/challenge/QkvDge63crdGnMfvM)


```js
function arrowFunc(parameters){
	if(parameters == true){
		return true
	}
	return parameters
}
```

[33. Frames Per Second](https://edabit.com/challenge/d9suvbchE2bnHNQuK)

```js
function frames(minutes, fps) {
	return minutes * 60 * fps
}
```

[34. Miserable Parody of a Calculator](https://edabit.com/challenge/fh9i7k936rvfjnCYR)

```js

```

[35. Buggy Code (Part 4)](https://edabit.com/challenge/4SmqXvQtL6qRgzfha)

```js
function greeting(name) {
  if(name == "Mubashir") {
    return "Hello, my Love!";
  }
	return "Hello, " + name + "!";
}
```

[36. Two Makes Ten](https://edabit.com/challenge/5erCDJ8eJDrXkmwTK)

```js
function makesTen(a, b) {
	if (a == 10 || b == 10 || a + b == 10){
		return true
	}else {
		return false
	}
}
```

[37. Let's Fuel Up!](https://edabit.com/challenge/YMWDcSuYwYvve3HZj)

```js

```

[38. Buggy Code (Part 2)](https://edabit.com/challenge/uE9AJ4sSrrpSASMpu)

```js
function maxNum(n1,n2) {
	if (n1<n2) {
	  return n2
	}
  else {
	return n1
  }
}
```


[39. Pair Management](https://edabit.com/challenge/BFnsRqe8PFvEwcRNt)

```js
function makePair(num1, num2) {
	return [num1,num2]
}
```

[40. Compare Strings by Count of Characters](https://edabit.com/challenge/yHGowWucg3k2kJdZ4)

```js
function comp(str1, str2) {
	if(str1.length == str2.length ){
		return true
	}else{
		return false
	}
}
```

[41. Is the String Empty?](https://edabit.com/challenge/EzbfiquDoAc2Zc9FL)

```js
function isEmpty(s) {
	if(s.length == ""){
		return true
	}else{
		return false
	}
}
```

[42. Check if an Integer is Divisible By Five](https://edabit.com/challenge/iBQYbSHZGhpktLRdn)

```js
function divisibleByFive(n) {
	if(n % 5 == 0){
		return true
	}else{
		return false
	}
}
```


[43. Multiple of 100](https://edabit.com/challenge/qMr6wYGr6NaXAPQGF)

```js
function divisible(num) {
	if (num % 100 == 0){
		return true
	}else {
		return false
	}
}
```

[44. Recursion: Length of a String](https://edabit.com/challenge/4MSbtYFBiRtxHEkY8)

```js
function length(str) {
	return str.length
}
```


[45. Divides Evenly](https://edabit.com/challenge/JfB9mWmbwYHbupxCB)

```js

```

[46. Return a String as an Integer](https://edabit.com/challenge/rGsgEswWuW339yNxY)

```js
function stringInt(str) {
	return (+str)
}
```

[47. Area of a Rectangle](https://edabit.com/challenge/g6b9HqkXqWu6GpfTo)

```js
function area(h, w) {
	if(h <= 0 || w <= 0){
		return -1
	}else{
		return h * w
	}
}
```

[48. Minimal I: If Boolean Then Boolean](https://edabit.com/challenge/nEdLGbAZQ5LaiumP6)

```js
function isEven(n) {
	if (n % 2 === 0) {
		return true
	}
	else if (n % 2 === 1) {
		return false
	}
}
```

[49. Concatenate First and Last Name into One String](https://edabit.com/challenge/RQwdZmtrW8mCnuCMN)

```js
function concatName(firstName, lastName) {
	return lastName  + ', ' +firstName
}
```

[50. Buggy Code](https://edabit.com/challenge/r2MbSxquAGPnDkjQx)

```js
function has_bugs(buggycode) {
	if (buggycode == true) {
		return "sad days"
	} else if (buggycode == false){
		return "it's a good day"
	}
}
```