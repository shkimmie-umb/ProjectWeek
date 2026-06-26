---
layout: pw45-project

permalink: /:path/

project_title: AI driven interface for SlicerTMS
category: IGT and Training
presenter_location: 

key_investigators:

- name: SangHyuk Kim
  affiliation: BWH & UMass Boston
  country: USA

- name: Puxun Tu
  affiliation: BWH & SJTU
  country: USA

- name: Steve Pieper
  affiliation: Isomics
  country: USA

- name: Lipeng Ning
  affiliation: BWH & HMS
  country: USA

---

# Project Description

<!-- Add a short paragraph describing the project. -->


SlicerTMS is a 3DSlicer module for patient-specific transcranial stimulation. It integrates several functions, including neuronavigation, electric field modeling, real-time EEG streaming and recording, and TMS control. These functions involve a complex user interface, and some tasks, such as neuronavigation registration, may need more than one user. To simplify the interface and improve the user experience, we will develop a new version leveraging LLM models and Slicer AI Agent tools. Specifically, we will eliminate LLM hallucinations at the infrastructure level by executing medical software APIs through human-verified Markdown Cookbooks and local Vector RAG technologies. Furthermore, the system establishes a next-generation intelligent environment featuring a self-evolving Auto-Correction engine that tracks and learns directly from clinician adjustment patterns, all while seamlessly supporting the trusted clinical interfaces medical professionals already use.



## Objective

<!-- Describe here WHAT you would like to achieve (what you will have as end result). -->


- Implement a voice-based interface for neuronavigation registration.
- Improve the data visualization interface using the AI agent, e.g., by switching between visualization methods.
- Simplify the interface with the EEG and TMS devices AI agent.
- Minimize LLM hallucination in SlicerTMS by compiling user intent into strict template-based execution payloads.



## Approach and Plan

<!-- Describe here HOW you would like to achieve the objectives stated above. -->


- Zero-Hallucination RAG System: Modularize verified VTK recipes into Markdown Cookbooks, embed them into a local Vector DB, and inject real-time scene variables for deterministic execution.
- UI and UX Modernization: Integrate high-density clinical data and 2D/3D visualizations into a dynamic spatial layout to overcome Slicer's legacy UI constraints.
- Architecture Evaluation Benchmark inference accuracy, latency, and medical data privacy between closed-network offline models and cloud-based counterparts.



## Progress

- Local LLM successfully integrated. Feasibility of offline AI assistance proven. Direct connection to SlicerTMS established.
- SlicerTMS Navigation workflow automated. Registration menu interaction reproduced. AI directly drives the Slicer UI.
- Cookbook architecture implemented. Simple verified tasks translated into strict markdown rules. Zero-hallucination task calling achieved.


## Next Steps

- Advanced scene awareness required. Agent must automatically recognize EEG nodes upon stylus contact. 
- Complex spatial understanding pending. AI agent should be able to auto-correct inaccurate annotations.
- Local LLMs must be evaluated against cloud models like Claude. Focus on reasoning accuracy and execution speed for targeting tasks.
- System should be able to process prompts to move specific coils to target nodes (SlicerMCP pipeline design).



# Illustrations

<!-- Add pictures and links to videos that demonstrate what has been accomplished. -->


_No response_



# Background and References

<!-- If you developed any software, include link to the source code repository.
     If possible, also add links to sample data, and to any relevant publications. -->


SlicerTMS, Slicer AI Agent, NousNav

