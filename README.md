# AI Course Prompt Repository

Welcome to the official prompt repository for the course. This `README.md` contains the core templates and examples used throughout the lectures to communicate effectively with AI tools like ChatGPT, Gemini, and GitHub Copilot. 

Use these examples as a foundation for your own projects, automating tasks, and writing code.

---

## 📚 Prompt Examples

### 1. Detailed Prompt
Use this structured framework to generate highly specific, formatted schedules or plans.

> **[Context/Role]:** Act as an expert study coach specialising in ADHD and fast-paced learning. 
> **[Task]:** Create a 3-day cramming schedule for a high school biology final. 
> **[Constraints]:** Incorporate the Pomodoro technique. Include 15-minute mandatory outdoor screen-free breaks. 
> **[Format]:** Output the schedule as a highly visual Markdown table.

### 2. Analysing a Video
Use this prompt to extract actionable insights from long-form video content without settling for a generic summary.

> Analyse this video https://www.youtube.com/watch?v=o4PbCF2yQb4. Do not give me a generic summary. Instead, extract the 3 most important takeaways, provide a bulleted list of actionable steps I can apply immediately, and highlight one surprising or unconventional point the speaker made. Format this as a bolded, quick-read cheat sheet.

### 3. Hustle Partner
Use this framework to brainstorm creative content strategies with the AI acting as your specialized marketing expert.

> **[Role]:** Act as a viral content strategist and Gen-Z marketing expert. 
> **[Context]:** I have zero budget and want to start a TikTok channel focused on cheap, tech-focused desk setups. 
> **[Task]:** Give me 5 scroll-stopping hook ideas for my first few videos that trigger immediate curiosity. 
> **[Format]:** Output a table with three columns: 'The Hook (First 3 Seconds)', 'The Visual Action', and 'Why it works'.

### 4. App Creation
Use this strict prompt to guide an AI in writing modular, best-practice code for application development.

> **Role:** Act as a Senior Flutter Developer. 
> **Task:** Generate a complete, multi-file Flutter widget for a modern, dark-mode Pomodoro timer. Add a button at the bottom of the page to allow the user to add tasks. Save tasks locally so next time the App is open, it can load the previous tasks. When adding a task, the user should be able to choose the time. Allow a five-minute break between tasks. Play a short chime when the timer is up. 
> **STRICT RULE:** Follow Flutter best practices. Only use the packages that are well-maintained and being updated. Keep different functionality in separate files. Keep the file size limited to maintain readability. Use sensible variable names and function names that explain the application.

### 5. Debugging
Use this template to troubleshoot code crashes while enforcing your project's specific syntax rules.

> **[Context]:** I just ran the app, and when I click the 'Start' button on the Pomodoro timer, the app crashes and throws this error: [Paste your stack trace/error message here] 
> **[Task]:** Explain exactly why this crashed in one simple sentence. Then, provide the corrected function. 
> **[Constraint]:** Remember our strict project rule: all variables must be declared at the very start of the function, with no declarations inside internal blocks.

### 6. Understanding the Code
Use this prompt to force the AI to explain complex logic conceptually using analogies, rather than outputting more confusing code.

> **[Task]:** I don't understand the state management logic you used to make the timer update on the screen. 
> **[Constraint]:** Do not show me any more code. Break down how this works using a simple, real-world analogy (like a manager assigning tasks to workers or a restaurant kitchen). Keep it under one paragraph.

---

## 🛠️ Resources

### Installing VS Code and Flutter
To set up your development environment for the App Creation section, refer to the official documentation:
* [Flutter Installation Guide for VS Code](https://docs.flutter.dev/install/with-vs-code)


# About us
Visit us at [CosmoRobotics](https://cosmorobotics.uk/learning/)