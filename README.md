# CMS Hospitals Data Downloader

Usage:
1. Install Python 3.
2. Run: python cms_hospital_downloader.py
3. CSV files will be saved in the data/ folder with snake_case headers.
4. Subsequent runs only download files modified since the last run (tracked in run_metadata.json).
