# Crear una Billetera Booteable desde USB

## 💾 Billetera Booteable en USB – Paso a Paso

### 🔧 Lo Que Necesitas

* Dos memorias USB: Una para el sistema operativo (por ejemplo, Tails o Ubuntu), otra para almacenamiento.
* Una computadora para arrancar desde USB.
* Software de billetera (por ejemplo, Electrum Portable).

### 🪜 Pasos

1. **Crea el USB Booteable:**

   * Descarga **Tails OS** o **Ubuntu Live**.
   * Usa **Rufus** o **Etcher** para grabarlo en la USB A.

2. **Descarga la Billetera:**

   * En una PC con internet, descarga **Electrum Portable**.
   * Transfiérelo a la USB B.

3. **Arranca el Sistema Operativo Live:**

   * Inserta la USB A y arranca la computadora desde ahí.
   * Desactiva todas las conexiones a internet.

4. **Ejecuta Electrum:**

   * Inserta la USB B con Electrum.
   * Genera una **nueva billetera** y guarda la frase semilla sin conexión.

5. **Guarda de Forma Segura:**

   * Guarda los datos de la billetera en la USB B (encriptado).
   * Guarda la frase semilla (idealmente en metal) y conserva la USB en un lugar seguro.

## 🔐 Consejos de Seguridad

* **Siempre verifica el software de la billetera** con firmas PGP si es posible.
* **Nunca guardes llaves privadas o semillas digitalmente** en dispositivos conectados a internet.
* **No etiquetes nada como “Billetera Cripto”** para evitar robos si es descubierto.
* **Considera el Respaldo Shamir** para dividir una semilla entre personas de confianza (por ejemplo, se necesitan 2 de 3 para recuperar).

___