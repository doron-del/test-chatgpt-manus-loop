# Flask Hello World Project

This is a simple Flask web server project that includes two routes:

- `/` : Returns "Hello, World!"
- `/api/status` : Returns JSON status `{ "status": "ok" }`

## Setup Instructions

1. Create and activate a Python virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Flask app:

```bash
python main.py
```

4. Open your browser and visit `http://localhost:5000` to see the Hello World message.

5. Visit `http://localhost:5000/api/status` to see the API status JSON.

## Notes

- The app runs on port 5000 by default and listens on all interfaces.
