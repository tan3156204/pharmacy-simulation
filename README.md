# City Pharmacy Simulator

This repo contains two Streamlit apps:

1. `streamlit_app.py` — single-round simulator (7 stores, 3 locations).
2. `streamlit_app_prototype.py` — multi-round prototype (closer to Communi‑Pharm).

## Deploy on Streamlit Cloud
1. Create a new GitHub repository and upload these files.
2. On https://share.streamlit.io/deploy fill in:
   - **Repository**: `<your-username>/<your-repo-name>`
   - **Branch**: `main` (or the branch you use)
   - **Main file path**: `streamlit_app_prototype.py`  (or `streamlit_app.py` for the single-round app)
3. Click **Deploy**.

## Run locally
```bash
pip install -r requirements.txt
streamlit run streamlit_app_prototype.py
# or
streamlit run streamlit_app.py
```
