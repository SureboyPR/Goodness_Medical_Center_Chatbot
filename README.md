# Goodness Medical Center Chatbot Demo

An intelligent chatbot application built for Goodness Medical Center to assist patients with common inquiries, appointment bookings, and emergency information. The chatbot features a user-friendly interface powered by Google Gemini AI for enhanced conversational capabilities.

## 🏥 Features

- **Visiting Hours Information**: Quick access to hospital visiting times and policies
- **Appointment Booking**: Streamlined appointment scheduling system
- **Emergency Contact Information**: Instant access to emergency contacts and procedures
- **AI-Powered Assistant**: Intelligent responses to general medical inquiries powered by Google Gemini
- **User-Friendly Interface**: Clean, intuitive Streamlit-based web interface

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Web Framework**: Streamlit
- **AI Integration**: Google Gemini API
- **Development Environment**: VS Code

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Google Gemini API key
- Required Python packages (see requirements.txt)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SureboyPR/goodness-medical-chatbot.git
   cd goodness-medical-chatbot
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Google Gemini API**
   - Obtain your Google Gemini API key
   - Create a `.env` file in the project root
   - Add your API key:
     ```
     GEMINI_API_KEY=your_api_key_here
     ```

4. **Run the application**
   ```bash
   streamlit run hospital_chatbot_app.py
   ```

5. **Access the chatbot**
   - Open your web browser
   - Navigate to `http://localhost:8501`
   - Start interacting with the Goodness Medical Center chatbot!

## 📋 Usage

### Main Features

1. **Visiting Times**: Ask about hospital visiting hours and policies
2. **Book Appointments**: Schedule appointments with healthcare providers
3. **Emergency Information**: Get emergency contact details and procedures
4. **General Inquiries**: Ask the AI assistant about medical services, directions, or other hospital-related questions

### Sample Interactions

- "What are your visiting hours?"
- "I need to book an appointment with a cardiologist"
- "What's the emergency contact number?"
- "Do you have parking facilities?"
- "What services does Goodness Medical Center offer?"

## 🏗️ Project Structure

```
goodness-medical-chatbot/
├── hospital_chatbot_app.py     # Main Streamlit application
├── requirements.txt            # Python dependencies
├── .env                       # Environment variables (API keys)
├── .gitignore                 # Git ignore file
└── README.md                  # Project documentation
```

## 🤖 AI Integration

The chatbot leverages Google Gemini's advanced language model to provide:
- Natural language understanding
- Contextual responses
- Medical information assistance
- Conversational flow management

## 🔧 Configuration

### Environment Variables

Create a `.env` file with the following variables:
```
GEMINI_API_KEY=your_google_gemini_api_key
HOSPITAL_NAME=Goodness Medical Center
EMERGENCY_CONTACT=+1-234-567-8900
```

## 🚦 Demo Status

This is a **demonstration project** showcasing the capabilities of an AI-powered medical center chatbot. It includes:
- Sample hospital information
- Mock appointment booking flow
- Real AI-powered responses via Google Gemini
- Prototype user interface

## 🔒 Privacy & Security

- Patient data is handled according to demo standards
- API keys are secured through environment variables
- No real medical advice is provided (for demonstration purposes only)

## 🤝 Contributing

This is a demo project for Goodness Medical Center. For suggestions or improvements:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 License

This project is created for demonstration purposes. Please refer to the LICENSE file for more details.

## 📞 Support

For questions about this demo or potential implementation:
- Email: [adedoyinvictor2015@gmail.com]
- Project Issues: GitHub Issues tab


**Note**: This is a demonstration chatbot. For actual medical emergencies, please contact emergency services immediately.
