---
layout: home
title: Constant
---
## Understanding `const` in Different Programming Languages

The `const` keyword is a common feature in many programming languages. It is used to declare variables or values that cannot be modified once assigned. In this article, we will explore how `const` is written and utilized in various programming languages.

## JavaScript

In JavaScript, `const` is used to declare a read-only reference to a value that cannot be reassigned. Here's an example:

```javascript
const PI = 3.14159;
```

In the above code snippet, the variable `PI` is assigned the value `3.14159`, and it cannot be changed later in the program. Attempting to reassign a value to `PI` will result in an error.

## C++

In C++, `const` is used to define constants that cannot be modified during runtime. Here's an example:

```cpp
const int MAX_VALUE = 100;
```

The `const` keyword precedes the variable declaration, and the variable is assigned the value `100`. Similar to JavaScript, attempting to modify the value of `MAX_VALUE` will result in a compilation error.

## Python

In Python, the `const` keyword is not explicitly available. However, the convention is to use uppercase variable names to indicate a constant value. Although the value can be modified, it is considered a best practice not to do so. Here's an example:

```python
MAX_CONNECTIONS = 5
```

While it is technically possible to change the value of `MAX_CONNECTIONS`, it is generally discouraged by developers.

## Java

In Java, the `final` keyword is used to create constants. The `final` keyword makes the variable unmodifiable once assigned. Here's an example:

```java
final double PI = 3.14159;
```

The `final` keyword precedes the variable declaration, and the variable `PI` is assigned the value `3.14159`. Trying to reassign a new value to `PI` will result in a compilation error.

## Ruby

In Ruby, constants are declared by capitalizing the variable name. Although constants can be modified, a warning will be issued if an attempt is made to change their value. Here's an example:

```ruby
MAX_ATTEMPTS = 3
```

Ruby follows a convention of not modifying constants, similar to Python.

## C#

In C#, `const` is used to define compile-time constants that cannot be modified. Here's an example:

```csharp
const int MAX_VALUE = 100;
```

The `const` keyword precedes the variable declaration, and the variable is assigned the value `100`. Attempting to modify the value of `MAX_VALUE` will result in a compilation error.

## PHP

In PHP, `const` is used to declare class constants. Here's an example:

```php
class Math {
    const PI = 3.14159;
}
```

In the above code snippet, the constant `PI` is defined within the `Math` class. It can be accessed using the syntax `Math::PI`.

## Go

In Go, `const` is used to declare constants. Here's an example:

```go
const MaxConnections = 10
```

The `const` keyword precedes the constant declaration, and the constant `MaxConnections` is assigned the value `10`. Constants in Go cannot be modified.

## GDScript

In GDScript, constants are typically declared using uppercase variable names. Here's an example:

```gdscript
const MAX_VALUE = 100
const MIN_VALUE := 0
```

You can use colon or equal sign to declare constants, both are valid. However the colon is preferred since it implies type inference.


## Swift

In Swift, `let` is used to declare constants. Here's an example:

```swift
let numberOfDays = 7
```

The `let` keyword is used

 to declare a constant named `numberOfDays` with a value of `7`. Once assigned, the value cannot be changed.

## Rust

In Rust, `const` is used to declare compile-time constants. Here's an example:

```rust
const MAX_VALUE: i32 = 100;
```

The `const` keyword is followed by the type and the value of the constant `MAX_VALUE`. Trying to modify the value of `MAX_VALUE` will result in a compilation error.

## TypeScript

In TypeScript, `const` is used to declare immutable bindings. Here's an example:

```typescript
const MAX_SIZE = 1024;
```

The `const` keyword is used to define a constant named `MAX_SIZE` with a value of `1024`. It cannot be reassigned.

## Kotlin

In Kotlin, `val` is used to declare read-only variables. Here's an example:

```kotlin
val PI = 3.14159
```

The `val` keyword precedes the variable declaration, and the variable `PI` is assigned the value `3.14159`. It cannot be reassigned.

