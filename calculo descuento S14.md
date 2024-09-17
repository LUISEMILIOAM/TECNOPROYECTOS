# Definir la función calcular_descuento
def calcular_descuento(monto_total, porcentaje_descuento=10):
    # Calcular el descuento
    descuento = monto_total * (porcentaje_descuento / 100)
    # Retornar el descuento
    return descuento

# Llamar a la función con solo el monto total (usando el valor por defecto para el porcentaje)
monto1 = 150.0
descuento1 = calcular_descuento(monto1)
monto_final1 = monto1 - descuento1

# Llamar a la función con el monto total y un porcentaje de descuento diferente
monto2 = 200.0
porcentaje_descuento2 = 15
descuento2 = calcular_descuento(monto2, porcentaje_descuento2)
monto_final2 = monto2 - descuento2

# Mostrar los resultados
(monto1, descuento1, monto_final1), (monto2, porcentaje_descuento2, descuento2, monto_final2)
