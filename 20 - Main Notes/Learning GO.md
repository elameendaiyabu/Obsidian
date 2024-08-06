###  Tags: [[go]]
---
- Folders are called modules and files inside modules are called packages.
- therefore, modules is just a collection of packages.
- var is used to declare variables
- syntax is " var     variableName   variableType"
- variables can be assigned like " variableName := 1"
- const can also be used
- if functions return a value, you need to specify the return type, "func addSum (a int, b int) int{}"

## arrays, loops, maps, & slices
- declaring arrays" var arrayName [arrayLength]arrayValueTypes"
- eg = var arrInt [3]int32, here arrInt is an array of int32 values of length 3
- can also be declared like so, arrInt := [3]int32{1,2,3}
- or arrInt := [...]int32{1,2,3}
- 