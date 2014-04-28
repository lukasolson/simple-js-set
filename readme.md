# Simple JS Set

Simple JS Set is a JavaScript implementation of `Set` that can be used to house any type of JavaScript object. It is a simple set with the following API:

#### `new Set(hashFunction)`
Constructor. Instantiate a new set with the given `hashFunction` (defaults to `JSON.stringify`).

#### `add(item)`
Add an item to the set.

#### `remove(item)`
Remove an item from the set.

#### `contains(item)`
Return whether or not the item is contained in the set.

#### `size()`
Return the number of unique items in the set.

#### `each(function(item), thisObj)`
Execute a function with each item in the set in context of `thisObj`.
