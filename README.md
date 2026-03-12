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

