# Table of Contents
- [Arrays](#arrays)

    - [Add/remove items](#addremove-items)
    - [Search among elements](#search-among-elements)
    - [Iterate over the elements](#itterate-over-elements)
    - [Transform the array](#transform-the-array)
    
# Arrays

## Add/remove items

|   |   |
|---|---|
|arr.push(...items)   | adds items to the end,   |
|arr.shift()   |extracts an item from the beginning,   |
|arr.pop()   |extracts an item from the end,   |
|arr.unshift(...items )|adds items to the beginning.|

|   |   |
|---|---|
|splice(pos, deleteCount, ...items)   | at index pos deletes deleteCount elements and inserts items|
|slice(start, end)|creates a new array, copies elements from index start till end (not inclusive) into it.|
|concat(...items)|returns a new array: copies all members of the current one and adds items to it. If any of items is an array, then its elements are taken.|

## Search among elements
|   |   |
|---|---|
|indexOf/lastIndexOf(item, pos)|look for item starting from position pos, return the index or -1 if not found.|
|includes(value)|returns true if the array has value, otherwise false.|
|find/filter(func)|filter elements through the function, return first/all values that make it return true.|
|findIndex|is like find, but returns the index instead of a value.|

## Itterate over elements
|   |   |
|---|---|
|forEach(func)|calls func for every element, does not return anything.

## Transform the array
|   |   |
|---|---|
|map(func)|creates a new array from results of calling func for every element.|
|sort(func)|sorts the array in-place, then returns it.|
|reverse()|reverses the array in-place, then returns it.|
|split/join|convert a string to array and back.|
|reduce/reduceRight(func, initial)|calculate a single value over the array by calling func for each element and passing an intermediate result between the calls.|

Please note that methods sort, reverse and splice modify the array itself.