@startuml

class Animal{
    -nombre: String
    -origen: String
    -color: String
    -sonido(String): void
    -comer(): void
}

class AnimalAcuatico extends Animal{
    -numeroAletas: int
    +nadar(): void
    +comer(): void
}

class AnimalTerrestre extends Animal{
    -numeroPatas: int
    +correr(): void
    +comer(): void
}

class AnimalAereo extends Animal{
    -numeroAlas: int
    +volar(): void
    +comer(): void
}

class Ballena extends AnimalAcuatico{
    -largo: int
    +pelearConPinocho(): void
}

class Perro extends AnimalTerrestre{
    -colorCollar: String
    +hacerTrucos(): void
}

class Pajaro extends AnimalAereo{
    -tipoPico: String
    +recolectarRamas(): void
}

@enduml
