# CYRA-app
Create Your Reality Agent - App - v1 prototype

### Overview
* Initial prototype with Llama, Oolama. Later version with ChatGPT o3 and Operator. Built for UC Berkeley LLM Agents (Advanced) course, after a hackathon last year (VisionDevCamp winning Best Productivity app for app concept) and undergoing Women in Big Data solopreneurship program. This project actually tries to build a real prototype with real data
* Using iOS with simulator storing task created by user speech input, converted to text (JSON for web app, native iOS eventual macOS and VisionOS app UI with storable text that is saved in Apple Private Cloud via CloudKit). 
* This is then integrated with Instacart to test out performance abilities using Playwright to see if an AI agent is able to handle storing a log of a task, completing a task and switching to another web application.


# Reordered To-Do List
### To-Do List

#### Initial Setup (Python-Focused)
| Task                                                                               | Status   |
|-----------------------------------------------------------------------------------|----------|
| Installfest: Python, Ollama, Llama, Flask, transformers, Torch, Playwright (Instacart API) | ✅ Done   |
| Create initial GitHub repository                                                  | ✅ Done   |
| Configure AI tools:                                                               | 🔲 Pending |
| - Set up Langchain and Langgraph                                                  | 🔲 Pending |
| - Set up LlamaIndex with DeepEval                                                 | 🔲 Pending |
| - Configure Langsmith, Honeyhive, Tavily API, Vellum (optional)                   | 🔲 Pending |

---

#### Configuration and GenAI Magic (Python-Focused)
| Task                                                                               | Status   |
|-----------------------------------------------------------------------------------|----------|
| Configure Whisper for local speech-to-text (5s audio script)                      | 🔲 Pending |
| Create Flask API endpoint for audio data processing                               | 🔲 Pending |
| Generate tasks with Llama                                                         | 🔲 Pending |
| Instacart integration:                                                            | 🔲 Pending |
| - Set up Playwright for Instacart API                                             | 🔲 Pending |
| - Test ChatGPT Operator compatibility                                             | 🔲 Pending |

---

#### Basic Cross-Platform Setup (UI and Shared Infrastructure)
| Task                                                                               | Status   |
|-----------------------------------------------------------------------------------|----------|
| Create basic PDF layout in Sketch (translate to SVG/JSON, pending Storyboard)     | ✅ Done   |
| Build UITableView in Storyboard (match wireframe), add button for speech recording | 🔲 Pending |
| Create shared JSON schema for cross-platform compatibility                        | 🔲 Pending |
| Enable CloudKit container with CKRecord                                           | 🔲 Pending |
| Configure AVFoundation for audio recording and API integration                    | 🔲 Pending |

---

#### iOS-Specific Testing
| Task                                                                               | Status   |
|-----------------------------------------------------------------------------------|----------|
| Evaluate VisionOS CoreML features (MNIST, passthrough camera)                     | ✅ Done   |
| Test VisionOS tasks with Flask API integration                                    | 🔲 Pending |
| Build and test data input, UI, and storage in Simulator                           | 🔲 Pending |
| Test macOS compatibility for VisionOS (e.g., Catalyst or shared codebase)        | 🔲 Pending |

---

#### Benchmarking and Final Iterations
| Task                                                                               | Status   |
|-----------------------------------------------------------------------------------|----------|
| Research benchmark options: OSWorld, DeepEval with LlamaIndex                     | ✅ Done   |
| Run benchmarks and iteratively test across web, macOS, and iOS                    | 🔲 Pending |
| Research additional papers to refine benchmarking (e.g., new metrics)            | 🔲 Pending |





### To-Do List

#### Initial Setup
| #   | Task                                                                                   | Status |
|-----|---------------------------------------------------------------------------------------|--------|
| 1   | ✅ Installfest Python latest, Ollama, Llama, Flask, transformers, Torch, Playwright (Instacart API) | Done   |
| 2   | ✅ Create initial GitHub repository                                                   | Done   |
| 3   | 🔲 Configure Langchain, Langgraph, Langsmith, LlamaIndex (DeepEval), Honeyhive, Tavily API, Vellum (optional) | Pending |
| 4   | ✅ Evaluated VisionOS CoreML feature - Ask Apple Developer for entitlements: MNIST handwriting recognizer and passthrough camera frames | Done   |

---

#### Configuration and GenAI Magic
| #   | Task                                                                                   | Status |
|-----|---------------------------------------------------------------------------------------|--------|
| 1   | 🔲 Configure speech-to-text Whisper: local transcription, create Python script for 5s audio | Pending |
| 2   | 🔲 Use Flask API - Check AVFoundation documentation to send to API                    | Pending |
| 3   | 🔲 Record audio and send to API for storage                                           | Pending |
| 4   | 🔲 Generate tasks with Llama                                                         | Pending |
| 5   | 🔲 Instacart integration - Test Playwright API and ChatGPT Operator compatibility     | Pending |

---

#### Basic Cross-Platform Setup
| #   | Task                                                                                   | Status |
|-----|---------------------------------------------------------------------------------------|--------|
| 1   | ✅ Create basic PDF layout in Sketch (translate to SVG/JSON, and later Storyboard in Xcode) | Done   |
| 2   | 🔲 Build UITableView in Storyboard (match wireframe), add button to trigger speech recording | Pending |
| 3   | 🔲 Create shared JSON schema for cross-platform compatibility                         | Pending |
| 4   | 🔲 Enable CloudKit container - CKRecord                                               | Pending |

---

#### iOS-Specific Testing
| #   | Task                                                                                   | Status |
|-----|---------------------------------------------------------------------------------------|--------|
| 1   | ✅ Evaluate VisionOS CoreML features and validate configurations                      | Done   |
| 2   | 🔲 Test VisionOS tasks, validate Flask API integration                                | Pending |
| 3   | 🔲 Execute build of data input, UI creation, and storage in Simulator                 | Pending |
| 4   | 🔲 Test MacOS compatibility for VisionOS                                              | Pending |

