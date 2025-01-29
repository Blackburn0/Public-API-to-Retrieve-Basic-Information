# Project documentation

## Description

This is a simple public API that returns the following details in JSON format:
- My registered email address on the HNG12 Slack workspace.
- The current datetime in ISO 8601 format (UTC).
- My GitHub repository URL of the project.

- Endpoint - https://public-api-to-retrieve-basic-information.vercel.app/

### Example Response

```bash
{
    "email": "hamzatadebayo5@gmail.com",
    "current_datetime": "2025-01-30T09:30:00Z",
    "github_url": "https://github.com/Blackburn0/Public-API-to-Retrieve-Basic-Information",
}
```

## Project setup

```bash
pip install -r requirements.txt
```

## Compile and run the project

```bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload

```

## Back Links

- [https://hng.tech/hire/python-developers](https://hng.tech/hire/python-developers)