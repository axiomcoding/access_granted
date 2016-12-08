# Access Granted
A **global variable** is any variable in Ruby with a leading `$` symbol. It is called a global variable because it has a greater scope than a   **local variable**, which we have been using thus far. There are several global variable pre-define in `access_granted.rb`.  

For example:  
```ruby
$nums = [1, 2, 3]

def first_num
  $nums[0]
end

first_num
#=> 1
``` 
- Although the `$nums` array was defined outside of the scope of the `first_num` method, the program still had access to it because of its *global* scope  

When writing your array methods, refer to the global variable names and be sure to include the `$` in the variable name when calling it (Note: Do not alter the arrays in the `access_granted.rb` file.)  