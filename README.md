# Jai Ashar

I'm the cofounder of **[Vora](https://askvora.com)**. Previously, I built machine-learning inference infrastructure at **AWS** and worked on computer-vision models and fruit-counting research at Penn's **[GRASP Lab](https://www.grasp.upenn.edu/)**. My work spans consumer products, machine learning, and systems programming.

## Vora · A proactive personal health AI agent

We're building Vora to investigate what's affecting your health, start conversations before you know what to ask, and follow up as you make changes.

Our iOS and Android apps are live. We've built proactive AI and a connected health-data foundation through partnerships and integrations, including knowledge graphs and algorithms for identifying trends. We're now developing an experience around **text and voice through iMessage, WhatsApp, and calls**, bringing together health context, explanations, and follow-ups.

[Explore Vora](https://askvora.com) · [iOS app](https://apps.apple.com/us/app/vora-health/id6754351240)

## AWS · Machine-learning inference infrastructure

At AWS, I contributed to **SageMaker foundation-model hosting** and **Bedrock asynchronous inference**. I also worked with enterprise customers to develop, train, and optimize models using PyTorch and Hugging Face, balancing model quality, memory, training time, and inference cost.

The [SageMaker launch](https://aws.amazon.com/blogs/aws/amazon-sagemaker-adds-new-inference-capabilities-to-help-reduce-foundation-model-deployment-costs-and-latency/) and [Bedrock API](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_StartAsyncInvoke.html) document the capabilities. My [engineering case study](https://github.com/Jaiashar/aws-inference) explains their public architecture and my role. AWS implementation source remains proprietary.

## GRASP Lab · Computer vision and fruit counting

At Penn's GRASP Lab, I worked on **computer-vision models and fruit-counting research**. The agricultural vision work represented in [Tréfo](https://github.com/Trefo) includes annotation, TensorFlow segmentation, and tracking across image sequences. The team's implementation combines fully convolutional networks, optical flow, Kalman filtering, and Hungarian assignment.

The public [GRASP fruit-counting repository](https://github.com/Jaiashar/grasp-fruit-counting) includes the historical agricultural FCN source, runnable tracking primitives, an animated synthetic demo, and automated tests. It explains my research role and preserves original team and upstream credits. The [research walkthrough](research-and-systems.md) covers the wider project; [AgDSS](https://github.com/Trefo/agdss) provides related annotation tooling.

## Selected builds

| Project | What I built and what you can inspect |
| --- | --- |
| **[PennOS](https://github.com/Jaiashar/penn-os)** | A team-built Unix-like OS in C with preemptive scheduling, process management, a shell, and PennFAT storage. Runs in Linux userspace. Source, container build, and automated smoke tests are available. |
| **[PennShell](https://github.com/Jaiashar/penn-shell)** | Pipelines, redirection, signals, and foreground/background jobs. Mytreyi Narayanaswamy and I pair-programmed it, contributing roughly equally. Includes source and automated checks. |
| **[Ziffyn](https://github.com/Jaiashar/ziffyn)** | A home-chef marketplace built around California's MEHKO framework. We recruited hundreds of chefs; I learned iOS and built the consumer, marketplace, and chef/driver apps from scratch. Case study; original app source has not been recovered. |
| **[Auricore](https://github.com/Jaiashar/auricore-web)** | Item identification and market-price research from photos or descriptions. I contributed across applications and built catalog pipelines. The web source is a historical snapshot, not a verified live service. |

Auricore's public data projects cover [multi-site product ingestion](https://github.com/Jaiashar/luxury-product-ingestion) and [catalog canonicalization](https://github.com/Jaiashar/product-canonicalization). Historical mobile and supporting-service repositories are private.

I also architected and developed a **fine-wine traceability platform**, connecting a blockchain network API with IoT trackers for temperature, humidity, and light exposure from vineyard to cellar. My [research notes](research-and-systems.md#open-uav-drone-simulation) cover Open-UAV, virtual memory, and additional team projects.
