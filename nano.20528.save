# Base image
FROM python:3.11-slim

# Container এর ভিতরে working directory
WORKDIR /app

# Local সব file container এ copy করবে
COPY . .

# Container run হলে এই command চলবে
CMD ["python", "app.py"]
