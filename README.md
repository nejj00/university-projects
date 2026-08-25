# Applied AI & Data Engineering Projects

## Information Retrieval and Search Engines

### [RAG System](https://github.com/nejj00/uni-rag-project)

Built a Retrieval-Augmented Generation (RAG) system — the technology that lets an AI assistant answer questions using a specific set of documents instead of just its general knowledge (similar to "chat with your PDF" tools). Part 1 builds a search-and-answer pipeline from scratch over a recipe dataset using classic keyword search; Part 2 upgrades it with AI-based semantic search, handling of long documents, and smarter query understanding, applied to a large collection of academic papers.

## Big Data Analytics Programming

### [Online Naive Bayes Spam Filter](https://github.com/nejj00/ku-leuven-bdap-assignment-1)

Built a spam email filter in C++ designed to keep working even as new, never-before-seen words keep showing up — a real-world problem, since you can't predict every word a spammer will use next. Solved this with two memory-efficient techniques for tracking a constantly growing vocabulary without needing unlimited memory, then benchmarked both to compare their accuracy and memory trade-offs.

### [Basketball Analytics & High-Speed Math](https://github.com/nejj00/ku-leuven-bdap-assignment-2)

Two-part assignment on processing data at scale. First, used Apache Spark — an industry-standard big-data tool — to analyze player-tracking data from real NBA games across a distributed computing cluster, calculating stats like distance run and clutch-time shooting efficiency. Second, sped up a statistical calculation by rewriting it to use a CPU's low-level parallel processing capabilities, cutting run time by up to 4x.

### [Fast Duplicate Detection at Scale](https://github.com/nejj00/ku-leuven-bdap-assignment-3)

Built a system to find near-duplicate documents in a collection of over one million documents — without the impossibly slow task of comparing every document to every other one. Used a similarity-hashing technique to shortlist only the likely matches first, cutting the number of comparisons needed by over 99.999% while still catching more than 99% of the true duplicates.

## Machine Learning: Project

### [Reinforcement Learning: Multi-Agent Games](https://github.com/nejj00/ku-leuven-ml-project)

Trained AI agents to play a cooperative survival video game using reinforcement learning — the same family of techniques used to train game-playing AI like AlphaGo. When the agent's performance plateaued, diagnosed that the bottleneck wasn't the learning algorithm itself but the information it had access to, and fixed it by giving it smarter, hand-designed cues about its surroundings — significantly boosting its score. Also implemented and compared several classic learning strategies on simplified two-player strategy games.

## Computer Vision

### [Classic Image Processing Pipeline](https://github.com/nejj00/computer-vision-assignment-1)

Built a video-processing pipeline using traditional (non-AI) image-processing techniques: smoothing and sharpening footage, detecting edges and shapes, and picking out objects by color and pattern-matching.

### [Computer Vision Competitions](https://github.com/gianlucaascari/computer-vision-competitions) (group project)

Two class-wide, ranked competitions built with a team of four:
- **Face recognition** — compared four different approaches to recognizing faces, from traditional image-processing techniques to modern deep-learning face embeddings. Personally built and evaluated the dimensionality-reduction approach (PCA/eigenfaces), one of the four methods compared.
- **Image classification & segmentation** — applied deep learning to label images with multiple objects, outline objects pixel-by-pixel, and test how easily the models could be fooled by adversarial images. Personally built and evaluated an image-segmentation model (U-Net) from scratch.
