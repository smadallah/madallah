# ⚡ ElecMachine Expert

**Electrical Machines Instructional & Troubleshooting Platform**

A comprehensive web-based platform for tertiary education in electrical machine diagnostics, virtual testing, and troubleshooting. Built with Streamlit frontend and FastAPI backend.

## 🎯 Key Features

- **Module 1: Safety & PPE** - Interactive safety certification for high-voltage environments
- **Module 2: Machine Fundamentals** - 3D models and specifications for DC, Induction, and Synchronous motors
- **Module 3: Virtual Testing** - Simulation of No-Load, Blocked-Rotor, and Load tests
- **Module 4: Troubleshooting Engine** - Decision-tree fault diagnosis with ranked root causes
- **Analytics Dashboard** - Track learning curves and fault patterns across cohorts

## 📋 Prerequisites

- Python 3.8+
- Docker & Docker Compose (optional)
- PostgreSQL 12+ (optional, for production)
- Firebase account (optional, for cloud deployment)

## 🚀 Quick Start

### Local Development

```bash
# Clone repository
git clone https://github.com/smadallah/madallah.git
cd madallah

# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
cd streamlit_app
streamlit run app.py
```

## 📊 Project Structure

See docs/ARCHITECTURE.md for detailed project layout.