# CYRA-app
Create Your Reality Agent - App - v1 prototype
### installfest
* Initial prototype with Llama, Oolama. Later version with ChatGPT o3 and Operator.
* Using iOS with simulator storing task created by user speech input, converted to text (JSON for web app, native iOS eventual macOS and VisionOS app UI with storable text that is saved in Apple Private Cloud via CloudKit). 
* This is then integrated with Instacart to test out performance abilities using Playwright to see if an AI agent is able to handle storing a log of a task, completing a task and switching to another web application.
### To-Do List



# To-Do List v1 - iOS 

| Initial Setup | Basic Cross-Platform Setup | Configuration and GenAI Magic |
| :------------ | :------------------------- | :---------------------------- |
| - ✅ Evaluated VisionOS CoreML feature | - [ ] - [ ] Create rest of CalendarKit for logging task times with prettier UI
| [ ] Implement PDF generation - PDFKit | - [ ] Configure speech-to-text Whisper: local transcription, create 5s audio script |
| - ✅ Installfest Python latest, Ollama, Llama, Flask, transformers, Torch, Playwright (Instacart API) | - [ ] Implement ReactJS web app creation with TailwindCSS |
| - 🔲 Use Flask API. Check AVFoundation documentation to send to API |
| - ✅ Create initial GH Repo | - [ ] Create shared JSON schema for cross-platform compatibility | - [ ] Record audio and send to API for storage |
| - [ ] Set up Xcode project with Whisper/ChatGPT 4.1 API integration | | - [ ] Generate tasks with Llama |
| | | - [ ] Build UITableView in Storyboard (match old wireframe), add button to trigger speech recording |
| | | - [ ] Enable CloudKit container - CKRecord |
| | Integration Playwright: | [ ] Submit request for ask Apple Dev during office hours for entitlements; handwriting recognizer with MNIST; passthrough camera frame  |

# To-Do List v2 - MacOS and VisionOS - Phase 3

| Initial Setup | Basic Cross-Platform Setup | Configuration and GenAI Magic |
| :Check documentation for cross-platform setup and install VisionOS3 (currently on VisionOS2) | :------------------------- | :---------------------------- |

- [ ] Implement in VisionOS 
- [ ] Setup other integration with Playwright (Instacart) using OpenAI Operator
  
- [ ] Generate tasks with ChatGPT4.1
- [ ] Build UITableView in Storyboard - make sure it matches old wireframe. Add button to trigger speech recording. 
- [ ] - [ ] Enable CloudKit container - CKRecord
- [ ] Integration Playwright
- [ ] 
#### Other UI 
- [ ] Create rest of CalendarKit for logging task times with prettier UI
- [ ] Execute build of data input, UI creation, storage to run in Simulator

Validate build 
- [ ] Record simulator demo



- [x] Research Benchmark (OSWorld, DeepEval integration with LlamaIndex for Computer Use) 
- [ ] Run Benchmark analysis for multiple apps - creation of multiple to-do list items and integration across 20 different intergrations already in use for OpenAI to store log of data into productivity app
