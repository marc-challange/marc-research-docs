# Research Paper Collection

Here is a curated list of research papers and documents related to the MLST episode on Mohamed Osman and the ARC challenge, covering topics from deep learning approaches to abstract reasoning, systematic generalization, and program synthesis.

---

## Show Notes: Mohamed Osman on the ARC Challenge

> This document provides a comprehensive summary and analysis of the Machine Learning Street Talk (MLST) episode featuring Mohamed Osman. It covers the technical breakthroughs from his team (MindsAI, acquired by Tufa Labs) in solving the Abstraction and Reasoning Corpus (ARC) challenge. The core innovations discussed include test-time fine-tuning (TTFT) and treating ARC as a perceptual problem, leading to a state-of-the-art 58% accuracy on the hidden test set. The notes also delve into the limitations of current AI architectures, the use of a modified T5 model for "meta-modeling," and the future of abstract reasoning benchmarks like ARC v2.

**Author:** MLST (Machine Learning Street Talk)
**Published:** 2025-03-22
[PDF Link](./papers/MLST_Mohamed_Osman_Show_Notes.pdf)

---

## Don't Throw the Baby Out with the Bathwater: How and Why Deep Learning for ARC

> The Abstraction and Reasoning Corpus (ARC-AGI) presents a formidable challenge for AI systems. This work demonstrates that fully committing to deep learning's capacity to acquire novel abstractions yields state-of-the-art performance on ARC. Specifically, we treat both the neural network and the optimizer as integral components of the inference process, fostering generalization to unseen tasks. We propose Test-Time Fine-Tuning (TTFT) and Augment Inference Reverse-Augmentation and Vote (AIRV) as effective test-time techniques, achieving boosts of up to 260% with AIRV and a further 300% with TTFT. This approach secured first place in the 2023 ARCathon and achieved the current best score (58%) on the ARC private test set.

**Authors:** Jack Cole, Mohamed Osman
**Published:** Early 2025
[PDF Link](./papers/Dont_Throw_The_Baby_Out_With_The_Bathwater_ARC.pdf)

---

## Human-like systematic generalization through a meta-learning neural network

> The power of human language and thought arises from systematic compositionality. Here we successfully address Fodor and Pylyshyn's challenge by providing evidence that neural networks can achieve human-like systematicity when optimized for their compositional skills. We introduce the meta-learning for compositionality (MLC) approach for guiding training through a dynamic stream of compositional tasks. In contrast to perfectly systematic but rigid symbolic models, and perfectly flexible but unsystematic neural networks, only MLC achieves both the systematicity and flexibility needed for human-like generalization. Our results show how a standard neural network architecture, optimized for its compositional skills, can mimic human systematic generalization in a head-to-head comparison.

**Authors:** Brenden M. Lake, Marco Baroni
**Published:** 2023-10-25
[PDF Link](./papers/Human_Like_Systematic_Generalization.pdf)

---

## Towards Efficient Neurally-Guided Program Induction for ARC-AGI

> ARC-AGI is an open-world problem domain in which the ability to generalize out-of-distribution is a crucial quality. Under the program induction paradigm, we present a series of experiments that reveal the efficiency and generalization characteristics of various neurally-guided program induction approaches. We consider three paradigms: Learning the grid space (LGS), Learning the program space (LPS), and Learning the transformation space (LTS). After identifying the strengths and weaknesses of these approaches, we suggest the third as a potential solution and run preliminary experiments.

**Author:** Simon Ouellette
**Published:** 2024-11-13
[PDF Link](./papers/Neurally_Guided_Program_Induction_ARC_AGI.pdf)

---

## Procedural Knowledge in Pretraining Drives Reasoning in Large Language Models

> This paper studies the generalisation strategies LLMs employ when performing reasoning tasks by investigating the pretraining data they rely on. We find that, while models rely on distinct data for factual questions, a document often has a similar influence across different reasoning questions within the same task, indicating the presence of procedural knowledge. This suggests the model's approach is unlike retrieval and more like a generalisable strategy that synthesises procedural knowledge from documents doing a similar form of reasoning.

**Authors:** Laura Ruis, Maximilian Mozes, Juhan Bae, Siddhartha Rao Kamalakara, Dwarak Talupuru, Acyr Locatelli, Robert Kirk, Tim Rocktäschel, Edward Grefenstette, Max Bartolo
**Published:** 2025-03-06
[PDF Link](./papers/Procedural_Knowledge_In_Pretraining.pdf)

---