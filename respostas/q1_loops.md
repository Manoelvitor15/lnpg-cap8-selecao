JAVA

int k = (j + 13) / 27;
while (k <= 10) {
    k++;
    i = 3 * k - 1;
}

--------------------------------------------------------------

PYTHON

k = (j + 13) // 27
while k <= 10:
    k += 1
    i = 3 * k - 1

--------------------------------------------------------------

HASKELL

let kInitial = (j + 13) `div` 27

let loop k = 
      if k > 10 
      then (k, i)
      else let nextK = k + 1
               nextI = 3 * nextK - 1
           in loop nextK

--------------------------------------------------------------

SWIFT

var k = (j + 13) / 27
while k <= 10 {
    k += 1
    let i = 3 * k - 1
}
