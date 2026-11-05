# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 1 correctas de 17 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 2: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT * FROM producto' at line 5


## ❌ Query 3: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-codigo | nombre | precio | codigo_fabricante
-1.00 | Disco duro SATA3 1TB | 86.99 | 5.00
-2.00 | Memoria RAM DDR4 8GB | 120.00 | 6.00
-3.00 | Disco SSD 1 TB | 150.99 | 4.00
-4.00 | GeForce GTX 1050Ti | 185.00 | 7.00
-5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
-6.00 | Monitor 24 LED Full HD | 202.00 | 1.00
-7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
-8.00 | Portátil Yoga 520 | 559.00 | 2.00
-9.00 | Portátil Ideapd 320 | 444.00 | 2.00
-10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
-11.00 | Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
+nombre | precio_eur | precio_usd
+Disco duro SATA3 1TB | 86.99 | 86.99
+Memoria RAM DDR4 8GB | 120.00 | 120.00
+Disco SSD 1 TB | 150.99 | 150.99
+GeForce GTX 1050Ti | 185.00 | 185.00
+GeForce GTX 1080 Xtreme | 755.00 | 755.00
+Monitor 24 LED Full HD | 202.00 | 202.00
+Monitor 27 LED Full HD | 245.99 | 245.99
+Portátil Yoga 520 | 559.00 | 559.00
+Portátil Ideapd 320 | 444.00 | 444.00
+Impresora HP Deskjet 3720 | 59.99 | 59.99
+Impresora HP Laserjet Pro M26nw | 180.00 | 180.00
```

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio_eur | precio_usd
-Disco duro SATA3 1TB | 86.99 | 86.99
-Memoria RAM DDR4 8GB | 120.00 | 120.00
-Disco SSD 1 TB | 150.99 | 150.99
-GeForce GTX 1050Ti | 185.00 | 185.00
-GeForce GTX 1080 Xtreme | 755.00 | 755.00
-Monitor 24 LED Full HD | 202.00 | 202.00
-Monitor 27 LED Full HD | 245.99 | 245.99
-Portátil Yoga 520 | 559.00 | 559.00
-Portátil Ideapd 320 | 444.00 | 444.00
-Impresora HP Deskjet 3720 | 59.99 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00 | 180.00
+nom del producte | euros | dòlars
+Disco duro SATA3 1TB | 86.99 | 95.69
+Memoria RAM DDR4 8GB | 120.00 | 132.00
+Disco SSD 1 TB | 150.99 | 166.09
+GeForce GTX 1050Ti | 185.00 | 203.50
+GeForce GTX 1080 Xtreme | 755.00 | 830.50
+Monitor 24 LED Full HD | 202.00 | 222.20
+Monitor 27 LED Full HD | 245.99 | 270.59
+Portátil Yoga 520 | 559.00 | 614.90
+Portátil Ideapd 320 | 444.00 | 488.40
+Impresora HP Deskjet 3720 | 59.99 | 65.99
+Impresora HP Laserjet Pro M26nw | 180.00 | 198.00
```

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nom del producte | euros | dòlars
-Disco duro SATA3 1TB | 86.99 | 95.69
-Memoria RAM DDR4 8GB | 120.00 | 132.00
-Disco SSD 1 TB | 150.99 | 166.09
-GeForce GTX 1050Ti | 185.00 | 203.50
-GeForce GTX 1080 Xtreme | 755.00 | 830.50
-Monitor 24 LED Full HD | 202.00 | 222.20
-Monitor 27 LED Full HD | 245.99 | 270.59
-Portátil Yoga 520 | 559.00 | 614.90
-Portátil Ideapd 320 | 444.00 | 488.40
-Impresora HP Deskjet 3720 | 59.99 | 65.99
-Impresora HP Laserjet Pro M26nw | 180.00 | 198.00
+nombre | precio
+DISCO DURO SATA3 1TB | 86.99
+MEMORIA RAM DDR4 8GB | 120.00
+DISCO SSD 1 TB | 150.99
+GEFORCE GTX 1050TI | 185.00
+GEFORCE GTX 1080 XTREME | 755.00
+MONITOR 24 LED FULL HD | 202.00
+MONITOR 27 LED FULL HD | 245.99
+PORTÁTIL YOGA 520 | 559.00
+PORTÁTIL IDEAPD 320 | 444.00
+IMPRESORA HP DESKJET 3720 | 59.99
+IMPRESORA HP LASERJET PRO M26NW | 180.00
```

⏱ Tiempo: 0.20 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
 nombre | precio
-DISCO DURO SATA3 1TB | 86.99
-MEMORIA RAM DDR4 8GB | 120.00
-DISCO SSD 1 TB | 150.99
-GEFORCE GTX 1050TI | 185.00
-GEFORCE GTX 1080 XTREME | 755.00
-MONITOR 24 LED FULL HD | 202.00
-MONITOR 27 LED FULL HD | 245.99
-PORTÁTIL YOGA 520 | 559.00
-PORTÁTIL IDEAPD 320 | 444.00
-IMPRESORA HP DESKJET 3720 | 59.99
-IMPRESORA HP LASERJET PRO M26NW | 180.00
+disco duro sata3 1tb | 86.99
+memoria ram ddr4 8gb | 120.00
+disco ssd 1 tb | 150.99
+geforce gtx 1050ti | 185.00
+geforce gtx 1080 xtreme | 755.00
+monitor 24 led full hd | 202.00
+monitor 27 led full hd | 245.99
+portátil yoga 520 | 559.00
+portátil ideapd 320 | 444.00
+impresora hp deskjet 3720 | 59.99
+impresora hp laserjet pro m26nw | 180.00
```

