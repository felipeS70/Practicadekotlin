# Practicadekotlin
## Parte_1 Variables y salidas 

fun main() {
    // 1. Nombre
    val nombre = "Felipe"
    println("Hola soy $nombre")

    // 2. Edad
    val edad = 24
    println("Tengo $edad años")

    // 3. Suma
    val a = 10
    val b = 5
    println("La suma es: ${a + b}")

    // 4. Curso
    val curso = "Aplicaciones moviles"
    println("Estoy llevando el curso de $curso")

    // 5. Comida 
    val comida = "Ceviche"
    println("Mi comida favorita es $comida")

    // 6. Videojuego 
    val videojuego = "Mario car"
    println("Mi videojuego favorito es $videojuego")
}
<img width="512" height="150" alt="image" src="https://github.com/user-attachments/assets/98d32da9-3aa7-4c3b-9754-08e3025405b9" />

## Parte_2 Condicionales If

fun main(){
    // 1. Mayor de edad
    val edad = 24
    if (edad >= 18) {
        println("Eres mayor de edad")
    } else { 
        println("Eres menor de edad")
    }

    // 2. Nota aprobado/desaprobado
    val nota = 15
    if (nota >= 11) {
        println("Aprobado")
    } else {
        println("Desaprobado")
    }

    // 3. Número positivo
    val numero = 7
    if (numero >= 0) {
        println("El número es positivo")
    } else {
        println("El número es negativo")
    }

    // 4. Par o impar
    val n = 10
    if (n % 2 == 0) {
        println("Es par")
    } else {
        println("Es impar")
    }

    // 5. Temperatura
    val temperatura = 25
    if (temperatura < 18) {
        println("Hace frío")
    } else {
        println("Hace calor")
    }
}

<img width="250" height="124" alt="image" src="https://github.com/user-attachments/assets/37fdfbb7-ee86-4c27-a5d5-d164f0929af5" />

## Parte 3 Condicional WHEN

fun main() {
    // 1. Día de la semana
    val dia = 3
    when (dia) {
        1 -> println("Lunes")
        2 -> println("Martes")
        3 -> println("Miércoles")
        4 -> println("Jueves")
        5 -> println("Viernes")
        6 -> println("Sábado")
        7 -> println("Domingo")
    }

    // 2. Piedra, Papel, Tijera
    val jugada = 1
    when (jugada) {
        1 -> println("Piedra")
        2 -> println("Papel")
        3 -> println("Tijera")
    }

    // 3. Mes del año
    val mes = 5
    when (mes) {
        1 -> println("Enero")
        2 -> println("Febrero")
        3 -> println("Marzo")
        4 -> println("Abril")
        5 -> println("Mayo")
        6 -> println("Junio")
        7 -> println("Julio")
        8 -> println("Agosto")
        9 -> println("Setiembre")
        10 -> println("Octubre")
        11 -> println("Noviembre ")
        12 -> println("Diciembre")
    }

    // 4. Nota por letras
  val nota = 16 // Variable numérica

    when (nota) {
        in 18..20 -> println("AD")
        in 14..17 -> println("A")
        in 11..13 -> println("B")
        in 0..10  -> println("C")
        else -> println("Nota no válida") 
    }

}

<img width="139" height="91" alt="image" src="https://github.com/user-attachments/assets/946bbdbe-c5c3-4fd3-a241-3ca6442648e1" />

fun main() {
    // 1. Números del 1 al 10
    for (i in 1..10) {
        println(i)
    }

    // 2. Nombre 5 veces
    for (i in 1..5) {
        println("Felipe")
    }

    // 3. Números del 1 al 20, indicando pares
    for (i in 1..20) {
        if (i % 2 == 0) {
            println("Numero par: $i")
        } else {
            println(i)
        }
    }

    // 4. Sumar del 1 al 10
    var suma = 0
    for (i in 1..10) {
        suma += i
    }
    println("El resultado final de la suma es: $suma")
}

<img width="65" height="196" alt="image" src="https://github.com/user-attachments/assets/0159efa8-d582-4505-9f61-bd07c319d37e" />
<img width="80" height="94" alt="image" src="https://github.com/user-attachments/assets/0a5f5362-f25a-47a9-baf7-d144729bd3e7" />
<img width="140" height="186" alt="image" src="https://github.com/user-attachments/assets/04092a04-2c3f-4528-9c58-f7c5a7a29f23" />
<img width="326" height="202" alt="image" src="https://github.com/user-attachments/assets/916ae4ea-b2df-432d-b84e-62e8c79bea3c" />

## Parte_5 Problemas combinados 
fun main() {
    // 5. Determinar positivo, negativo o cero
    val num = -5
    if (num > 0) {
        println("positivo")
    } else if (num < 0) {
        println("negativo")
    } else {
        println("cero")
    }

    // 6. Tabla de multiplicar
    val tablaDel = 7
    for (i in 1..12) {
        println("$tablaDel x $i = ${tablaDel * i}")
    }

    // 7. Nivel del estudiante (usando rangos en when)
    val notaFinal = 15
    when (notaFinal) {
        in 18..20 -> println("Excelente")
        in 14..17 -> println("Bueno")
        in 11..13 -> println("Regular")
        in 0..10 -> println("Reprobado")
    }
}
<img width="131" height="186" alt="image" src="https://github.com/user-attachments/assets/063bd430-0811-4a5d-a4e7-e688011d6bf1" />
<img width="131" height="83" alt="image" src="https://github.com/user-attachments/assets/93c0e4b3-47ae-44b2-a6b1-fa75f20c7d07" />



