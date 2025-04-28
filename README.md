# CYRA-app
Create Your Reality Agent - App - v1 prototype

### Overview
* Initial prototype with Llama, Oolama. Later version with ChatGPT o3 and Operator. Built for UC Berkeley LLM Agents (Advanced) course, after a hackathon last year (VisionDevCamp winning Best Productivity app for app concept) and undergoing Women in Big Data solopreneurship program. This project actually tries to build a real prototype with real data
* Using iOS with simulator storing task created by user speech input, converted to text (JSON for web app, native iOS eventual macOS and VisionOS app UI with storable text that is saved in Apple Private Cloud via CloudKit). 
* This is then integrated with Instacart to test out performance abilities using Playwright to see if an AI agent is able to handle storing a log of a task, completing a task and switching to another web application.
### To-Do List

# updated To-Do Listv1 - iOS
| Initial Setup | Basic Cross-Platform Setup | Configuration and GenAI Magic | Testing/Benchmarking |
| :------------ | :------------------------- | :---------------------------- | :------------------ |
| - 1 ✅ Evaluated VisionOS CoreML feature |  - ✅ Create basic pdf layout in sketch that I will translate into SVG/JSON and then Storyboard and in XCode basic | 🔲 Configure speech-to-text Whisper: local transcription, create 5s audio script | - ✅ Research Benchmark (OSWorld, DeepEval integration with LlamaIndex for Computer Use) |
| - 2 ✅ Installfest Python latest, Ollama, Llama, Flask, transformers, Torch, Playwright (Instacart API)  | 🔲 Check if this would work in MacOS and visionOS - research documentation | 🔲 Record audio and send to API for storage |🔲 Execute build of data input, UI creation, storage to run in Simulator | 
| - 3 🔲 Configure Langchain, Langgraph, langsmith, LlamaIndex (DeepEval), honeyhive, tavily API, vellum optional.  | - 🔲 create structure with CalendarKit for logging task times with prettier UI | Use ChatGPT to create rest of UI based on SVG and JSON I created from Sketch/Figma/Storyboard for storage that would work on iOS and MacOS | - 🔲 Run Benchmark analysis for multiple apps - creation of multiple to-do list items and integration across 20 different integrations already in use for OpenAI to store log of data into productivity app | 🔲 stuff | - 🔲 Implement ReactJS web app creation with TailwindCSS | [ ] Implement PDF generation - PDFKit | |
| - 4 🔲 Use Flask API. Check AVFoundation documentation to send to API | 🔲 do more cross platform stuff   | 🔲 iterate genAI | 🔲 test | 🔲 test
| - 5 ✅ Create initial GH Repo | - 🔲 Create shared JSON schema for cross-platform compatibility | - 🔲 test storage in web, MacOS  | 🔲   |
| - 6 🔲 Set up Xcode project with Whisper/ChatGPT 4.1 API integration | more cross-platform stuff | - 🔲 Generate tasks with Llama | 🔲  stuff | 🔲 stuff
| - 7 🔲 | 🔲  |  🔲 Build UITableView in Storyboard (match old wireframe), add button to trigger speech recording | 🔲 stuff | 🔲 stuff 
| -8 🔲 | 🔲 | 🔲 Enable CloudKit container - CKRecord | stuff| stuff
| -9 🔲 | 🔲 Read ChatGPT4.1 (Operator documentation) with Instacart Playwright API  | 3 🔲 Submit request for ask Apple Dev during office hours for entitlements; handwriting recognizer with MNIST; passthrough camera frame | 4 🔲 research papers one more time for other CUA benchmarks | 5 🔲 ask GSIs if there are other benchmarks I need to hit. 

# To-Do List v2 - MacOS and VisionOS - Phase 3
### This is when we can get entitlments for VisionOS and if not iOS as an app (if we have time), we create a MacOS version to store data with Cloud Kit for Apple Private Cloud.

| Initial Setup                                                                                                  | Basic Cross-Platform Setup                                      | Configuration and GenAI Magic                                                      | Testing and Benchmarking |
|:---------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------|:-----------------------------------------------------------------------------------|:--------------------------|
| - 🔲 1  Check documentation for cross-platform setup and install VisionOS3 (currently on VisionOS2)             | - 🔲 Add button to trigger speech recording                    | - 🔲 Test that data renders in CloudKit on VisionOS                                        | Validate build and record simulator demo      |
| - 🔲 2 Integration Playwright |                                                                                    | - 🔲 Run in simulator                                                     | - 🔲 Stuff stuff                                                                   | - 🔲 Research Benchmark (OSWorld, DeepEval integration with LlamaIndex for Computer Use) | 
| - 🔲 3 See what works for VisionOS with CalendarKit and other SwiftUI components and what has to be uniquely customized | 🔲 Check if this would be compatible on MacOS |  - 🔲 test computer vision capture with CoreML on VisionOS |