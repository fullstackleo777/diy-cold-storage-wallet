# Create an Air Gapped Computer

## 💻 Air-Gapped Computer Wallet – Step-by-Step

### 🔧 What You Need

* A **dedicated laptop or computer**.
* Wallet software (e.g., **Electrum**).
* Encrypted **USB drive** for backups.
* Optional: Metal seed backup plate.

### 🪜 Steps

1. **Set Up the Computer:**

   * Install a fresh OS (e.g., Ubuntu).
   * Physically disconnect Wi-Fi and Ethernet.
   * NEVER connect it to the internet after setup.

2. **Install Electrum:**

   * On an online PC, download Electrum from [electrum.org](https://electrum.org).
   * Verify its **PGP signature** (optional but strongly recommended).
   * Move installer to air-gapped PC via USB.

3. **Generate Wallet:**

   * Launch Electrum in **offline mode**.
   * Create a **new wallet** and securely note down the **seed phrase**.
   * Save the wallet file to an **encrypted USB drive**.

4. **Verify Functionality:**

   * Write down the **receiving address** (public key).
   * Use this to receive crypto later.

5. **Store Seed and USB Separately:**

   * Consider using a **metal backup** for the seed.
   * Keep the air-gapped device powered off and locked away.

## 🔐 Security Tips

* **Always verify wallet software** with PGP signatures if possible.
* **Never store private keys or seeds digitally** on internet-connected devices.
* **Label nothing as “Crypto Wallet”** to avoid theft if discovered.
* **Consider Shamir Backup** for splitting a seed among trusted parties (e.g., 2 of 3 needed to recover).

___