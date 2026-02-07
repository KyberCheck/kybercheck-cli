# KyberCheck CLI Distribution

This repository is used for the distribution of pre-compiled KyberCheck binaries.

## 🚀 Fast Installation (Linux)

To install the KyberCheck CLI on your local machine:

1. **Download the latest binary**:
   ```bash
   curl -L -o kybercheck https://github.com/KyberCheck/kybercheck-cli/releases/latest/download/kybercheck-linux-amd64
   ```

2. **Make it executable**:
   ```bash
   chmod +x kybercheck
   ```

3. **Move to your PATH**:
   ```bash
   sudo mv kybercheck /usr/local/bin/
   ```

## 🛠 Usage

```bash
kybercheck scan . --api-key YOUR_API_KEY
```

## 🔗 Links

- **GitHub Action**: [KyberCheck/kybercheck-action](https://github.com/KyberCheck/kybercheck-action)
- **Dashboard & API Keys**: [kybercheck.com](https://kybercheck.com)
- **Full Documentation**: [Visit our website](https://www.kybercheck.com/docs)

---
_Note: The source code for the KyberCheck scanner is private to ensure the security of our detection patterns and proprietary analysis logic._
