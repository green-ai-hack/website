![hero](images/hero.png)

# What's the Green AI Hack?

The **Green AI Hack** is an AI hackathon that explores the trade-off between performance and environmental footprint of AI models. We aim to **raise awareness** about the environmental impacts of AI and provide **best practices** to reduce them.

Each submission is evaluated using two metrics: a **performance metric** (such as accuracy) and an **impact metric** that quantifies the solution's environmental friendliness. The final ranking considers both metrics, rewarding teams that **optimize for both performance and sustainability**.

[Samuel Rincé](https://samuelrince.com) created the Green AI Hack and organized the **first edition in 2022** during the [IA Pau](https://iapau.org/)'s Data Challenge. Future editions can be held in your organization or university. [Contact us](contact.md) to learn more about hosting your own Green AI Hack.

# Why the Green AI Hack?

While the environmental footprint of AI is occasionally discussed, it's rarely accounted for, especially by AI practitioners. Understanding the environmental issues surrounding AI can be challenging due to its complexity.

We want AI practitioners to **unlearn inefficient practices** regarding energy consumption and model selection and focus on **finding the right model for the task** and **using AI responsibly**.

The Green AI Hack is the **ideal event** to **train technical teams or students** on **green AI practices**. It can help establish proper governance and best practices for achieving **sustainability goals** in organizations.

# How it works?

The Green AI Hack is powered by **open-source software** developed by various organizations from the **sustainable IT landscape**. We utilize [SoftAWERE](https://gitlab.com/softawere-hackathon/softawere/), a continuous integration (CI) toolchain that combines open-source software to monitor energy consumption and environmental impacts of AI models during testing.

[Scaphandre](https://github.com/hubblo-org/scaphandre) and [NVIDIA GPU Exporter](https://github.com/utkuozdemir/nvidia_gpu_exporter) are used to **monitor energy consumption** of all components on the server that will run and test each submission.

[BoaviztAPI](https://github.com/Boavizta/boaviztapi) is used to **compute environmental impacts** such as carbon emissions or abiotic resource utilization, from energy consumption and hardware manufacturing.

Submission jobs are managed in **GitLab CI pipelines** and results are push to an **online leaderboard** where teams can compare their solutions and scores.

