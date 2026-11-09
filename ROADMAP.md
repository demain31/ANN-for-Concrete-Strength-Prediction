# Project Development Roadmap

## Phase 1: Engine Refactoring & Vectorization (Claude Code)
- [ ] Refactor Python inference runtime into modular packages (`src/inference`, `src/utils`).
- [ ] Vectorize custom activation functions (Swish, SELU, ELU) using optimized NumPy routines.
- [ ] Eliminate activation loop bottlenecks and minimize dynamic memory allocations.
- [ ] Harden error handling and input dimension verification.

## Phase 2: Quality Assurance & Automated Testing
- [ ] Implement automated test suite with `pytest`.
- [ ] Verify non-regression against baseline cross-validation metrics (Val MSE = 18.15, R² = 0.9385).
- [ ] Build synthetic mock data generators for isolated local testing without external Kaggle dependencies.

## Phase 3: Multimodal Expansion
- [ ] Implement 1D-CNN modular blocks for ultrasonic pulse velocity (UPV) and acoustic sensor waveforms.
- [ ] Implement 2D convolutional blocks for surface crack detection and porosity analysis.
- [ ] Unify multimodal latent representations into the core inference engine.

## Phase 4: TinyML & Bare-Metal C++ Port (Arduino Uno)
- [ ] Export trained weights and binary connectivity masks (`W * Mask01`) to static C++ header files.
- [ ] Implement zero-allocation forward pass optimized for ATmega328P (< 2 KB SRAM).
- [ ] Validate real-time inference latency and accuracy on direct sensor hardware on the desk.