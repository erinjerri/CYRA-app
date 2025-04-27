# CYRA-app
Create Your Reality Agent - App - v1 prototype

### Overview
* Initial prototype with Llama, Oolama. Later version with ChatGPT o3 and Operator. Built for UC Berkeley LLM Agents (Advanced) course, after a hackathon last year (VisionDevCamp winning Best Productivity app for app concept) and undergoing Women in Big Data solopreneurship program. This project actually tries to build a real prototype with real data though.
* Using iOS with simulator storing task created by user speech input, converted to text (JSON for web app, native iOS eventual macOS and VisionOS app UI with storable text that is saved in Apple Private Cloud via CloudKit). 
* This is then integrated with Instacart to test out performance abilities using Playwright to see if an AI agent is able to handle storing a log of a task, completing a task and switching to another web application.
### To-Do List

# updated To-Do Listv1 - iOS
| Initial Setup | Basic Cross-Platform Setup | Configuration and GenAI Magic | Testing/Benchmarking |
| :------------ | :------------------------- | :---------------------------- | :------------------ |
| - ✅ Evaluated VisionOS CoreML feature | - 🔲 Create rest of CalendarKit for logging task times with prettier UI | | - ✅ Research Benchmark (OSWorld, DeepEval integration with LlamaIndex for Computer Use) |
| - [ ] Implement PDF generation - PDFKit | - [ ] Configure speech-to-text Whisper: local transcription, create 5s audio script | | - 🔲 Run Benchmark analysis for multiple apps - creation of multiple to-do list items and integration across 20 different integrations already in use for OpenAI to store log of data into productivity app |
| - ✅ Installfest Python latest, Ollama, Llama, Flask, transformers, Torch, Playwright (Instacart API) | - 🔲 Implement ReactJS web app creation with TailwindCSS | | |
| - 🔲 Use Flask API. Check AVFoundation documentation to send to API | | | |
| - ✅ Create initial GH Repo | - 🔲 Create shared JSON schema for cross-platform compatibility | - 🔲 Record audio and send to API for storage | |
| - 🔲 Set up Xcode project with Whisper/ChatGPT 4.1 API integration | | - 🔲 Generate tasks with Llama | |
| | | - 🔲 Build UITableView in Storyboard (match old wireframe), add button to trigger speech recording | |
| | | - 🔲 Enable CloudKit container - CKRecord | |
| | Read ChatGPT4.1 (Operator documentation) with Instacart Playwright API  | 🔲 Submit request for ask Apple Dev during office hours for entitlements; handwriting recognizer with MNIST; passthrough camera frame | |

# To-Do List v2 - MacOS and VisionOS - Phase 3
### This is when we can get entitlments for VisionOS and if not iOS as an app (if we have time), we create a MacOS version to store data with Cloud Kit for Apple Private Cloud.

| Initial Setup                                                                                                  | Basic Cross-Platform Setup                                      | Configuration and GenAI Magic                                                      | Testing and Benchmarking |
|:---------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------|:-----------------------------------------------------------------------------------|:--------------------------|
| - 🔲 Check documentation for cross-platform setup and install VisionOS3 (currently on VisionOS2)             | - 🔲 Add button to trigger speech recording                    | - 🔲 Enable CloudKit container - CKRecord                                           | Validate build and record simulator demo      |
| - 🔲 Integration Playwright |                                                                                    | - 🔲 Stuff                                                     | - 🔲 Stuff stuff                                                                   | - 🔲 Research Benchmark (OSWorld, DeepEval integration with LlamaIndex for Computer Use) | 
| - 🔲 Create rest of CalendarKit for logging task times with prettier UI | 🔲 Execute build of data input, UI creation, storage to run in Simulator |  - 🔲 Run Benchmark analysis for multiple apps - creation of multiple to-do list items and integration across 20 different integrations already in use for OpenAI to store log of data into productivity app |