# ReportFlow - Automated Report Generator

AWS-powered automation system for generating and distributing reports on custom schedules.

## Features

- Automated report generation
- EventBridge Scheduler integration
- Multiple output formats (PDF, Excel, CSV)
- Serverless architecture
- Cost-efficient scaling

## Tech Stack

- Python
- AWS (Lambda, EventBridge, S3, SES)

## Quick Start

1. Clone the repo:
```bash
git clone https://github.com/Shrikant8705/ReportFlow.git
cd ReportFlow
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure AWS credentials:
```bash
aws configure
```

4. Run:
```bash
python main.py
```

## Configuration

Set up environment variables in `.env`:
```
AWS_REGION=us-east-1
AWS_S3_BUCKET=your-bucket
REPORT_SCHEDULE=0 8 * * ? *
```

## License

MIT