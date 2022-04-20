# Arrays

irb(main):003:0> strings = ["tom", "tyler", "alex", "amy"]
=> ["tom", "tyler", "alex", "amy"]
irb(main):004:0> integers = [2, 3, 4, 5]
=> [2, 3, 4, 5]
irb(main):005:0> floats = [22.1, 24.2, 25.6, 27.7]
=> [22.1, 24.2, 25.6, 27.7]
irb(main):006:0> booleans = [true, false, true, false]
=> [true, false, true, false]

## This section illustrates array methods

irb(main):011:0> strings = ["tom", "tyler", "alex", "amy"]
=> ["tom", "tyler", "alex", "amy"]
irb(main):012:0> integers = [2, 3, 4, 5]
=> [2, 3, 4, 5]
irb(main):013:0> floats = [22.1, 24.2, 25.6, 27.7]
=> [22.1, 24.2, 25.6, 27.7]
irb(main):014:0> booleans = [true, false, true, false]
=> [true, false, true, false]

.pop will remove last element

irb(main):038:0> strings
=> ["tyler", "alex"]
irb(main):039:0> strings.pop
=> "alex"


.shift will remove first element

=> ["tina", "tyler", "alex", "tony"]
irb(main):036:0> strings.shift
=> "tina"


.unshift fills arrays with elements that will begin at the front

irb(main):035:0> strings.unshift "tina"
=> ["tina", "tyler", "alex", "tony"]

.push will push given element to the end of the array and returns the array itself with pushed elements

irb(main):034:0> strings.push "tony"
=> ["tyler", "alex", "tony"]

.length shows the user the number of elements in the arrays

irb(main):040:0> strings.length
=> 1


irb(main):018:0> strings.length
=> 2
irb(main):019:0> integers.pop
=> 5
irb(main):020:0> integers.shift
=> 2
irb(main):021:0> integers.unshift
=> [3, 4]
irb(main):022:0> integers.length
=> 2
irb(main):023:0> floats.pop
=> 27.7
irb(main):024:0> floats.shift
=> 22.1
irb(main):025:0> floats.unshift
=> [24.2, 25.6]
irb(main):026:0> floats.length
=> 2
irb(main):027:0> floats.push
=> [24.2, 25.6]
irb(main):028:0> booleans.pop
=> false
irb(main):029:0> booleans.shift
=> true
irb(main):030:0> booleans.unshift
=> [false, true]
irb(main):031:0> booleans.push
=> [false, true]
irb(main):032:0> booleans.length
=> 2


An index position is the position of the element in the array. Index positions always start count with 0 first.

animals = ["dog", "cat", "bird", "frog"]

* The index position for bird will be 2. 
