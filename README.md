# AI Image Generator - Pollinations (BYOP)

A clean, user-friendly web application for generating AI images using the Pollinations AI with **Bring Your Own Pollen (BYOP)** support. Users bring their own API keys and only pay for what they generate - no subscriptions, no hidden fees!

**🌟 Key Benefit: Zero cost to app developer - users pay for their own usage with their Pollinations API keys.**

## ✨ Features

- **BYOP (Bring Your Own Pollen)** - Users use their own API keys, you pay $0 as the developer
- **Simple Interface** - Clean, intuitive design that anyone can use
- **Multiple AI Models** - Choose from Flux, Flux Realism, Flux Anime, Flux 3D, Turbo, GPT Image, and Seedream
- **Flexible Sizing** - Generate images in various aspect ratios (Square, Landscape, Portrait, Wide)
- **Secure Key Storage** - API keys stored locally in browser (never sent to any server except Pollinations)
- **Quick Examples** - Pre-loaded prompts to inspire creativity
- **Easy Download** - Download generated images with one click
- **URL Sharing** - Copy image URLs to share your creations
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **No Setup Required** - Just open and start creating

## 🚀 Live Demo

[View Live App](#) *(Add your deployed URL here)*

## 🚀 How to Use

1. **Get Your API Key**: Sign up at [enter.pollinations.ai](https://enter.pollinations.ai) to get your free API key (starts with `pk_` or `sk_`)
2. **Enter API Key**: Paste your API key in the app and click "Save Key" (stored locally in your browser)
3. **Describe Your Image**: Enter a detailed text description of what you want to create
4. **Choose Settings**: Select your preferred AI model and image size
5. **Generate**: Click the "Generate Image" button
6. **Download or Share**: Save your creation or copy the URL to share

### Why BYOP?

- **You control costs** - Only pay for what you generate with your own API key
- **No subscriptions** - Pay-as-you-go model, $1 ≈ 1 Pollen
- **Free daily credits** - Get free daily Pollen based on your tier
- **Privacy** - Your API key stays in your browser, never stored on any server

### Example Prompts

- "A futuristic city with flying cars at night, neon lights, cyberpunk style"
- "A cute robot gardener tending to colorful flowers in a sunny garden"
- "Abstract art with vibrant colors, geometric shapes, modern style"
- "A magical forest with glowing mushrooms and fireflies, fantasy illustration"

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **API**: Pollinations AI Generation API (`https://gen.pollinations.ai`)
- **Authentication**: Bearer token (API key)
- **Design**: Modern gradient UI with responsive layout
- **Storage**: LocalStorage for API key persistence

## 📦 Installation

No installation required! Simply:

1. Download the `pollinations-image-generator.html` file
2. Open it in any modern web browser
3. Start generating images

### For Developers

If you want to host this application:

```bash
# Clone the repository
git clone https://github.com/moh65-debug/pollinations-image-generator.git

# Navigate to the directory
cd pollinations-image-generator

# Open with a local server (or just open the HTML file)
# Using Python 3:
python -m http.server 8000

# Using Node.js http-server:
npx http-server
```

## 🎯 Available AI Models

- **Flux** (Default) - Balanced quality and speed
- **ZImage** - High-quality generation
- **Flux 2 Dev** - Latest Flux development model
- **GPT Image** - OpenAI-style generation
- **GPT Image Large** - Larger OpenAI-style model
- **Seedream 5** - Latest Seedream version
- **Seedream / Seedream Pro** - Creative generation models
- **Nanobanana / Nanobanana 2 / Nanobanana Pro** - Fast generation series
- **Klein** - Specialized model
- **Kontext** - Context-aware generation
- **Imagen 4** - Google's image model
- **Grok Imagine** - X.AI's image model

## 🛠️ Advanced Features

- **Seed Control** - Generate reproducible images with seed values
- **Prompt Enhancement** - Let AI improve your prompts automatically
- **Negative Prompts** - Specify what to avoid in generations (Flux & ZImage)
- **Safety Filters** - Optional content filtering
- **Multiple Sizes** - From 512×512 to 1920×1080

## 📐 Image Sizes

- Square: 1024x1024
- Landscape: 1280x720
- Portrait: 720x1280
- Wide: 1920x1080

## 🌟 Key Features Explained

### Clean Interface
The app features a modern, gradient-based design that's easy on the eyes and simple to navigate. No clutter, no confusion.

### Instant Generation
Images are generated in real-time using the Pollinations API. No waiting, no queuing.

### Example Prompts
Click any example chip to instantly populate the prompt field and see what's possible.

### Keyboard Shortcuts
Press `Ctrl + Enter` in the prompt field to quickly generate an image.

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Credits

This app is built with [**Pollinations.ai**](https://pollinations.ai/)

<p align="center">
  <a href="https://pollinations.ai">
    <img src="https://pollinations.ai/logo-white.svg" alt="Pollinations.ai Logo" height="60">
  </a>
</p>

<p align="center">
  <a href="https://pollinations.ai">
    <img src="https://img.shields.io/badge/Built%20With-pollinations.ai-purple?style=for-the-badge" alt="Built with Pollinations.ai">
  </a>
</p>

Powered by [Pollinations AI](https://pollinations.ai/) - Built with ❤️ for the creative community

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check the Pollinations AI documentation

## 🔮 Future Enhancements

- [ ] Image history/gallery
- [ ] Advanced parameters (seed, steps, guidance)
- [ ] Batch generation
- [ ] Style presets
- [ ] Image-to-image generation
- [ ] Negative prompts
- [ ] In-browser image editing

---

<p align="center">
  <strong>Made with Pollinations AI</strong><br>
  <a href="https://github.com/yourusername/pollinations-image-generator/issues">Report Issue</a> • 
  <a href="https://github.com/yourusername/pollinations-image-generator">Star on GitHub</a>
</p>

<p align="center">
  <a href="https://pollinations.ai">
    <img src="https://img.shields.io/badge/Built%20With-pollinations.ai-purple?style=flat-square" alt="Built with Pollinations.ai">
  </a>
</p>