## Perl

In Perl, `use constant` is used to declare constants. Here's an example:

```perl
use constant MAX_ATTEMPTS => 3;
```

The `use constant` statement declares a constant named `MAX_ATTEMPTS` with a value of `3`. It cannot be modified.

## Lua

In Lua, constants are typically created using uppercase variable names. Although the value can be modified, it is considered a convention not to do so. Here's an example:

```lua
MAX_VALUE = 100
```

While it is technically possible to change the value of `MAX_VALUE`, it is generally discouraged by developers.

## R

In R, constants are typically declared using the `<-` assignment operator. Here's an example:

```r
PI <- 3.14159
```

The `<-` operator assigns the value `3.14159` to the constant `PI`. It cannot be reassigned.

## Swift

In Swift, `let` is used to declare constants. Here's an example:

```swift
let numberOfDays = 7
```

The `let` keyword is used to declare a constant named `numberOfDays` with a value of `7`. Once assigned, the value cannot be changed.

## Haskell

In Haskell, constants are defined using the `let` keyword. Here's an example:

```haskell
let maxAttempts = 3
```

The `let` keyword is used to define a constant named `maxAttempts` with a value of `3`. It cannot be modified.

## Perl 6

In Perl 6, constants can be created using the `constant` keyword. Here's an example:

```perl
constant MAX_ATTEMPTS = 3;
```

The `constant` keyword is used to declare a constant named `MAX_ATTEMPTS` with a value of `3`. It cannot be modified.

## Shell Scripting

In shell scripting, variables are typically assigned using the `=` operator, and the convention is to use uppercase names for constants. Here's an example:

```bash
MAX_RETRIES=3
```

While the value of `MAX_RETRIES` can be modified, it is considered a convention not to do so.

## MATLAB

In MATLAB, constants are typically declared using the `persistent` keyword. Here's an example:

```matlab
persistent GRAVITY;
GRAVITY = 9.81;
```

The `persistent` keyword is used to declare a constant named `GRAVITY` with a value of `9.81`. It cannot be modified once assigned.

## PowerShell

In PowerShell, constants are created using the `Set-Variable` cmdlet with the `-Option` parameter set to `Constant`. Here's an example:

```powershell
Set-Variable -Name PI -Value 3.14159 -Option Constant
```

The `Set-Variable` cmdlet creates a constant named `PI` with a value of `3.14159`. It cannot be modified.

## Julia

In Julia, constants can be declared using the `const` keyword. Here's an example:

```julia
const MAX_VALUE = 100
```

## Elixir

In Elixir, constants are created using the `defmodule` and `defconst` macros. Here's an example:

```elixir
defmodule Math do
  defconst PI, 3.14159
end
```

The `defmodule` macro defines a module named `Math`, and the `defconst` macro is used to declare a constant named `PI` with a value of `3.14159`. It cannot be modified.

## Erlang

In Erlang, constants are typically defined using uppercase variable names. Although the value can be modified, it is considered a convention not to do so. Here's an example:

```erlang
-define(MAX_VALUE, 100).
```

The `-define` directive is used to define a constant named `MAX_VALUE` with a value of `100`. While it is technically possible to change the value of `MAX_VALUE`, it is generally discouraged by developers.

## Groovy

In Groovy, `final` is used to declare constants. Here's an example:

```groovy
final int MAX_VALUE = 100
```

The `final` keyword precedes the variable declaration, and the variable is assigned the value `100`. Attempting to modify the value of `MAX_VALUE` will result in an error.

## Conclusion

The `const` keyword or similar constructs in different programming languages allow developers to define variables or values that should not be modified. While the exact syntax may differ, the purpose remains the same. By using `const`, you can make your code more readable, maintainable, and less prone to bugs caused by unintentional modifications.

Remember to choose the appropriate approach for creating constants in the programming language you are working with and follow the best practices recommended by the language community.