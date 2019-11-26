# file
A high-level file library for Wu

## Example

```fsharp
# example.wu

import file { File }

file := File from("example.wu")
print("file output:\n")
print(file read())
```