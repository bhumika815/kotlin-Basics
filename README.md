import java.util.Scanner
fun main ( args: Array<String>){
    val sc = Scanner (System.`in`)
    print("enter a number:")
    val number = sc. nextInt()
    if (number % 2==0) {
        println("$number is even")
    }else{
        println("$number is odd")
    }
}
