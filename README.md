# Readmission Forecasting System

A comprehensive healthcare analytics platform that predicts patient readmission risks using machine learning models.

## 🚀 Features

- **Patient Data Analysis**: Upload and analyze patient data in real-time
- **Multiple ML Models**: Support for various machine learning models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - LightGBM
  - MLP (Multi-layer Perceptron)
- **Interactive Dashboard**: Visualize predictions and patient data
- **Model Comparison**: Compare performance across different models
- **Data Export**: Export analysis results and predictions
- **Real-time API**: RESTful API for model predictions and data processing

## 🛠️ Technologies Used

### Frontend
- **React**: UI framework
- **TypeScript**: Type-safe JavaScript
- **Vite**: Next-generation frontend tooling
- **Tailwind CSS**: Utility-first CSS framework
- **shadcn/ui**: Beautiful, accessible components
- **Chart.js**: Interactive data visualization

### Backend
- **Python**: Core programming language
- **Flask**: Web framework
- **Scikit-learn**: Machine learning library
- **XGBoost**: Gradient boosting framework
- **LightGBM**: Lightweight gradient boosting framework
- **TensorFlow**: Deep learning framework

### Infrastructure
- **Docker**: Containerization
- **Docker Compose**: Multi-container orchestration
- **Nginx**: Web server and reverse proxy
- **Git**: Version control

## 📋 Prerequisites

- Node.js (v18 or higher)
- Python (v3.9 or higher)
- Docker and Docker Compose
- Git

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd readmission-forecasting
   ```

2. Install dependencies:
   ```bash
   # Frontend dependencies
   npm install
   
   # Backend dependencies
   pip install -r requirements.txt
   ```

3. Start the development environment:
   ```bash
   # Start frontend
   npm run dev
   
   # Start backend
   python src/api-server-template/app.py
   ```

For detailed deployment instructions, see [GUIDE.md](GUIDE.md).

## 📊 Project Structure

```
readmission-forecasting/
├── src/
│   ├── api-server-template/    # Backend API server
│   ├── components/             # React components
│   ├── services/              # API services
│   └── utils/                 # Utility functions
├── public/                    # Static assets
├── dist/                      # Build output
└── docker/                    # Docker configuration
```

## 🔧 Configuration

The application can be configured through environment variables:

- `VITE_API_URL`: Backend API URL
- `VITE_CLERK_PUBLISHABLE_KEY`: Authentication key
- `MODEL_VERSION`: Current model version
- `DEFAULT_MODEL`: Default model to use
- `BATCH_SIZE`: Prediction batch size

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support, email support@example.com or join our Slack channel.
