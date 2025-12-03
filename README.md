# Code for Paper World Models with Hints from Large Language Models

@inproceedings{liu-etal-2025-world,
    title = "World Models with Hints of Large Language Models for Goal Achieving",
    author = "Liu, Zeyuan  and
      Huan, Ziyu  and
      Wang, Xiyao  and
      Lyu, Jiafei  and
      Tao, Jian  and
      Li, Xiu  and
      Huang, Furong  and
      Xu, Huazhe",
    editor = "Chiruzzo, Luis  and
      Ritter, Alan  and
      Wang, Lu",
    booktitle = "Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)",
    month = apr,
    year = "2025",
    address = "Albuquerque, New Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.naacl-long.3/",
    doi = "10.18653/v1/2025.naacl-long.3",
    pages = "50--72",
    ISBN = "979-8-89176-189-6",
    abstract = "Reinforcement learning struggles in the face of long-horizon tasks and sparse goals due to the difficulty in manual reward specification. While existing methods address this by adding intrinsic rewards, they may fail to provide meaningful guidance in long-horizon decision-making tasks with large state and action spaces, lacking purposeful exploration. Inspired by human cognition, we propose a new multi-modal model-based RL approach named Dreaming with Large Language Models (DLLM). DLLM integrates the proposed hinting subgoals from the LLMs into the model rollouts to encourage goal discovery and reaching in challenging tasks. By assigning higher intrinsic rewards to samples that align with the hints outlined by the language model during model rollouts, DLLM guides the agent toward meaningful and efficient exploration. Extensive experiments demonstrate that the DLLM outperforms recent methods in various challenging, sparse-reward environments such as HomeGrid, Crafter, and Minecraft by 41.8{\%}, 21.1{\%}, and 9.9{\%}, respectively."
}
