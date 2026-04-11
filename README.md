# GraspAI Chat

**GraspAI Chat** is a native iOS client for AWS Bedrock that puts the full power of enterprise AI in your pocket. Connect directly to your own AWS account and chat with the world's leading AI models through a fast, clean, and familiar mobile interface.

Unlike consumer AI apps, GraspAI Chat connects to your own AWS infrastructure. Your conversations stay in your account, your costs stay under your control, and you choose which models you use.

Available on the [App Store](https://apps.apple.com).

---

## Features

### AI Chat
- Real-time streaming responses as they generate
- Multi-turn conversations with full context preservation
- DeepSeek R1 chain-of-thought reasoning display
- Stop generation mid-stream
- Markdown rendering with syntax highlighting for Swift, Python, JavaScript, JSON, and Bash

### Supported Models
| Provider | Models |
|----------|--------|
| Anthropic | Claude Sonnet 4.6, Claude Opus 4.6, Claude Sonnet 4.5, Claude Opus 4.5, Claude Haiku 4.5 |
| Amazon | Nova Micro, Nova Lite, Nova Pro, Nova Premier, Nova 2 Lite |
| DeepSeek | DeepSeek R1, DeepSeek V3.2 |
| Meta | Llama 3.1 70B, Llama 3.1 8B |
| AI21 Labs | Jamba 1.5 Large, Jamba 1.5 Mini |

### Image Generation
- Generate images with Nova Canvas and Stability AI models
- Multiple sizes, quality options, and style presets
- Reference image support for variations
- Smart iteration detection — say "make it darker" or "add a sunset"
- Auto-context retention uses your last generated image as a reference
- Save directly to your photo library or share

### Vision / Image Input
- Attach photos from your camera or photo library
- Supported on Claude 4.x and Nova Lite, Pro, Premier, and 2 Lite
- Analyze diagrams, screenshots, documents, and more

### Web & Search
- Automatic web search for news and current events queries
- URL detection with one-tap content extraction
- Smart search detection auto-enabled with the Precise preset

### Conversation Management
- Multiple persistent conversations
- Auto-generated titles from the first message
- Star important conversations (swipe left-to-right)
- Delete conversations (swipe right-to-left)
- Message selection, bulk delete, and select all
- AI-powered conversation export

### Configuration
- Three authentication methods: IAM Access Keys, Long-term API Key, or Cognito Federated Sign-In
- Three presets: Creative, Balanced, and Precise
- Adjustable temperature, max tokens, and system prompt
- Global and regional inference profile preference for cost and compliance optimization
- Streaming toggle per session

### AgentCore Gateway (MCP)
- Connect to AWS Bedrock AgentCore Gateway
- Dynamic tool discovery via MCP protocol
- Tool invocation with AWS Signature V4 authentication
- Automatic tool use in chat — the model decides when to call tools

### Enterprise / MDM
- Apple Managed App Configuration support
- IT admins can lock settings, enforce model allowlists, and pre-configure credentials via MDM
- Lockable settings include: region, credential type, model selection, allowed models, streaming, gateway config, Cognito config, image models, and auto-save to photos
- Lock indicators shown in the UI for MDM-managed fields
- MDM configuration merges with user config — credentials always remain with the user

### Security
- Credentials stored securely in iOS Keychain
- Images persisted to the device Documents directory with in-memory cache
- Conversation history stored locally on device

---

## Requirements

- iOS 16.0 or later
- iPhone or iPad
- An AWS account with access to AWS Bedrock
- AWS Bedrock model access enabled for your desired models

---

## Authentication Options

**IAM Access Keys** — Use your AWS Access Key ID and Secret Access Key. Recommended for individual developers.

**Long-term API Key** — Use a Bedrock long-term API key. Easiest setup for exploration.

**Cognito Federated Sign-In** — Sign in with email and password via Amazon Cognito. Recommended for enterprise deployments.

---

## Subscription

GraspAI Chat is free to download. A **GraspAI Pro** subscription unlocks unlimited use of the app.

- Monthly: $3.99/month
- Yearly: $39.99/year (save ~17%)
- Lifetime: one-time purchase

AWS usage costs apply separately based on your AWS account pricing.

---

## Support

For support, feature requests, or bug reports, please [open an issue](https://github.com/graspaichat/GraspAI-Chat/issues) or contact us at grasp-ios-app@proton.me.

## Privacy Policy

See [PRIVACY_POLICY.md](./PRIVACY_POLICY.md).
