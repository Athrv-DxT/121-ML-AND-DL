# 📘 Day 54 – Autoencoder Concept using PCA

## 🧩 Concepts Covered
- **Dimensionality Reduction** using Principal Component Analysis (PCA)
- **Encoding & Decoding** steps to simulate an **Autoencoder**
- **Reconstruction Error** and **Explained Variance**
- Visualization of **Original vs Reconstructed** images

---

## 🧠 Concept Summary

Autoencoders are neural networks that learn to **compress** (encode) data into a smaller dimension and then **reconstruct** (decode) it back to the original form.

Here, we use **PCA** to simulate this compression and reconstruction mathematically.

### Formula:
**X' = Wᵀ(WX)**

where:  
- `W` → Principal Component Matrix  
- `X` → Original Data  
- `X'` → Reconstructed Data

---

## 🧾 Steps:
1. Load the **Digits dataset** (8x8 grayscale images).  
2. **Scale** data using StandardScaler.  
3. Apply **PCA(n_components=20)** → Encoder.  
4. **Inverse Transform** → Decoder.  
5. Compare Original vs Reconstructed images.  
6. Measure **Reconstruction Error**.

---

