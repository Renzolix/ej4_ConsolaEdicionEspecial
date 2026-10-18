# Ejercicio 4: HardwareGeek y ConsolaEdicionEspecial

## Explicación Lógica
1. **Modificador `protected`:** Permite que las subclases lean y modifiquen directamente el atributo `precioCosto` sin necesidad de pasar por métodos intermediarios.
2. **Modificador `private`:** Mantiene `numeroSerie` completamente oculto fuera de `HardwareGeek`. La subclase sólo puede leerlo invocando la interfaz pública `getNumeroSerie()`.