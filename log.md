# Development Log

## Day 1

### Report
- [Initial project discussion](https://chatgpt.com/c/6837e954-31c4-800d-b6b5-8477ba9bcfa8)
- Generated project overview to establish clear mental model of the project scope

### Next Steps
- Research existing implementations of video activity detection

## Day 2

### Progress
- Identified multiple existing implementations
- Began evaluating [human-activity-recognition](https://github.com/noorkhokhar99/human-activity-recognition/tree/main?tab=readme-ov-file) implementation

### Issues Encountered
- OpenCV installation on Kaggle lacks GPU support
  - Error when trying to run GPU-accelerated portions

### Solutions Identified
1. Run code on Google Colab (pre-configured with GPU support)
2. Build OpenCV locally with GPU support

### Next Steps
- Implement solution #1 (Colab) for immediate testing
- Consider solution #2 (local build) for long-term development