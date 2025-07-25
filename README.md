# 🛡️ Image Encryption Tool – Python + Tkinter + Pillow

A simple but effective GUI-based image encryption and decryption tool built using Python. This tool encrypts an image by shuffling its pixels based on a seed key, and can also decrypt it using the same key. Perfect for demonstrating basic image manipulation and lightweight encryption techniques in a cybersecurity context.

## 💡 Features

- 🖼️ Select and encrypt/decrypt any `.png` or `.jpg` image
- 🔐 Use a seed key to control the encryption pattern
- 🔁 Reversible encryption: same seed restores the original image
- 🖱️ Intuitive GUI using Tkinter
- 📦 Easy to run — no database or server required

### 📸 How It Works

The program uses Python’s `random` module with a **seed key** to shuffle the pixel indices of an image:

- **Encryption**: Pixels are shuffled using a deterministic random generator seeded by the user key.
- **Decryption**: The pixels are reordered back into their original form using the same key.

This makes the encryption **reversible only if the same key is reused**.

#### ⚙️ How to Run

**📦 Prerequisites**

- Python 3.x
- Pillow (Python Imaging Library)
- Tkinter (comes pre-installed with Python)

**🔧 Installation**

```bash
pip install pillow




