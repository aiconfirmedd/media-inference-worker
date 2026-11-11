# media-inference-worker

Old test client from the media pipeline. The service account was still active
when I copied this, but I have no idea how much credit is left or when the key
will be rotated.

```bash
pip install -r requirements.txt
python generate.py qwen-image-3 "Editorial portrait, hard flash, 35mm grain"
```

Other endpoints and raw requests are in `RUNBOOK.md`.

## Credentials

Copy `.env.example` to `.env` and set your own Higgsfield credentials locally. Never commit `.env`. The previously tracked pair is public in upstream history: its actual owner must revoke it and inspect usage before replacing it. Removing this file does not revoke the pair.