⏱ Tiempo: 0.18 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,10 @@
-nombre | precio
-disco duro sata3 1tb | 86.99
-memoria ram ddr4 8gb | 120.00
-disco ssd 1 tb | 150.99
-geforce gtx 1050ti | 185.00
-geforce gtx 1080 xtreme | 755.00
-monitor 24 led full hd | 202.00
-monitor 27 led full hd | 245.99
-portátil yoga 520 | 559.00
-portátil ideapd 320 | 444.00
-impresora hp deskjet 3720 | 59.99
-impresora hp laserjet pro m26nw | 180.00
+nombre | iniciales
+Asus | AS
+Lenovo | LE
+Hewlett-Packard | HE
+Samsung | SA
+Seagate | SE
+Crucial | CR
+Gigabyte | GI
+Huawei | HU
+Xiaomi | XI
```

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,12 @@
-nombre | iniciales
-Asus | AS
-Lenovo | LE
-Hewlett-Packard | HE
-Samsung | SA
-Seagate | SE
-Crucial | CR
-Gigabyte | GI
-Huawei | HU
-Xiaomi | XI
+nombre | precio
+Disco duro SATA3 1TB | 87.00
+Memoria RAM DDR4 8GB | 120.00
+Disco SSD 1 TB | 151.00
+GeForce GTX 1050Ti | 185.00
+GeForce GTX 1080 Xtreme | 755.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 246.00
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
+Impresora HP Deskjet 3720 | 60.00
+Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.19 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-Disco duro SATA3 1TB | 87.00
+nombre | precio truncado
+Disco duro SATA3 1TB | 86.00
 Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 151.00
+Disco SSD 1 TB | 150.00
 GeForce GTX 1050Ti | 185.00
 GeForce GTX 1080 Xtreme | 755.00
 Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 246.00
+Monitor 27 LED Full HD | 245.00
 Portátil Yoga 520 | 559.00
 Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 60.00
+Impresora HP Deskjet 3720 | 59.00
 Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.18 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio truncado
-Disco duro SATA3 1TB | 86.00
-Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 150.00
-GeForce GTX 1050Ti | 185.00
-GeForce GTX 1080 Xtreme | 755.00
-Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.00
-Portátil Yoga 520 | 559.00
-Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 59.00
-Impresora HP Laserjet Pro M26nw | 180.00
+codigo_fabricante
+1.00
+1.00
+2.00
+2.00
+3.00
+3.00
+4.00
+5.00
+6.00
+6.00
+7.00
```

⏱ Tiempo: 0.20 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 11: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,8 @@
 codigo_fabricante
 1.00
-1.00
 2.00
-2.00
-3.00
 3.00
 4.00
 5.00
 6.00
-6.00
 7.00
```

⏱ Tiempo: 0.19 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 12: Incorrecto
```diff
--- 
+++ 
@@ -1,8 +1,10 @@
-codigo_fabricante
-1.00
-2.00
-3.00
-4.00
-5.00
-6.00
-7.00
+nombre
+Asus
+Crucial
+Gigabyte
+Hewlett-Packard
+Huawei
+Lenovo
+Samsung
+Seagate
+Xiaomi
```

⏱ Tiempo: 0.19 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
 nombre
+Xiaomi
+Seagate
+Samsung
+Lenovo
+Huawei
+Hewlett-Packard
+Gigabyte
+Crucial
 Asus
-Crucial
-Gigabyte
-Hewlett-Packard
-Huawei
-Lenovo
-Samsung
-Seagate
-Xiaomi
```

⏱ Tiempo: 0.17 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 14: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,12 @@
-nombre
-Xiaomi
-Seagate
-Samsung
-Lenovo
-Huawei
-Hewlett-Packard
-Gigabyte
-Crucial
-Asus
+nombre | precio
+Disco duro SATA3 1TB | 86.99
+Disco SSD 1 TB | 150.99
+GeForce GTX 1050Ti | 185.00
+GeForce GTX 1080 Xtreme | 755.00
+Impresora HP Deskjet 3720 | 59.99
+Impresora HP Laserjet Pro M26nw | 180.00
+Memoria RAM DDR4 8GB | 120.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 245.99
+Portátil Ideapd 320 | 444.00
+Portátil Yoga 520 | 559.00
```

⏱ Tiempo: 0.18 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,6 @@
-nombre | precio
-Disco duro SATA3 1TB | 86.99
-Disco SSD 1 TB | 150.99
-GeForce GTX 1050Ti | 185.00
-GeForce GTX 1080 Xtreme | 755.00
-Impresora HP Deskjet 3720 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00
-Memoria RAM DDR4 8GB | 120.00
-Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.99
-Portátil Ideapd 320 | 444.00
-Portátil Yoga 520 | 559.00
+codigo | nombre
+1.00 | Asus
+2.00 | Lenovo
+3.00 | Hewlett-Packard
+4.00 | Samsung
+5.00 | Seagate
```

⏱ Tiempo: 0.18 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 16: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,3 @@
 codigo | nombre
-1.00 | Asus
-2.00 | Lenovo
-3.00 | Hewlett-Packard
 4.00 | Samsung
 5.00 | Seagate
```

⏱ Tiempo: 0.17 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 17: Error
- **Descripción**: 'NoneType' object is not iterable

