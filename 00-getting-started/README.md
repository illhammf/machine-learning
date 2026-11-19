# Getting Started | Persiapan

This section prepares the development environment for the lessons in this repository.  
Bagian ini menyiapkan lingkungan pengembangan untuk mengikuti seluruh materi.

## 1. Install Python | Instal Python

Use Python 3.11 or newer. Verify the installation:

```bash
python --version
python -m pip --version
```

On some Linux systems, the command may be `python3`.

## 2. Create a virtual environment | Buat virtual environment

From the repository root:

```bash
python -m venv .venv
```

Activate it:

```powershell
# Windows PowerShell
.venv\Scripts\Activate.ps1
```

```bash
# Linux / macOS / WSL
source .venv/bin/activate
```

A virtual environment keeps this repository's packages separate from other Python projects.

Virtual environment menjaga dependensi proyek ini tetap terpisah dari proyek Python lainnya.

## 3. Install dependencies | Instal dependensi

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## 4. Verify the setup | Verifikasi instalasi

```bash
python -c "import numpy, pandas, matplotlib, seaborn, sklearn; print('Environment ready!')"
```

## 5. Launch JupyterLab | Jalankan JupyterLab

```bash
jupyter lab
```

## 6. Run a Python file | Jalankan file Python

```bash
python path/to/script.py
```

## Troubleshooting | Pemecahan masalah

- If `python` is not found, check the Python installation and PATH.
- If PowerShell blocks activation, review the execution policy for your environment; do not change system-wide settings unnecessarily.
- If a package installation fails, confirm that the virtual environment is active and that pip is up to date.

- Jika perintah `python` tidak ditemukan, periksa instalasi Python dan PATH.
- Jika aktivasi gagal, periksa kebijakan eksekusi PowerShell pada lingkungan yang digunakan.
- Jika instalasi package gagal, pastikan virtual environment aktif dan pip sudah diperbarui.
