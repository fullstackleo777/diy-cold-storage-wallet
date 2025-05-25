# Crear una Computadora Aislada del Internet

## 💻 Billetera en Computadora Aislada – Paso a Paso

### 🔧 Lo Que Necesitas

* Una **laptop o computadora dedicada**.
* Software de billetera (por ejemplo, **Electrum**).
* **USB encriptada** para respaldos.
* Opcional: Placa metálica para respaldo de semilla.

### 🪜 Pasos

1. **Configura la Computadora:**

   * Instala un sistema operativo nuevo (por ejemplo, Ubuntu).
   * Desconecta físicamente el Wi-Fi y el cable Ethernet.
   * NUNCA la conectes a internet después de configurarla.

2. **Instala Electrum:**

   * En una PC con internet, descarga Electrum desde [electrum.org](https://electrum.org).
   * Verifica su **firma PGP** (opcional pero muy recomendable).
   * Mueve el instalador a la computadora aislada con un USB.

3. **Genera la Billetera:**

   * Inicia Electrum en **modo sin conexión**.
   * Crea una **nueva billetera** y anota de forma segura la **frase semilla**.
   * Guarda el archivo de la billetera en un **USB encriptado**.

4. **Verifica la Funcionalidad:**

   * Escribe la **dirección de recepción** (clave pública).
   * Usa esta dirección para recibir criptomonedas después.

5. **Guarda la Semilla y el USB por Separado:**

   * Considera usar un **respaldo metálico** para la semilla.
   * Mantén el dispositivo aislado apagado y guardado en un lugar seguro.

## 🔐 Consejos de Seguridad

* **Siempre verifica el software de la billetera** con firmas PGP si es posible.
* **Nunca guardes llaves privadas o semillas digitalmente** en dispositivos conectados a internet.
* **No etiquetes nada como “Billetera Cripto”** para evitar robos si es descubierto.
* **Considera el Respaldo Shamir** para dividir una semilla entre personas de confianza (por ejemplo, se necesitan 2 de 3 para recuperar).

___