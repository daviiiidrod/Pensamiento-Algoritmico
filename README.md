# Pensamiento-Algoritmico
Algoritmo Sistema Descuentos
Inicio
    Escribir "Ingrese el monto de la compra:"
    Leer monto
    Si monto > 1000 Entonces
        descuento <- monto * 0.20
    Sino Si monto >= 500 Entonces
        descuento <- monto * 0.10
    Sino
        descuento <- 0
    FinSi
    montoFinal <- monto - descuento
    Escribir "El monto final a pagar es: $", montoFinal
Fin
