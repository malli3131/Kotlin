'''

data class Person(val name:String, val age:Int)

fun main(args: Array<String>) {
    welcome()
    val sum = add(10, 20)
    println("Sum is $sum")
    val persons = listOf(Person("Naga", 30), Person("Hari", 33))
    val oldest = persons.maxBy{it.age ?: 0 }
    println("The oldest one: $oldest")
}

fun welcome(){
    println("Welcome the Kotlin Wolrd!")
}

fun add(a:Int, b:Int) : Int {
   return (a + b)
}
'''
