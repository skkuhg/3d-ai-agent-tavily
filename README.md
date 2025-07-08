# 3D AI Agent - Tavily Assistant

A highly interactive and elegant 3D AI agent powered by Tavily AI that provides intelligent responses with natural speech synthesis and a beautiful 3D interface.

## 🎯 Features

### 🎨 3D Agent Design
- **Realistic Human-like Appearance**: Professionally designed 3D character with natural proportions
- **Expressive Facial Features**: Detailed eyes, eyebrows, and facial expressions that respond to emotions
- **Customizable Appearance**: Multiple skin tones, color themes, and mood settings
- **Professional Clothing**: Sleek, modern outfit with customizable accent colors

### 🎭 Interactive Animations
- **Mood-Based Expressions**: Eyebrow movements and body language that change with personality
- **Natural Movements**: Breathing effects, head tilts, eye movements, and gestures
- **Speaking Animations**: Enhanced hand gestures and facial expressions when talking
- **Idle Behavior**: Subtle floating, swaying, and blinking animations

### 🎛️ Personalization Options
- **Color Themes**: 360° hue adjustment for clothing and accent colors
- **Skin Tone Selection**: 6 different inclusive skin tone options
- **Mood Settings**: 5 personality modes (Happy, Excited, Thoughtful, Neutral, Friendly)
- **Animation Speed**: Adjustable movement speed controls
- **Voice Customization**: Pitch and rate adjustments for speech synthesis

### 🗣️ Voice & Communication
- **Speech Recognition**: Voice input with microphone support
- **Text-to-Speech**: Natural voice synthesis with customizable settings
- **Real-time Responses**: Powered by Tavily AI for intelligent conversations
- **Mood Display**: Visual indicators showing agent's current emotional state

### 🎪 Enhanced UI/UX
- **Glassmorphism Design**: Modern interface with blur effects and transparency
- **Smooth Animations**: Fluid transitions and hover effects throughout
- **Interactive Camera**: Mouse-controlled camera movement for dynamic viewing
- **Responsive Layout**: Works across different screen sizes and devices

## 🚀 Getting Started

### Prerequisites
- A modern web browser with WebGL support
- Tavily AI API key (get yours at [tavily.com](https://tavily.com/))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/skkuhg/3d-ai-agent-tavily.git
   cd 3d-ai-agent-tavily
   ```

2. **Set up your API key**
   - Copy `.env.example` to `.env`
   - Add your Tavily API key to the `.env` file:
     ```
     TAVILY_API_KEY=your_actual_api_key_here
     ```

3. **For local development, modify the HTML file**
   - Open `index.html` in your text editor
   - Replace `YOUR_TAVILY_API_KEY_HERE` with your actual API key
   - Or set up a local server to handle environment variables

4. **Run the application**
   - Open `index.html` in your web browser
   - Or serve it through a local web server for better performance

## 🎮 Usage

### Basic Interaction
1. **Text Chat**: Type your questions in the input field and press Enter or click Send
2. **Voice Input**: Click the microphone button to speak your questions
3. **Customization**: Use the settings panel (⚙️) to personalize your agent

### Settings Panel
- **Agent Color Theme**: Adjust the hue slider to change clothing and accent colors
- **Animation Speed**: Control how fast the agent moves and gestures
- **Voice Settings**: Customize pitch and rate for speech synthesis
- **Skin Tone**: Choose from 6 different skin tone options
- **Agent Mood**: Select personality mode to change behavior and expressions

### Voice Features
- **Speech Recognition**: Works in supported browsers (Chrome, Edge, Safari)
- **Text-to-Speech**: Automatic voice responses with customizable settings
- **Voice Controls**: Click and hold microphone button to speak

## 🛠️ Technical Details

### Technologies Used
- **Three.js**: 3D graphics and animation
- **Tavily AI API**: Intelligent search and response generation
- **Web Speech API**: Voice recognition and synthesis
- **CSS3**: Modern styling with glassmorphism effects
- **HTML5**: Semantic markup and accessibility

### 3D Rendering Features
- **Advanced Lighting**: Multiple light sources with rim lighting effects
- **Shadow Mapping**: Realistic shadows and depth
- **Particle Effects**: Animated background particles
- **Material Shading**: Phong shading with specular highlights
- **Anti-aliasing**: Smooth edges and high-quality rendering

### Performance Optimizations
- **Efficient Animation**: Optimized animation loops
- **Geometry Instancing**: Reused geometries for better performance
- **Texture Optimization**: Efficient material usage
- **Responsive Rendering**: Adaptive quality based on device capabilities

## 🔐 Security

### API Key Protection
- Never commit your actual API key to version control
- Use environment variables for API key storage
- The `.env` file is included in `.gitignore`
- Follow the `.env.example` template for setup

### Best Practices
- Keep your API key secure and private
- Regularly rotate your API keys
- Use environment variables in production
- Monitor your API usage on the Tavily dashboard

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Tavily AI** for providing the intelligent search API
- **Three.js** community for the amazing 3D graphics library
- **Web Speech API** for voice recognition and synthesis capabilities
- Modern web browsers for supporting advanced web technologies

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/skkuhg/3d-ai-agent-tavily/issues) page
2. Create a new issue with detailed information
3. Include browser version, error messages, and steps to reproduce

## 🚀 Future Enhancements

- [ ] Multi-language support
- [ ] Custom avatar uploads
- [ ] Advanced gesture recognition
- [ ] Integration with other AI services
- [ ] Mobile app version
- [ ] Voice command shortcuts
- [ ] Advanced personality customization
- [ ] Real-time collaboration features

---

**Made with ❤️ and powered by Tavily AI**