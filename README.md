# 🧬 Multimodal AI Agent

An advanced AI agent that combines video analysis and web search capabilities using Google's Gemini 2.0 model. This powerful system can analyze uploaded videos, understand visual content, and provide comprehensive answers by combining visual understanding with real-time web research.

## 🌟 Features

### Core Functionality
- **Video Analysis**: Deep analysis of video content using Gemini 2.0 Flash
- **Web Research Integration**: Real-time web search via DuckDuckGo
- **Multimodal Understanding**: Combines visual and textual information
- **Real-time Processing**: Instant video analysis and response generation
- **Interactive Interface**: User-friendly Streamlit interface
- **Context-Aware Responses**: Maintains context across video and web content

### Advanced Capabilities
- **Multi-Format Support**: Handles MP4, MOV, AVI, and other video formats
- **Visual Object Detection**: Identifies objects, people, and scenes in videos
- **Action Recognition**: Understands activities and movements
- **Text Extraction**: Reads text from video frames
- **Scene Understanding**: Analyzes video scenes and contexts
- **Temporal Analysis**: Understands video sequences and timing

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Google Gemini API key
- Sufficient storage for video processing

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rchhabra13/portfolio-projects.git
   cd portfolio-projects/multimodal_ai_agent
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up API keys**
   ```bash
   export GOOGLE_API_KEY="your-google-api-key-here"
   ```

4. **Run the application**
   ```bash
   streamlit run multimodal_agent.py
   ```

5. **Access the application**
   - Open your browser to `http://localhost:8501`
   - Upload a video file
   - Ask questions about the video content

## 💡 Usage Examples

### Video Content Analysis
```
"What is happening in this video?"
"Describe the main objects and people in the scene."
"What activities are taking place?"
```

### Visual Question Answering
```
"What color is the car in the video?"
"How many people are visible in this frame?"
"What text can you read from the signs?"
```

### Contextual Research
```
"Find more information about the technology shown in this video."
"What are the latest developments in this field?"
"Explain the scientific concepts demonstrated here."
```

## 🛠️ Technical Architecture

### Core Technologies
- **Framework**: Agno AI Agent Framework
- **Language Model**: Google Gemini 2.0 Flash
- **Video Processing**: OpenCV and FFmpeg
- **Web Search**: DuckDuckGo integration
- **UI**: Streamlit for user interface
- **Multimodal Processing**: Google's multimodal capabilities

### Processing Pipeline
1. **Video Upload**: User uploads video file
2. **Video Processing**: Video is processed and frames extracted
3. **Visual Analysis**: Gemini analyzes visual content
4. **Text Extraction**: Any text in video is extracted
5. **Web Research**: Relevant web searches are performed
6. **Context Integration**: Visual and web information is combined
7. **Response Generation**: Comprehensive answer is generated

## 📊 Supported Video Types

### Educational Content
- Tutorial videos
- Lecture recordings
- Educational demonstrations
- Scientific experiments

### Business Content
- Product demonstrations
- Marketing videos
- Training materials
- Presentation recordings

### Entertainment Content
- Movie clips
- TV show segments
- Music videos
- Sports highlights

### Technical Content
- Code walkthroughs
- Technical demonstrations
- Software tutorials
- Hardware reviews

## 🔧 Configuration

### Environment Variables
```bash
GOOGLE_API_KEY=your-google-api-key
```

### Customization Options
- **Video Quality**: Adjust processing quality vs speed
- **Frame Rate**: Control frame extraction frequency
- **Search Scope**: Limit web search to specific domains
- **Response Length**: Control answer detail level
- **Language**: Set preferred language for responses

## 📈 Performance Features

- **Efficient Processing**: Optimized video processing pipeline
- **Memory Management**: Handles large video files efficiently
- **Caching**: Intelligent caching for repeated queries
- **Parallel Processing**: Concurrent video and web processing
- **Error Recovery**: Robust error handling and fallback mechanisms

## 🔒 Security & Privacy

- **Data Protection**: Secure handling of video content
- **API Security**: Secure API key management
- **Privacy Compliance**: Follows data privacy best practices
- **Temporary Storage**: Videos are processed and removed

## 🤝 Contributing

We welcome contributions from developers and AI enthusiasts:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

### Areas for Contribution
- Additional video format support
- Improved visual analysis
- Better web search integration
- Enhanced UI/UX
- Performance optimizations

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions:
- Create an issue in the GitHub repository
- Check the documentation
- Review the FAQ section

## 🔮 Roadmap

- [ ] Support for live video streams
- [ ] Audio analysis capabilities
- [ ] Advanced object tracking
- [ ] Real-time video processing
- [ ] Mobile app support
- [ ] Batch video processing
- [ ] Advanced analytics
- [ ] Multi-language support

## 📊 Use Cases

### Content Creation
- Video analysis for content creators
- Automated video descriptions
- Content optimization suggestions
- Trend analysis in video content

### Education
- Interactive video learning
- Automated video summarization
- Educational content analysis
- Student engagement tracking

### Business
- Marketing video analysis
- Product demonstration reviews
- Training material assessment
- Competitive analysis

### Research
- Video data analysis
- Behavioral pattern recognition
- Content trend analysis
- Scientific video documentation

## 🙏 Acknowledgments

- Google for the Gemini 2.0 model
- Agno framework for agent orchestration
- Streamlit for the user interface
- OpenCV for video processing
- DuckDuckGo for web search capabilities

---

**Note**: This application is designed for educational and research purposes. Always ensure you have the right to process and analyze the videos you upload.

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->

<!-- Updated: 2025-09-16 -->
