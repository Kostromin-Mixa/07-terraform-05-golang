# 07-terraform-05-golang my my my

Задача 1.
package main
import "fmt"
func add(output, f int,)  int {return output * f}
var f = 3.2808; 
func main() {
    fmt.Print("Enter a number: ")
    var input float64
    fmt.Scanf("%f", &input)
    output := input * 2
    fmt.Println(output)    
    fmt.Println("В", output, "метрах", f*output, "футов")
}

Задача 2.
package main 
import "fmt"
func main() {
x := []int{48,96,86,68,57,82,63,70,37,34,83,27,19,97,9,17,}
min := x[0]
for _, a := range x {
if (a < min) {
min = a  
fmt.Println(min)
}}}

Задача 3.
package main
import "fmt"
func main() {
sum := 0
for i:=0; i<=96; i++ {
if (i%3==0){
sum += 3
fmt.Println(sum)
}
}	
}


