# Retail Compliance Dashboard (Streamlit)

Pipeline kualitas data → klasifikasi transaksi (Cancelled / Admin-Fee / Zero Price / Normal Sale) → insight bisnis + ekspor Excel & HTML offline.

## Jalankan lokal
pip install -r requirements.txt
streamlit run app.py

## Deploy
- Streamlit Cloud: hubungkan repo → pilih `app.py`
- Tambahkan secret: `GEMINI_API_KEY` untuk narasi AI (opsional)
