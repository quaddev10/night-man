<h1 align="center" style="font-weight: bold; background: #000; border-radius: 1.5rem; padding: 1.5rem 0;">
  <span style="font-weight: bold; color: #ff5733;">M</span>
  <span style="font-weight: bold; color: #ff8d33;">I</span>
  <span style="font-weight: bold; color: #ffbd33;">D</span>
  <span style="font-weight: bold; color: #dbff33;">N</span>
  <span style="font-weight: bold; color: #75ff33;">I</span>
  <span style="font-weight: bold; color: #33ff57;">G</span>
  <span style="font-weight: bold; color: #33ffa5;">H</span>
  <span style="font-weight: bold; color: #33fff5;">T</span>
  <span>&nbsp;</span>
  <span style="font-weight: bold; color: #339cff;">M</span>
  <span style="font-weight: bold; color: #5733ff;">A</span>
  <span style="font-weight: bold; color: #8d33ff;">N</span>
</h1>

<br/>

<p align="center" style="font-weight: bold; font-size: 1.1rem; font-style: italic; text-transform: uppercase; letter-spacing: 0.05rem; word-spacing: 0.1rem; line-height: 1.5; max-width: 800px; margin: 0 auto; padding: 0 1rem;">  
A DARKEST THEME EXISTS IN VSCODE, PERFECTLY SUITED FOR JAVASCRIPT, TYPESCRIPT, PYTHON, JAVA, C++, C#, GO, RUST, SWIFT, KOTLIN, PHP, RUBY, PERL, SHELL, SQL, LUA, R, HASKELL, SCALA, DART, ELIXIR, OBJECTIVE-C, F#, COBOL, AND MORE—DELIVERING AN IMMERSIVE, HIGH-CONTRAST EXPERIENCE FOR EVERY DEVELOPER.  
</p>

<div align="center">
  
  <img src="https://github.com/girish-kor/midnight-coder/blob/main/assets/theme-icon.gif" alt="Theme Icon">
  
</div>

<hr style="margin: 2rem 0;"/>

<h2 align="center" style="margin-bottom: 2rem;"> &lt; / Extension Matrix &gt; </h2>

<div align="center">

| CONTRAST RATIO     | ERGONOMICS    | COGNITIVE LOAD | COLOR SCIENCE      |
| ------------------ | ------------- | -------------- | ------------------ |
| WCAG AAA Certified | 8+ Hour Rated | Minimal-Impact | Quantum-Calibrated |

</div>

<hr style="margin: 2rem 0;"/>

<h2 align="center" style="margin-bottom: 2rem;"> &lt;/Activation Protocol&gt; </h2>

```sh
# Launch VS Code > Extensions (Ctrl+Shift+X)
# Search: "Midnight Coder"
# Install > Reload IDE
# Ctrl+K Ctrl+T > Select Theme
```

<hr style="margin: 2rem 0;"/>

<h2 align="center" style="margin-bottom: 2rem;"> &lt; / Engineering Parameters &gt; </h2>

```json
{
  "workbench.colorTheme": "Midnight Coder",
  "editor.fontSize": 15,
  "editor.fontFamily": "'Fira Code', 'JetBrains Mono', 'Cascadia Code', Consolas, monospace",
  "editor.fontLigatures": true,
  "editor.lineHeight": 1.7,
  "terminal.integrated.fontSize": 14,
  "editor.renderWhitespace": "boundary",
  "editor.cursorBlinking": "blink"
}
```

<hr style="margin: 2rem 0;"/>

<h2 align="center" style="margin-bottom: 2rem;"> &lt; / Theme Showcase &gt; </h2>

<details>
  <summary><strong>JavaScript</strong></summary>

```javascript
const fetchUser = async (id) => {
  try {
    const response = await fetch(`/api/users/${id}`);
    return response.json();
  } catch (error) {
    console.error("Fetch error:", error);
  }
};
```

</details>

<details>
  <summary><strong>TypeScript</strong></summary>

```typescript
interface User {
  id: number;
  name: string;
}

const getUser = async (id: number): Promise<User> => {
  const response = await fetch(`/api/users/${id}`);
  return response.json();
};
```

</details>

<details>
  <summary><strong>Python</strong></summary>

```python
with open('data.txt', 'r') as file:
    contents = file.read()

squares = [x**2 for x in range(10) if x % 2 == 0]
```

</details>

<details>
  <summary><strong>Java</strong></summary>

```java
public class Main {
    public static void main(String[] args) {
        Runnable task = () -> System.out.println("Quantum thread running");

        List<Integer> numbers = Arrays.asList(1, 2, 3);
        numbers.stream().map(n -> n * 2).forEach(System.out::println);
    }
}
```

</details>

<details>
  <summary><strong>C++</strong></summary>

```cpp
#include <iostream>
#include <vector>

int main() {
    std::vector<int> numbers = {1, 2, 3};
    for (int num : numbers) {
        std::cout << num * 2 << std::endl;
    }
    return 0;
}
```

</details>

<details>
  <summary><strong>C#</strong></summary>

```csharp
using System;
using System.Linq;

class Program {
    static void Main() {
        var numbers = new int[] {1, 2, 3};
        var doubled = numbers.Select(n => n * 2);
        foreach (var num in doubled) {
            Console.WriteLine(num);
        }
    }
}
```

