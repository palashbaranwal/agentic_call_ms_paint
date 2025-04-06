# Agentic Call to MS Paint

An innovative project that demonstrates AI-powered automation of Microsoft Paint using Google's Gemini AI model. This project showcases the integration of natural language processing with desktop application automation.

Demo - https://www.youtube.com/watch?v=gIQtjWXhp3Q

## 🌟 Features

- AI-powered interpretation of user commands using Gemini 2.0
- Automated control of Microsoft Paint
- Mathematical computations and string manipulations
- Real-time drawing and text placement in MS Paint
- Execution logging for debugging and monitoring

## 🛠️ Technologies Used

- Python 3.x
- Google Gemini AI API
- pywinauto (for Windows automation)
- win32gui and win32con (for Windows GUI interaction)
- PIL (Python Imaging Library)
- asyncio (for asynchronous operations)

## 📋 Prerequisites

- Windows Operating System
- Python 3.x installed
- Microsoft Paint installed
- Google Cloud API credentials

## 🔧 Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd Agentic_call_to_Ms_Paint
```

2. Install required dependencies:
```bash
pip install python-dotenv google-cloud-aiplatform pywinauto Pillow
```

3. Set up environment variables:
Create a `.env` file in the root directory and add:
```
GEMINI_API_KEY=your_gemini_api_key_here
```

## 📝 Project Structure

- `submit.py`: Main execution script containing AI integration and control flow
- `example2.py`: Implementation of tools and MS Paint automation functions
- `execution_logs.txt`: Logs of program execution
- `README.md`: Project documentation

## 🚀 Usage

1. Ensure Microsoft Paint is installed on your system
2. Run the main script:
```bash
python submit.py
```

### Example Operations

The system can perform various operations, such as:

1. Mathematical calculations:
   - Basic arithmetic operations
   - Exponential calculations
   - Trigonometric functions

2. String manipulations:
   - Converting text to ASCII values
   - Processing character arrays

3. MS Paint automation:
   - Opening Paint automatically
   - Drawing rectangles with specific coordinates
   - Adding text inside shapes

### Sample Query

```python
"""Get the ASCII values of all characters in the word "INDIA", 
then compute the sum of exponentials of those ASCII values. 
After that, open Microsoft Paint, draw a rectangle with suitable coordinates, 
and print the final result inside the rectangle."""
```

## ⚙️ Configuration

The project uses several configuration parameters:

- Maximum iterations: 6 (configurable in submit.py)
- Default rectangle coordinates: 0,380,540,700
- Timeout for AI responses: 10 seconds

## 🔍 Debugging

- Check `execution_logs.txt` for detailed execution logs
- The system includes debug prints for tracking:
  - AI response generation
  - Function calls
  - Paint automation steps

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⚠️ Known Limitations

- Works only on Windows operating systems
- Requires specific screen coordinates for Paint automation
- May need adjustments for different screen resolutions
- Limited to 6 iterations per session

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Google Gemini AI team for the AI model
- pywinauto community for Windows automation tools
- Contributors and testers

## 📞 Support

For support, please open an issue in the repository or contact the maintainers.

---
*Note: This project is for demonstration purposes and may require adjustments based on your specific system configuration.* 
