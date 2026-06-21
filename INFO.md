# 👤 Fiche d'Identité Technique & Scientifique

> *Optima, immo absoluta perfectio.*
> — **YEVI Mawuli Péniel Samuel**

---

## 🔬 Profil & Positionnement

Je suis étudiant en **Systèmes Embarqués & IoT** à l'IFRI-UAC et chercheur indépendant. Mon travail se situe à l'intersection de la performance matérielle bas niveau (HPC), de la conception de systèmes d'IA locaux (Edge AI) et de la recherche mathématique théorique.

Plutôt que d'utiliser des modèles existants comme des boîtes noires, je conçois des runtimes de calcul, des architectures de modèles séquentiels et des outils de recherche pour explorer comment l'information est représentée, transformée et optimisée.

---

## ⚡ Domaines d'Expertise & Stack

### 💾 Calcul Bas Niveau & Systèmes (HPC)
*   **Langages** : Assembleur x86-64 (AVX2, AVX-512), C, C++, Rust (en apprentissage), CUDA.
*   **Concepts** : Dispatch de kernels, parallélisme CPU/GPU, vectorisation, quantification de poids d'IA (`int4` / `int8` symétrique et asymétrique), gestion mémoire (ZOH, Blelloch prefix sum).

### 🧠 Intelligence Artificielle & Mathématiques
*   **Architectures** : SSMs (State Space Models - Mamba), Transformers.
*   **Mathématiques appliquées** : Résolution d'équations différentielles non linéaires (opérateurs de Koopman, catégories), topologie causale d'ordonnancement (*wavefront*).
*   **Frameworks d'entraînement** : PyTorch, Unsloth (QLoRA), Hugging Face, llama.cpp.

### 🌐 Ingénierie Logicielle & Tooling
*   **Systèmes** : Python (FastAPI, SSE), Electron, Django, PostgreSQL.
*   **Front-end** : TypeScript, React, Next.js, Vanilla CSS, Tailwind CSS.
*   **Outils développeurs** : CLI Rust autonomes, extensions VS Code, intégration Git.

---

## 📂 Catalogue des Projets Phares

### 1. [optimatrix](file:///home/samuel-yevi/Dev/frameworks/optimatrix) — Substrat de calcul numérique
*   **Rôle** : Bibliothèque de primitives d'algèbre linéaire haute performance (similaire à un BLAS étendu).
*   **Stack** : Assembleur x86-64 AVX2, C, CUDA, bindings Python (`pybind11`).
*   **Détails** : Implémente le GEMM batché, les convolutions 1D et 2D, les activations (GELU, SiLU) avec backward, et un packager de poids `int4` (nibble-pack).
*   **Fichiers de référence** :
    *   [README.md](file:///home/samuel-yevi/Dev/frameworks/optimatrix/README.md)
    *   [USAGE.md](file:///home/samuel-yevi/Dev/frameworks/optimatrix/USAGE.md)

### 2. [k-mamba](file:///home/samuel-yevi/Dev/Researches/k-mamba) — SSMs Multi-dimensionnels
*   **Rôle** : Modèles d'espaces d'états avec récurrence native ND simultanée et convolution ND native.
*   **Concepts** : Remplacement des scans 1D successifs (VMamba/Mamba-ND) par une récurrence native ND structurée sur un graphe causale wavefront parallélisable (parallélisme géométrique exact intra-niveau).
*   **Fichiers de référence** :
    *   [THEORY.md](file:///home/samuel-yevi/Dev/Researches/k-mamba/THEORY.md)

### 3. [bissi](file:///home/samuel-yevi/Dev/Hackathons/gemma4good/bissi) — Assistant Agentique Offline (Edge AI)
*   **Rôle** : Assistant IA local-first fonctionnant 100% hors-ligne.
*   **Stack** : Gemma 4 E2B affiné avec Unsloth (QLoRA) → Quantifié en Q4_K_M (3.2 Go) → llama.cpp → FastAPI (SSE streaming) → Electron.
*   **Impact** : Conçu pour les environnements à faible connectivité en Afrique de l'Ouest. Permet l'analyse documentaire, le calcul et l'exécution locale de code Python.
*   **Fichiers de référence** :
    *   [README.md](file:///home/samuel-yevi/Dev/Hackathons/gemma4good/bissi/README.md)

### 4. [plenum](file:///home/samuel-yevi/Dev/side_projects/plenum) — Délibération Multi-IA
*   **Rôle** : Outil CLI/TUI pour faire débattre plusieurs LLMs en parallèle (Claude, Gemini, DeepSeek, ChatGPT, Kimi).
*   **Mécanisme** : Système asynchrone (`asyncio.gather()`) qui réinjecte les réponses de chaque modèle dans le prompt des autres à chaque tour, forçant une délibération collective.
*   **Fichiers de référence** :
    *   [README.md](file:///home/samuel-yevi/Dev/side_projects/plenum/README.md)

### 5. [Serenity](file:///home/samuel-yevi/Dev/Researches/Serenity) — Modèle d'Univers & TEM
*   **Rôle** : Cadre d'étude théorique basé sur la *Théorie de l'Environnement Mathématique*.
*   **Concept** : Résolution des équations différentielles non linéaires par projection/changement d'environnement de dimension supérieure (linéarisation via Bifoncteurs, opérateurs de Koopman appliqués à la cosmologie physique).
*   **Fichiers de référence** :
    *   [README.md](file:///home/samuel-yevi/Dev/Researches/Serenity/README.md)

---

## 🏆 Hackathons & Compétitions
*   **Gemma 4 Good Hackathon (2025/2026)** : Création et affinement de l'assistant local [bissi](file:///home/samuel-yevi/Dev/Hackathons/gemma4good/bissi).
*   **DataTour 2026** : Compétition et résolution de challenges en Data Science.
*   **Bitcoin Mastermind Hackathon 2026** : En cours de préparation.

---

## 🎯 Objectifs de recherche & Collaboration

Je suis ouvert aux collaborations de recherche académique et d'ingénierie avancée, en particulier sur :
*   L'optimisation mathématique des modèles séquentiels non-Attention (Mamba, SSMs, RWKV).
*   L'accélération matérielle des LLMs sur CPU/GPU/NPU de bord (Edge).
*   La modélisation mathématique rigoureuse de la dynamique physique des systèmes neuronaux.

📩 **Contact** : [leumasnedlogdev777@gmail.com](mailto:leumasnedlogdev777@gmail.com) | [LinkedIn](https://www.linkedin.com/in/samuel-yevi-b42071388/)
