## Day 5 Questions

1. What is a Hash, and how is it different from an Array in Ruby?

In a hash you can use anything to call indexed information. In an array you can only use numbers to call indexed values.

1. In the space below, create a Hash stored to a variable named `pet_store`.  This hash should hold an inventory of items and the number of that item that you might find at a pet store.

1. given the following `states = {"CO" => "Colorado", "IA" => "Iowa", "OK" => "Oklahoma"}`, how would you access the value `"Iowa"`?

puts states[IA]

1. With the same hash above, how would we get all the keys?  All the values?

states.keys - this will return all keys
states.values - this will return all values


1. What is another example of when we might use a hash?  In this case, why is a hash better than an array?

We could use a hash for something like storing makes and cars(key)
and models(value)

Based on what I have read, hashes are faster than arrays.
With arrays you have to search through more values unless
the array is sorted to get your target.
With hashes, 'the location is generated based on the value'

1. What questions do you still have about hashes?
