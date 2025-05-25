# Create a USB Bootable Wallet

## 💾 USB Bootable Wallet – Step-by-Step

### 🔧 What You Need

* Two USB sticks: One for OS (e.g., Tails or Ubuntu), one for storage.
* A computer to boot from USB.
* Wallet software (e.g., Electrum Portable).

### 🪜 Steps

1. **Create Bootable USB:**

   * Download **Tails OS** or **Ubuntu Live**.
   * Use **Rufus** or **Etcher** to flash it onto USB A.

2. **Download Wallet:**

   * On an online PC, download **Electrum Portable**.
   * Transfer to USB B.

3. **Boot Into Live OS:**

   * Insert USB A and boot the computer from it.
   * Disable all internet connections.

4. **Run Electrum:**

   * Insert USB B with Electrum.
   * Generate a **new wallet** and save the seed phrase offline.

5. **Store Securely:**

   * Save the wallet data to USB B (encrypted).
   * Store the seed phrase (ideally on metal) and keep USB in secure place.

## 🔐 Security Tips

* **Always verify wallet software** with PGP signatures if possible.
* **Never store private keys or seeds digitally** on internet-connected devices.
* **Label nothing as “Crypto Wallet”** to avoid theft if discovered.
* **Consider Shamir Backup** for splitting a seed among trusted parties (e.g., 2 of 3 needed to recover).

---