</details>

<details>
  <summary><strong>Go</strong></summary>

```go
package main

import "fmt"

func main() {
    numbers := []int{1, 2, 3}
    for _, num := range numbers {
        fmt.Println(num * 2)
    }
}
```

</details>

<details>
  <summary><strong>Rust</strong></summary>

```rust
fn main() {
    let numbers = vec![1, 2, 3];
    let doubled: Vec<_> = numbers.iter().map(|n| n * 2).collect();
    println!("{:?}", doubled);
}
```

</details>

<details>
  <summary><strong>Swift</strong></summary>

```swift
let numbers = [1, 2, 3]
let doubled = numbers.map { $0 * 2 }
print(doubled)
```

</details>

<details>
  <summary><strong>Kotlin</strong></summary>

```kotlin
fun main() {
    val numbers = listOf(1, 2, 3)
    val doubled = numbers.map { it * 2 }
    println(doubled)
}
```

</details>

<details>
  <summary><strong>PHP</strong></summary>

```php
<?php
$numbers = [1, 2, 3];
$doubled = array_map(fn($n) => $n * 2, $numbers);
print_r($doubled);
?>
```

</details>

<details>
  <summary><strong>Ruby</strong></summary>

```ruby
numbers = [1, 2, 3]
doubled = numbers.map { |n| n * 2 }
puts doubled
```

</details>

<details>
  <summary><strong>Perl</strong></summary>

```perl
my @numbers = (1, 2, 3);
my @doubled = map { $_ * 2 } @numbers;
print "@doubled\n";
```

</details>

<details>
  <summary><strong>Shell</strong></summary>

```bash
#!/bin/bash
DEPLOY_ENV="production"
QUANTUM_SERVICE_VERSION="1.4.2"

docker build -t quantum-service:$QUANTUM_SERVICE_VERSION .
aws ecr push quantum-service:$QUANTUM_SERVICE_VERSION
```

</details>

<details>
  <summary><strong>SQL</strong></summary>

```sql
SELECT id, name, age * 2 AS double_age FROM users WHERE active = 1;
```

</details>

<details>
  <summary><strong>Lua</strong></summary>

```lua
numbers = {1, 2, 3}
for i, num in ipairs(numbers) do
    print(num * 2)
end
```

</details>

<details>
  <summary><strong>R</strong></summary>

```r
numbers <- c(1, 2, 3)
doubled <- numbers * 2
print(doubled)
```

</details>

<details>
  <summary><strong>Haskell</strong></summary>

```haskell
main = print (map (*2) [1, 2, 3])
```

</details>

<details>
  <summary><strong>Scala</strong></summary>

```scala
val numbers = List(1, 2, 3)
val doubled = numbers.map(_ * 2)
println(doubled)
```

</details>

<details>
  <summary><strong>Dart</strong></summary>

```dart
void main() {
  List<int> numbers = [1, 2, 3];
  List<int> doubled = numbers.map((n) => n * 2).toList();
  print(doubled);
}
```

</details>

<details>
  <summary><strong>Elixir</strong></summary>

```elixir
numbers = [1, 2, 3]
doubled = Enum.map(numbers, &(&1 * 2))
IO.inspect(doubled)
```

</details>

<details>
  <summary><strong>Objective-C</strong></summary>

```objective-c
NSArray *numbers = @[@1, @2, @3];
NSArray *doubled = [numbers valueForKeyPath:@"@unionOfObjects.self.intValue * 2"];
NSLog(@"%@", doubled);
```

</details>

<details>
  <summary><strong>F#</strong></summary>

```fsharp
let numbers = [1; 2; 3]
let doubled = List.map ((*) 2) numbers
printfn "%A" doubled
```

</details>

<details>
  <summary><strong>COBOL</strong></summary>

```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. DoubleNumbers.
DATA DIVISION.
WORKING-STORAGE SECTION.
    01 NUMBERS PIC 9(2) OCCURS 3 VALUE (1 2 3).
PROCEDURE DIVISION.
    PERFORM VARYING I FROM 1 BY 1 UNTIL I > 3
        DISPLAY NUMBERS(I) * 2
    END-PERFORM.
STOP RUN.
```

</details>

<hr style="margin: 2rem 0;"/>

<div align="center" style="background: #000; border-radius: 1.5rem; padding: 1.5rem; margin-top: 2rem;">
<h3 style="color: #fff; margin-bottom: 1.5rem;">&lt; / PUBLISHERS &gt;</h3>

<p align="center">
  <a href="https://github.com/girish-kor" style="text-decoration: none; margin: 0 10px;">
    <img src="https://img.shields.io/badge/GitHub-girish--kor-%237A06F7?style=for-the-badge&logo=github" alt="GitHub" />
  </a>
  
  <a href="mailto:girishkor05@gmail.com" style="text-decoration: none; margin: 0 10px;">
    <img src="https://img.shields.io/badge/Email-girishkor05%40gmail.com-%23C70039?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
  
  <a href="LICENSE" style="text-decoration: none; margin: 0 10px;">
    <img src="https://img.shields.io/badge/License-MIT-%2300C853?style=for-the-badge" alt="License" />
  </a>
</p>
</div>
#   n i g h t - m a n  
 