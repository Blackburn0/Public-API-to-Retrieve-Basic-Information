# HNG12 Public API

This is a simple public API that returns the following details in JSON format:
- Your registered email address on the HNG12 Slack workspace.
- The current datetime in ISO 8601 format (UTC).
- The GitHub repository URL of the project.

## Technology Stack
- **Programming Language:** Python
- **Framework:** FastAPI
- **Deployment:** Hosted on Vercel
- **CORS Handling:** Configured to allow cross-origin requests

## API Documentation

### Endpoint
**GET** `/`

### Response Format (200 OK)
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

## Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

### Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the API Locally
```bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

### Deployment
This API is deployed and publicly accessible at:
`https://public-api-to-retrieve-basic-information.vercel.app/`

## Hiring Links
- [Hire Python Developers](https://hng.tech/hire/python-developers)