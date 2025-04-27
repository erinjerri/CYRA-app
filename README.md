# CYRA-app
Create Your Reality Agent - App - v1 prototype
### installfest
* Initial prototype with Llama, Oolama. Later version with ChatGPT o3 and Operator.
* Using iOS with simulator storing task created by user speech input, converted to text (JSON for web app, native iOS eventual macOS and VisionOS app UI with storable text that is saved in Apple Private Cloud via CloudKit). 
* This is then integrated with Instacart to test out performance abilities using Playwright to see if an AI agent is able to handle storing a log of a task, completing a task and switching to another web application.
### To-Do List



# Reformatted To-Do List

| Initial Setup | Basic Cross-Platform Setup | Configuration and GenAI Magic |
| :------------ | :------------------------- | :---------------------------- |
| - [x] Evaluated VisionOS CoreML feature | - [ ] Implement PDF generation - PDFKit | - [ ] Configure speech-to-text Whisper: local transcription, create 5s audio script |
| - [ ] Installfest Python latest, Ollama, Llama, Flask, transformers, Torch, Playwright (Instacart API) | - [ ] Implement ReactJS web app creation with TailwindCSS | - [ ] Use Flask API. Check AVFoundation documentation to send to API |

| - [ ] Create initial GH Repo | - [ ] Create shared JSON schema for cross-platform compatibility | - [ ] Record audio and send to API for storage |

| - [ ] Set up Xcode project with Whisper/ChatGPT 4.1 API integration | | - [ ] Generate tasks with Llama |



| | | - [ ] Build UITableView in Storyboard (match old wireframe), add button to trigger speech recording |
| | | - [ ] Enable CloudKit container - CKRecord |
| | Integration Playwright: | [ ] Submit request for ask Apple Dev during office hours for entitlements; handwriting recognizer with MNIST; passthrough camera frame  |



#### Initial Setup 
- [x] Evaluated VisionOS CoreML feature I need to ask an Apple Developer during office hours to provide entitlements (get handwriting recognizer to work with MNIST dataset and get entitlements for passthrough camera frames)
- [x] Installfest Python latest, Ollama, Llama, Flask, transformers and other Python Frameworks plus Torch, Playwright (Instacart API)
- [ ] Create initial GH Repo
- [ ] Set up Xcode project with Whisper/ChatGPT 4.1 API integration

### Basic cross-platform setup

- [ ] Implement PDF generation - PDFKit
- [ ] Implement ReactJS web app creation with TailwindCSS
- [ ] Create shared JSON schema for cross-platform compatibility

#### Configuration and GenAI Magic
- [ ] Configure speech-to-text Whisper - local transcription, create python script for 5sec audio. 
- [ ] Use Flask API. Check AVFoundation still current documentation to send to API. 
- [ ] Record audio and send to API for storage.
- [ ] Generate tasks with Llama
- [ ] Build UITableView in Storyboard - make sure it matches old wireframe. Add button to trigger speech recording. 
- [ ] - [ ] Enable CloudKit container - CKRecord
- [ ] Integration Playwright
- [ ] 
#### Other UI 
- [ ] Create rest of CalendarKit for logging task times with prettier UI
- [ ] Execute build of data input, UI creation, storage to run in Simulator

Validate build 
- [ ] Record simulator demo

Phase 3
- [ ] Implement in VisionOS 
- [ ] Setup other integration with Playwright (Instacart) using OpenAI Operator

- [x] Research Benchmark (OSWorld, DeepEval integration with LlamaIndex for Computer Use) 
- [ ] Run Benchmark analysis for multiple apps - creation of multiple to-do list items and integration across 20 different intergrations already in use for OpenAI to store log of data into productivity app
