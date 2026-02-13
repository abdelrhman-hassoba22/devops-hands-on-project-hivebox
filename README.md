# **HiveBox - Phase 2**

## Version: 0.0.1

### Overview
Initial version that prints the application version.

### Prerequisites
- Python 3.11+
- Docker

### Local Testing

#### Run without Docker:
```bash
python app.py
```

Expected output:
```
HiveBox version: 0.0.1
```

#### Run with Docker:

1. Build the image:
```bash
docker build -t hivebox:0.0.1 .
```

2. Run the container:
```bash
docker run --rm hivebox:0.0.1
```

Expected output:
```
HiveBox version: 0.0.1
```

### Project Structure
```
.
├── app.py              # Main application
├── Dockerfile          # Docker configuration
├── requirements.txt    # Python dependencies
├── .dockerignore      # Docker ignore rules
└── README.md          # This file
```

