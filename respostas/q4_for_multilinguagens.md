PHP

<?php
$n = 100;
$sum = 0;
for ($i = 0, $j = 17; $i < $n; $i++, $j--) {
    $sum += $i * $j + 3;
}
echo $sum;
?>

----------------------------------------------------------------

Go (Golang)

package main
import "fmt"

func main() {
    n := 100
    sum := 0
    // Em Go, usa-se a atribuição paralela i, j = i+1, j-1
    for i, j := 0, 17; i < n; i, j = i+1, j-1 {
        sum += i * j + 3
    }
    fmt.Println(sum)
}

----------------------------------------------------------------

LUA

local n = 100
local i, j = 0, 17
local sum = 0

while i < n do
    sum = sum + (i * j + 3)
    i = i + 1
    j = j - 1
end

print(sum)

----------------------------------------------------------------

C++

#include <iostream>

int main() {
    int n = 100;
    long sum = 0;
    for (int i = 0, j = 17; i < n; i++, j--) {
        sum += i * j + 3;
    }
    std::cout << sum << std::endl;
    return 0;
}

----------------------------------------------------------------

C#

using System;

class Program {
    static void Main() {
        int n = 100;
        int sum = 0;
        for (int i = 0, j = 17; i < n; i++, j--) {
            sum += i * j + 3;
        }
        Console.WriteLine(sum);
    }
}
