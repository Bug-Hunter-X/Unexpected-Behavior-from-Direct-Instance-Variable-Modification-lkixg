# Ruby Bug: Direct Instance Variable Modification

This example demonstrates a common, yet subtle, error in Ruby: directly modifying instance variables using `instance_variable_set` or `instance_variable_get`. While technically possible, this practice undermines the benefits of encapsulation and can make code harder to maintain and debug.