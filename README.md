# AI-Driven Phishing: Adaptive Defense Strategies

AI-powered phishing detection system using machine learning to classify phishing vs. legitimate emails in real-time. Built with Python, Flask, and Scikit-Learn.

## 📄 Research Paper

[**Read the Full Research Paper (PDF)**](./Project.pdf)

**Authors:** Joel Yim, Jason Xu  
**Institution:** University of Washington

**Abstract:** Phishing attacks remain one of the biggest Cybersecurity threats, using manipulative tactics to obtain confidential information. This research evaluates AI-based phishing detection techniques including Machine Learning, Deep Learning, and Natural Language Processing models, exploring their advantages and limitations.

## Project Overview

Modern anti-phishing tools struggle to detect hyper-personalized AI-powered phishing techniques that bypass traditional email filters and blocklists. This project implements and analyzes various AI-based detection approaches to combat evolving phishing threats.

### Key Features

- **Real-time Classification**: Web interface for instant phishing email detection
- **Machine Learning Models**: Implementation and comparison of multiple ML algorithms (Logistic Regression, Decision Tree, Random Forest, KNN, SVM)
- **Deep Learning Analysis**: Evaluation of CNN, RNN, and Transformer models
- **NLP Techniques**: Assessment of BERT and other NLP approaches
- **Hybrid Approach**: Research into combining ML, DL, and NLP with human oversight
- **Automated Processing**: Error handling and data preprocessing automation

## Technologies Used

- **Python**: Core programming language
- **Flask**: Web framework for the detection interface
- **Scikit-Learn**: Machine learning model implementation
- **Pandas**: Data processing and analysis
- **Joblib**: Model serialization

### Models Evaluated

- **Machine Learning**: Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors (KNN), Support Vector Machine (SVM)
- **Deep Learning**: Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN), Transformers
- **NLP**: BERT (Bidirectional Encoder Representations from Transformers)

## Key Findings

Our research compared various detection approaches and found:

- **Hybrid Models (ML + NLP + Human)**: Achieved ~95% accuracy with high scalability
- **Deep Learning Models**: Reached ~90% accuracy but faced scalability challenges
- **Traditional ML Models**: Demonstrated 85-97.6% accuracy with moderate scalability
- **False Positive Management**: Critical challenge requiring reinforcement learning approaches

## Getting Started

### Prerequisites

```bash
Python 3.x
pip
```

### Installation

```bash
# Clone the repository
git clone https://github.com/joelyim/ai-phishing-detection.git
cd ai-phishing-detection

# Install dependencies
pip install -r requirements.txt
```

### Usage

```bash
# Run the Flask application
python app.py

# Access the web interface at http://localhost:5000
```

## Future Improvements

- Enhanced user interface for improved user experience
- Integration of additional ML detection methods
- Implementation of deep learning approaches
- Adversarial training to counter AI-generated phishing
- Real-time detection with low-latency AI models
- Cloud-based solutions for scalability

## 👥 Authors

- **Joel Yim** - [GitHub](https://github.com/joelyim) | [LinkedIn](https://www.linkedin.com/in/joelyim1/)
- **Jason Xu** - University of Washington

## 🙏 Acknowledgments

Special thanks to Dr. Geetha for her invaluable assistance and support throughout the research process.

## 📚 References

Full references and citations are available in the [research paper](./Project.pdf).
