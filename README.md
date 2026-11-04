# ZERO WASTE AI 3.0

Kazakhstan-focused waste reporting and recycling management platform.

The app includes public pollution reports and a map, resident and enterprise accounts, an admin review panel, and industrial waste analytics.

## Run locally (Windows)

```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python app.py
```

Configure `ZERO_WASTE_ADMIN_EMAIL` and `ZERO_WASTE_ADMIN_PASSWORD` to create the first administrator. No default demo or administrator passwords are included.