---

#### Benchmarking and Final Iterations
| #   | Task                                                                                   | Status |
|-----|---------------------------------------------------------------------------------------|--------|
| 1   | ✅ Research Benchmark options: OSWorld and DeepEval with LlamaIndex                   | Done   |
| 2   | 🔲 Run Benchmark analysis across apps, generating to-do list items                   | Pending |
| 3   | 🔲 Iteratively test web, MacOS, and iOS configurations                                | Pending |
| 4   | 🔲 Research additional papers for benchmarking refinement                             | Pending |

### Old To-Do List

# Updated To-Do List - v1 - iOS (Phase 1) and MacOS (Phase 2)
| Initial Setup | Basic Cross-Platform Setup | Configuration and GenAI Magic | Testing/Benchmarking |
| :------------ | :------------------------- | :---------------------------- | :------------------ |
| - 1 ✅ Evaluated VisionOS CoreML feature |  - ✅ Create basic pdf layout in sketch that I will translate into SVG/JSON and then Storyboard and in XCode basic | 🔲 Configure speech-to-text Whisper: local transcription, create 5s audio script | - ✅ Research Benchmark (OSWorld, DeepEval integration with LlamaIndex for Computer Use) |
| - 2 ✅ Installfest Python latest, Ollama, Llama, Flask, transformers, Torch, Playwright (Instacart API)  | 🔲 create structure with CalendarKit for logging task times with prettier UI | 🔲 Record audio and send to API for storage |🔲 Execute build of data input, UI creation, storage to run in Simulator | 
| - 3 🔲 Configure Langchain, Langgraph, langsmith, LlamaIndex (DeepEval), honeyhive, tavily API, vellum optional.  | - 🔲 Check if this would work in MacOS - research documentation | Use ChatGPT to create rest of UI based on SVG and JSON I created from Sketch/Figma/Storyboard for storage that would work on iOS and MacOS | - 🔲 Run Benchmark analysis for multiple apps - creation of multiple to-do list items and integration across 20 different integrations already in use for OpenAI to store log of data into productivity app | 🔲 stuff | - 🔲 Implement ReactJS web app creation with TailwindCSS | [ ] Implement PDF generation - PDFKit | |
| - 4 🔲 Use Flask API. Check AVFoundation documentation to send to API | 🔲 Check if this would work on VisionOS | 🔲 Generate tasks with Llama | 🔲 test stuff | 🔲 test stuff
| - 5 ✅ Create initial GH Repo | - 🔲 Create shared JSON schema for cross-platform compatibility | - 🔲 Enable CloudKit container - CKRecord  | 🔲 test stuff | 🔲 Submit request for ask Apple Dev during office hours for entitlements; handwriting recognizer with MNIST; passthrough camera frame
| - 6 🔲 Set up Xcode project with Whisper/ChatGPT 4.1 API integration | more cross-platform stuff | - 🔲 Build UITableView in Storyboard (match old wireframe), add button to trigger speech recording | 🔲 test stuff | 🔲 test stuff
| - 7 🔲 Instacart Integration | 🔲 Read ChatGPT4.1 (Operator documentation) with Instacart Playwright API  |  🔲  Test if this can work in another application integrated with ChatGPT Operator compatible iOS apps | 🔲 test stuff | 🔲 test stuff 
| - 8 🔲 Next iterations| 🔲 Test in web, MacOS| 🔲 Any last configurations | 🔲 Research papers one more time for other CUA benchmarks | 🔲 Ask GSIs if there are other benchmarks I need to hit.

# To-Do List v2 - MacOS and VisionOS - Phase 3
### This is when we can get entitlments for VisionOS and if not iOS as an app (if we have time), we create a MacOS version to store data with Cloud Kit for Apple Private Cloud.

| Initial Setup                                                                                                  | Basic Cross-Platform Setup                                      | Configuration and GenAI Magic                                                      | Testing and Benchmarking |
|:---------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------|:-----------------------------------------------------------------------------------|:--------------------------|
| - 🔲 1  Check documentation for cross-platform setup and install VisionOS3 (currently on VisionOS2)             | - 🔲 Add button to trigger speech recording                    | - 🔲 Test that data renders in CloudKit on VisionOS                                        | Validate build and record simulator demo      |
| - 🔲 2 Integration Playwright |                                                                                    | - 🔲 Run in simulator                                                     | - 🔲 Stuff stuff                                                                   | - 🔲 Research Benchmark (OSWorld, DeepEval integration with LlamaIndex for Computer Use) | 
| - 🔲 3 See what works for VisionOS with CalendarKit and other SwiftUI components and what has to be uniquely customized | 🔲 Check if this would be compatible on MacOS |  - 🔲 test computer vision capture with CoreML on VisionOS |

# Overview Installation Outline Overview - 5-7-25
                                 
| Completion Status and Task                 | Notes                               |
|:-------------------------------------------|:--------------------------------------------------------------|
| -🔲 Configure tool 
| -🔲 Define Agents
| -🔲 Voice Workflow and Pipeline
| -🔲 Building Real Time Voice Application
| -🔲 Create UI
| -🔲 Verify/check data into UI is correctly transcribed (what you said, what you wrote)
| -🔲 Store data into Apple Private Cloud
| -🔲 Configuration Under the Hood
| -🔲 LangChain
| -🔲 LangGraph
| -🔲 Llama Index - Chunking
| -🔲 Computer Use Agent Comparison
| -🔲 Upload screenshots of recording Vision Pro workflow 
| -🔲 Authorize auth0 check-out (configure)