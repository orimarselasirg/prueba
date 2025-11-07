# 🧩 Ejercicios de Control de Flujo en Python

A continuación tienes los ejercicios modificados para que tengan un poco más de dificultad, incluyendo más condiciones, validaciones o cálculos extra.

---

## 1. Panadería de Don Pancho — Descuentos por cantidades

La panadería de Don Pancho vende pan a **$300 cada uno**.

**Reglas:**
- Si compra más de 20 panes → 10% descuento  
- Si compra más de 50 panes → 20% descuento  
- Si ingresa una cantidad negativa → mostrar `"Cantidad inválida"`  

**Objetivo:**  
Calcular y mostrar el total a pagar.

---

## 2. Cine “La Estrella” — Tarifas por edad

Pedir la edad del cliente:

| Edad | Precio |
|------|---------|
| < 5 años | Entrada gratis |
| 5 a 11 | $5.000 |
| 12 a 59 | $8.000 |
| ≥ 60 | $4.000 (descuento adulto mayor) |

**Condiciones adicionales:**
- Si la edad es negativa, mostrar un error.

**Objetivo:**  
Mostrar el precio de la entrada.

---

## 3. Gimnasio “Solo Leveling Fit” — Motivación + Bono

Pedir cuántos días entrenó esta semana.

**Reglas:**
- ≥ 4 días → `"¡Excelente disciplina!"` + gana **1 punto de energía**  
- 2 o 3 días → `"Bien, pero puedes dar más"`  
- 0 o 1 día → `"No aflojes, tú puedes mejorar"`

**Objetivo:**  
Mostrar mensaje y si aplica, los puntos ganados.

---

## 4. Heladería “Frosty” — Sabor y topping

**Sabores y precios:**
- chocolate → $4.000  
- vainilla → $3.500  

**Topping (opcional):**  
- cuesta $1.000

**Validaciones:**
- Si el usuario ingresa un sabor que no existe → `"Sabor no disponible"`  
- Si el sabor es válido, preguntar si quiere topping y calcular total.

---

## 5. Librería “El Saber” — Descuento estudiante + cupón

Cada libro cuesta **$25.000**.

**Reglas:**
- Si es estudiante → 15% de descuento  
- Si además tiene cupón `"LIBRO10"` → 10% adicional sobre el valor ya descontado  
- Si no es estudiante, el cupón no aplica.  
- Si ingresa cupón incorrecto, ignorarlo.

**Objetivo:**  
Mostrar total final a pagar.

---

## 6. Parqueadero “RapidCar” — Tarifa escalonada

**Tarifas:**
- 0 a 5 horas: $2.000 por hora  
- 5 horas → $2.000 x hora + multa fija de $5.000  

**Validaciones:**
- No permitir números negativos.  
- Mostrar el valor total a pagar.

---

## 7. Restaurante “El Sabor Colombiano” — Menú + bebida opcional + IVA

**Menú base:** $12.000  

**Opciones de bebida:**
- sí → $3.000  
- no → $0  

**Impuesto:**  
Aplicar IVA del **8%** al total final.

**Objetivo:**  
Mostrar el valor con IVA incluido.

---

## 8. Empresa “TecnoPlus” — Evaluación compuesta

El usuario ingresa **dos notas (0.0 - 5.0):**

- Prueba técnica → 70%  
- Prueba lógica → 30%

**Cálculo:**

**Condiciones:**
- nota_final ≥ 3 → `"Aprobado"`  
- 2 ≤ nota_final < 3 → `"Revisión"`  
- < 2 → `"Reprobado"`  
- Validar que las notas estén dentro del rango 0.0 - 5.0.

---

## 9. Supermercado “AhorroMax” — Descuentos y envío

Cada producto cuesta **$2.000**.

**Reglas:**
- 30 unidades → 15% descuento  
- 10 unidades → 5% descuento  
- Si el total después del descuento es < $50.000 → agregar $5.000 de envío  

**Objetivo:**  
Calcular y mostrar el total final a pagar.

---

## 10. Club “Noche Estelar” — Acceso + validación documento

Pedir **edad** y **documento**.

**Reglas:**
- Edad ≥ 18 → puede entrar **solo si tiene documento**.  
- Edad < 18 → `"Entrada denegada"`  
- Edad ≥ 18 pero sin documento → `"Debe presentar documento"`  

**Objetivo:**  
Mostrar si la persona puede ingresar o no.

---

