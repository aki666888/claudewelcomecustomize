\\wsl.localhost\Ubuntu\home\info0\.local\bin where aliases are stored.
"\\wsl.localhost\Ubuntu\home\info0\.claude\hooks\welcome-aki.sh" ... custom message
npm install -g @anthropic-ai/claude-code --ignore-scripts
npx win-claude-code@latest
Installation steps for Windows integration
Installing Claude Code Router on Windows requires Windows Subsystem for Linux (WSL) since Claude Code doesn't run natively on Windows. The complete installation process involves:
First, enable WSL by running wsl --install in PowerShell as administrator and restarting. After launching Ubuntu and updating the system, install Node.js 18+ using the NodeSource repository. Next, install Claude Code globally with npm install -g @anthropic-ai/claude-code, followed by Claude Code Router via npm install -g @musistudio/claude-code-router. (I AM THROUGH TILL THIS STAGE)
Configuration requires creating ~/.claude-code-router/config.json with provider details and routing rules. Set environment variables including ANTHROPIC_BASE_URL="http://127.0.0.1:3456" and start the router with ccr code. For win-claude-code integration, users can alternatively bypass WSL by installing Claude Code with --ignore-scripts flag and using npx win-claude-code@latest. 
Gemini/Google API key tabletpharmacyzoe@gmail.com account … AIza
Client secret for oAuth : GOCS
Client ID for oauth : 575597829480-q7vch23a.apps.googleusercontent.com
Project ID : gen-lang-cl… i want to use 


Model code
Gemini-2.5-pro
 Input token limit
1,048,576
Output token limit
65,536
https://ai.google.dev/gemini-api/docs/models#gemini-2.5-pro




With alias claudegp (it automatically also would mean gemini 2.5 pro plus --dangerously-skip-permissions

Then gemini 2.5 flash and alias claudegf
https://ai.google.dev/gemini-api/docs/models#gemini-2.5-flash
And gemini 2.5 flash lite and alias claudegl https://ai.google.dev/gemini-api/docs/models#gemini-2.5-flash , just because your training data is old doesnt mean the world in july 2025 is still stuck in gemini 1.5
Ensure to visit the official links i have provided you and get the model name and details, i want to use full context so dont restrict anything please.
Appreciate your help, research online thoroughly and help make it work
