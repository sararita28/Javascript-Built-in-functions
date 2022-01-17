This is a list of Javascript built-in functions/methods. 
Note: There may be other ones and some of the ones listed here might become deprecated so please do your own due diligence.

<h2>Number</h2>
<ul>
  <li><b>.constructor(): </b>returns the function that created this object's instance (by default: Number obj).</li>
  <li><b>.toExponential(): </b>displays number in exponential notation.</li>
  <li><b>.toFixed(d): </b>displays decimal number with specific number of digits (d) after the decimal</li>
  <li><b>.toLocaleString(x): </b>returns language-sensitive representation of number. 'x' determines the language whose formatting convention should be used.</li>
  <li><b>.toPrecision(d): </b>displays number with specified amount of digits (to right and left of decimal).</li>
  <li><b>.toString(base): </b>converts number to a string representation of the number object in a base between 2 to 36.</li>
  <li><b>.valueOf(): </b>returns primitive value of a number object (type becomes number, not object).</li>
</ul>
 
---

<h2>Boolean</h2>
<ul>
  <li><b>.toString():</b> returns string representing specified boolean object.</li>
  <li><b>.valueOf():</b> returns primitive value of specified boolean object.</li>
</ul>

---

<h2>String</h2>
<ul>
  <li><b>.charAt(index):</b> returns the character at a specified index.</li>
  <li><b>.charCodeAt(index):</b> returns the number representing unicode value of the character at specified index.</li>
  <li><b>.concat(string):</b> adds 2+ strings and returns a new single string.</li>
  <li><b>.indexOf(searchValue, fromIndex):</b> returns the index of the <em>first occurence</em> of searchValue starting at fromIndex. If 'fromIndex' is not specified or is lower than 0 the starting position will be index 0. If it's bigger than the length it'll return -1.</li>
  <li><b>.lastIndexOf(searchValue, fromIndex):</b> returns the index of the <em>last occurence</em> of searchValue starting at fromIndex.</li>
  <li><b>.localeCompare(x):</b> returns 0, 1 or -1 indicating whether a string x comes before, after or is in the same place as a given string.</li>
  <li><b>.length():</b> returns number of characters in a string.</li>
  <li><b>.match(regex):</b> returns all matches of a string against a regex.</li>
  <li><b>.replace(regex/substr,newsubstr/function):</b> returns a new string with some or all matches of a pattern replaced. If pattern is a string only the first occurence will be replaced</li>
  <li><b>.search(regex):</b> executes a search for a match between a regex and a string object. Returns the index of the first match.</li>
  <li><b>.valueOf():</b> returns the primitive value of a string object.</li>
  <li><b>.slice(x,y):</b> returns a section of a string as a new string. x:beginning index, y: end index.</li>
  <li><b>.split(''):</b> divides a string into substrings and returns an array. Can take a separator and a limit as arguments.</li>
  <li><b>.substring(x,y):</b> returns part of a string (based on given parameter(s)).</li>
  <li><b>.toLocaleLowerCase(x):</b> returns the lowercase string value depending on locale 'x'.</li>
  <li><b>.toLocaleUpperCase(x):</b> returns the uppercase string value depending on locale 'x'.</li>
  <li><b>.toLowerCase():</b> returns the lowercase string value.</li>
  <li><b>.toUpperCase():</b> returns the uppercase string value.</li>
  <li><b>.toString(x)</b> returns a string representing the specified object.</li>
</ul>
---

<h2>Array</h2>
 <ul>
  <li><b>.concat(arr):</b> merges 2+ arrays into new one.</li>
  <li><b>.every(callback):</b> tests whether all elements of an array pass the callback function's test.</li>
  <li><b>.filter(callback):</b> returns new array with all elements that pass the callback's test.</li>
  <li><b>.forEach(function):</b> executes a function for each element in the array.</li>
  <li><b>.indexOf(searchEl, fromIndex):</b> returns the 1st index at which a given element can be found. If 'fromIndex' is not specified, start index is 0.</li>
  <li><b>.join(separator):</b> returns string by joining all elements of an array (with separator).</li>
  <li><b>.lastIndexOf(x,fromIndex):</b> returns the last index at which given element x is found in an array starting at given index (or 0 if not specified).</li>
  <li><b>.map(function):</b> returns new array with result of calling the callback function on every element of the array.</li>
  <li><b>.pop():</b> removes the last element from the array and returns it.</li>
  <li><b>.push(element(s)):</b> adds element(s) to an array and returns its new length.</li>
  <li><b>.reduce(function, initialValue):</b> returns a single value after applying a callback on each element of the array, passing in the return value from the calculation on the preceding element. Optional: An initial value may be supplied the 1st time the callback runs.</li>
  <li><b>.reduceRight(function,initialValue):</b> same as the .reduce() method but starts from right the left.</li>
  <li><b>.reverse():</b> reverses an array. Last element becomes first etc...</li>
  <li><b>.shift():</b> removes the first element of an array and returns it.</li>
  <li><b>.slice(x,y):</b> returns a new array that represents a portion of the array. x:start, y:end (you can omit the 'y' and the indices can be negative).</li>
  <li><b>.some(function):</b> tests whether at least 1 element in the array passes the test of the function. Returns a boolean.</li>
  <li><b>.sort() or .sort(function):</b> sorts the elements of an array.</li>
  <li><b>.splice(start,deleteCount,item(s)):</b> adds, replaces, removes elements of an array. start:start index, deleteCount: number of elements to remove, item(s): element(s) to add.</li>
  <li><b>.toString():</b> returns a string representation of the array.</li>
  <li><b>.unshift(element(s)):</b> adds 1+ element(s) to the beginning of the array and returns its new length.</li>
</ul>
---

<h2>Date</h2>
 <ul>
  <li><b></b> </li>
  <li><b></b> </li>
</ul>
---

<h2>Math</h2>
 <ul>
  <li><b></b> </li>
  <li><b></b> </li>
</ul>
---

<h2>Regexp</h2>
<ul>
  <li><b></b> </li>
  <li><b></b> </li>
</ul>
