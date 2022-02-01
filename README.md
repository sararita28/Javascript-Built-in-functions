<h1>How to use this rep</h1>
This is a list of Javascript built-in functions/methods. 
Note: There may be other ones and some of the ones listed here might become deprecated so please do your own due diligence.


---



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
  <li><b>.Date():</b> returns today's date and time.</li>
  <li><b>.new Date() or .new Date(value/dateStr/dateObj/year,month,day,hr,min,sec,ms):</b> returns a date depending on the arguments provided.</li>
  <li><b>.getDate():</b> returns the day of the month for the specified date according to local time.</li>
  <li><b>.getDay():</b> returns the day of the week for the specified date according to local time.</li>
  <li><b>.getFullYear():</b> returns the year for the specified date according to local time.</li>
  <li><b>.getHours():</b> returns the hours for the specified date according to local time.</li>
  <li><b>.getMilliseconds():</b> returns the milliseconds for the specified date according to local time.</li>
  <li><b>.getMinutes():</b> returns the minutes for the specified date according to local time.</li>
  <li><b>.getMonth():</b> returns the month for the specified date according to local time.</li>
  <li><b>.getSeconds():</b> returns the seconds for the specified date according to local time.</li>
  <li><b>.getTime():</b> returns the number of milliseconds since the Unix Epoch.</li>
  <li><b>.getTimezoneOffset():</b> returns the difference in minutes between a UTC timezone and the local timezone.</li>
  <li><b>.getUTCDate():</b> returns the day of the month (from 1 to 31) in the specified date according to universal time.</li>
  <li><b>.getUTCDay():</b> returns the day of the week in the specified date according to universal time.</li>
  <li><b>.getUTCFullYear():</b> returns the year in the specified date according to universal time.</li>
  <li><b>.getUTCHours():</b> returns the hours in the specified date according to universal time.</li>
  <li><b>.getUTCMilliseconds():</b> returns the milliseconds portion of the time object's value according to universal time.</li>
  <li><b>.getUTCMinutes():</b> returns the minutes in the specified date according to universal time.</li>
  <li><b>.getUTCMonth():</b> returns the month of the specified date according to universal time, as a zero-based value (where zero indicates the first month of the year).</li>
  <li><b>.getUTCSeconds():</b> returns the seconds in the specified date according to universal time.</li> 
  <li><b>.setDate(dayValue):</b> changes the day of the month of a given date instance based on local time.</li>
  <li><b>.setFullYear(yearValue,monthValue,dateValue):</b> sets the full year for a specified date according to local time. Returns new timestamp.</li>
  <li><b>.setHours(hoursValue,minutesValue,secondsValue,msValue):</b> sets the hours for a specified date according to local time. Returns the number of milliseconds since Jan 1st 1970 UTC till the represented date.</li>
  <li><b>.setMilliseconds(millisecondsValue):</b> sets the milliseconds for a specified date according to local time.</li>
  <li><b>.setMinutes(minutesValue, secondsValue, msValue):</b> sets the minutes for a specified date according to local time.</li>
  <li><b>.setMonth(monthValue, dayValue):</b> sets the month for a specified date according to the currently set year.</li>
  <li><b>.setSeconds(secondsValue, msValue):</b> sets the seconds for a specified date according to local time.</li>
  <li><b>.setTime(timeValue):</b> sets the Date object to the time represented by a number of milliseconds since January 1, 1970, 00:00:00 UTC.</li>
  <li><b>.setUTCDate(dayValue):</b> changes the day of the month of a date based on UTC.</li>
  <li><b>.setUTCFullYear(yearValue, monthValue, dayValue):</b> sets the full year for a specified date according to universal time.</li>
  <li><b>.setUTCHours(hoursValue, minutesValue, secondsValue, msValue):</b> sets the hour for a specified date according to universal time, and returns the number of milliseconds since  January 1, 1970 00:00:00 UTC until the time represented by the updated Date instance.</li>
  <li><b>.setUTCMilliseconds(millisecondsValue):</b> sets the milliseconds for a specified date according to universal time.</li>
  <li><b>.setUTCMinutes(minutesValue, secondsValue, msValue):</b> sets the minutes for a specified date according to universal time.</li>
  <li><b>.setUTCMonth(monthValue, dayValue):</b> sets the month for a specified date according to universal time.</li>
  <li><b>.setUTCSeconds(secondsValue, msValue):</b> sets the seconds for a specified date according to universal time.</li>
  <li><b>.toDateString():</b> returns the date portion of a date object in the follong format (Example): Thu Jan 01 1970.</li>
  <li><b>.toLocaleDateString(locales,options):</b> returns a string with a language sensitive representation of the date portion of the date in the user's timezone.</li>
  <li><b>.toLocaleString(locales,options):</b> returns a string with language sensitive representation.</li>
  <li><b>.toLocaleTimeString(locales,options):</b> returns a string with language sensitive representation of the time portion of the date.</li>
  <li><b>.toString():</b> returns a string representing the specified date object.</li>
  <li><b>.toTimeString():</b> returns the time portion of a date object in human readable form in English.</li>
  <li><b>.toUTCString():</b> converts a date to a string using UTC timezone.</li>
  <li><b>.valueOf():</b> returns the primitive value of a date object.</li>
</ul>

---

<h2>Math</h2>
 <ul>
  <li><b>.abs(x):</b> returns the absolute value of a number.</li>
  <li><b>.acos(x):</b> returns the arccosine a.k.a inverse cosine (in radians) of a number.</li>
  <li><b>.asin(x):</b> returns the arcsine a.k.a inverse sine (in radians) of a number.</li>
  <li><b>.atan(x):</b> returns the arctangent (in radians) of a number. </li>
  <li><b>.atan2(y,x):</b> returns the angle in the plane (in radians) between the positive x-axis and the ray from (0,0) to the point (x,y) for Math.atan2(y,x)</li>
  <li><b>.ceil(x):</b> rounds a number up to the next largest integer.</li>
  <li><b>.cos(x):</b> returns the cosine of the specific angle (in radians).</li>
  <li><b>.exp(x):</b> returns e^x where x is the argument and e is the base of the natural log.</li>
  <li><b>.floor(x):</b> returns the larger integer <= a given number x.</li>
  <li><b>.log(x):</b> returns the natural logarithm (base e) of a number x.</li>
  <li><b>.max(value(s)):</b> returns the largest of the number value(s).</li>
  <li><b>.min(value(s)):</b> returns the lowest of the number value(s).</li>
  <li><b>.pow(base,exponent):</b> returns the base to the exponent power.</li>
  <li><b>.random():</b> returns a random number between 0 and 1.</li>
  <li><b>.round(x):</b> returns the value of a number x rounded to the nearest integer.</li>
  <li><b>.sin(x):</b> returns the sine of a number x.</li>
  <li><b>.sqrt(x):</b> returns the square root of a number x.</li>
  <li><b>.tan(x):</b> returns the tangent of a number x.</li>
</ul>

---

<h2>Regexp</h2>
<ul>
  <li><b>.exec(string):</b> executes a search for a match in a specified string. Returns a result array or null.</li>
  <li><b>.test(string):</b> executes a search for a match between a regexp and a specified string. Returns a boolean.</li>
  <li><b>.toString():</b> returns a string representing the regexp.</li>
</ul>
