# SST-EM: Advanced Metrics for Evaluating Semantic, Spatial and Temporal Aspects in Video Editing

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)

## Overview

SST-EM (Semantic, Spatial, and Temporal Evaluation Metric) is a cutting-edge evaluation framework for video editing models. 
It addresses the limitations of traditional metrics by leveraging Vision-Language Models, Object Detection, and Temporal Consistency checks to evaluate semantic fidelity and temporal smoothness. 
SST-EM integrates four components—semantic extraction, object tracking, object refinement, and temporal consistency—into a unified metric with weights optimized through human evaluations. This framework offers a comprehensive, multidimensional assessment of video editing quality.

### Key Features
- Multidimensional evaluation combining semantic and visual metrics.
- Evaluated stae-of-the-art video editing models such as VideoP2P, TokenFlow, Control-A-Video, and FateZero.
- Customizable for various video styles, genres, and complexities.

## Results

Here’s a comparison of results for various video editing models:  

<p align="center">
  <img src="images/Edited_results_comparison_models.png" alt="Edited Results Comparison" width="700">
</p>  

---
## Usage
**Step 1: Clone the repository**
```bash
git clone https://github.com/VarunBiyyala/Custom_evaluation_Metrics.git
cd Custom_evaluation_Metrics
```
**Step 2: Install dependencies.**
The detailed installations are in the demo notebook.

**Step 3: Run the framework.**
Before running the framework, make sure your edited videos are uploaded in the below structure.

## Data Structure

To run this evaluation pipeline, your edited videos has to be arranged in the following structure
```plaintext
├── ModelName/                 # Name of the video editing  model
  ├── video1/                  # Example datasets
  ├── video2/                  # Images for documentation
  ├── video3/                   # Helper scripts
  .
  .
  .
**Note:** Video names should be the editing prompt used during video editing.
