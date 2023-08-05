# API Gateway + CORS + Lambda

How to Run!

```
# Configure AWS
aws configure

# Bootstrap CDK in new AWS Account
cdk bootstrap aws://<account-id>/<region>

# Activate venv
python -m virtualenv .venv
.\.venv\Scripts\activate.ps1

# Install CDK if not installed
npm install -g aws-cdk
pip install aws-cdk-lib

# List Modukes
cdk list

# Check CF Stack
cdk synth

# Deploy stack
cdk deploy Api*
```