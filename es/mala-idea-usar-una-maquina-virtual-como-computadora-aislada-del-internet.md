# Mala Idea: Usar una Máquina Virtual como Computadora Aislada del Internet

Implementar una computadora aislada (air-gapped) dentro de una máquina virtual (VM) en una computadora conectada a internet contradice completamente el propósito del aislamiento.

## 🚫 Por Qué Es Una Mala Idea

1. **No hay aislamiento real**  
Una máquina virtual (VM) que se ejecuta en un host conectado a internet **comparte el mismo hardware** (CPU, RAM, a veces disco). Si el host está comprometido, **la VM también lo está**. Los atacantes pueden saltarse esa "brecha" con ataques de canal lateral, vulnerabilidades del hipervisor o exploits de escape de VM.

2. **Sigues conectado a la red**  
Aunque la VM no tenga una NIC virtual (tarjeta de red), tu sistema operativo anfitrión sí la tiene. El malware en tu sistema principal puede **monitorear, copiar o interactuar con la VM**, rompiendo completamente el modelo de aislamiento.

3. **El aislamiento físico requiere separación física**  
La esencia de una computadora aislada es que **no haya ruta física o inalámbrica hacia una red**. Una VM no cuenta — es como decir que una celda en tu sala sigue siendo segura cuando toda la casa está comprometida.

### ✅ Qué Deberías Hacer en Su Lugar

Para **aislar correctamente** una computadora, sigue esta configuración:

| Característica              | Configuración Aislada Real           |
| --------------------------- | ------------------------------------ |
| **Hardware separado**       | Sí – computadora física diferente    |
| **Sin interfaces de red**   | Quitar o desactivar Wi-Fi/Ethernet   |
| **Sin USB salvo escaneo**   | Usar medios de solo escritura o USB seguros |
| **Sin periféricos compartidos** | No compartir teclado, ratón, discos  |
| **Sin virtualización**      | Instalación directa de sistema operativo |

### ⚠️ Ejemplo de Uso en la Vida Real (Relevancia en Cripto)

Si planeas:

* **Firmar transacciones cripto sin conexión** (por ejemplo, con GPG, Bitcoin Core o billeteras hardware)
* **Guardar claves privadas de billeteras frías**
* **Generar frases semilla de forma segura**

Entonces una **máquina físicamente aislada** es **obligatoria**.

### 🛡️ Consejo Pro

Para configuraciones cripto sin conexión, usa:

* Una laptop económica o una Raspberry Pi
* Sistema operativo Linux con suma de verificación verificada desde una descarga limpia (por ejemplo, Tails, Ubuntu)
* Arranca desde un **USB en modo Live** si no deseas instalar
* Firma transacciones sin conexión → transfiere vía código QR o USB solo cuando sea necesario (con medidas de higiene estrictas)

___
