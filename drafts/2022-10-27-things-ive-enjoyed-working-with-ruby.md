Ruby has number of convenience functions that I have grown to appreciate. For example when checking the length if the length of a string is zero, in most programming languages the most common thing is to do this: mystring.length == 0. In ruby, you can do: mystring.length.zero?. Another cool one, is when checking if a value is less than zero, instead of myvalue < 0 you can do myvalue.negative?

RSpec observation matchers, the ability, in one assertion, to observe the change of state from one form to another

Need to split an array into chunks? Use ***Enumarable.each_slice(<chunk_size>)***. How cool is that...