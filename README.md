# STEP JALANIN (PERHATIKAN URUTAN)
1. instal ffmpeg (windows) : https://phoenixnap.com/kb/ffmpeg-windows
2. instal python 3.12.3 (kalau belum instal)
3. activate venv : .\venv\Scripts\activate
4. instal package di environment tsb. : pip install -r requirements.txt
5. jalanin flask app : py app.py

# INFO LAIN
- python versi 3.10.2
- .\pythondist\python.exe --version
- inisiasi venv : python -m venv venv
- activate venv : .\venv\Scripts\activate
- hah : pip install flask flask-cors scikit-learn numpy
- pip install transformers ✅
- pip install torch ✅
- pip install pydub huggingsound jiwer
- torch==1.12.1

# COBA
{
    "avg_similarity": 20000,
    "best_params": {
        "min_silence_len": 300,
        "silence_thresh": -40
    },
    "completeness_percentage": {
        "avg_cer": 0.37319543201896144,
        "avg_similarity": 98.12789261341095,
        "avg_wer": 0.7625,
        "completeness_percentage": 100.0
    }
}