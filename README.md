# Jai Ashar

I'm the cofounder of **[Vora](https://askvora.com)**. Previously, I built machine-learning inference infrastructure at **AWS**, working on **Amazon SageMaker and Amazon Bedrock**. My work spans consumer products, model deployment, and systems programming.

## Vora · A proactive personal health AI agent

We're building Vora to investigate what's affecting your health and progress, start conversations before you know what to ask, and follow up as you make changes. The agent will bring together wearables, blood work, meals, supplements, and health history, explain what it notices, ask for missing context, and help you decide what to change.

Our iOS and Android apps are live. We've built a connected health-data foundation through partnerships and integrations, along with proactive AI, knowledge graphs, and algorithms for identifying trends and relationships in that data. We're now developing the primary experience around **text and voice through iMessage, WhatsApp, and calls**, with explanations, graphs, recommendations, and follow-ups in the conversation.

[Explore Vora](https://askvora.com) · [iOS app](https://apps.apple.com/us/app/vora-health/id6754351240)

## AWS · Machine-learning inference infrastructure

At AWS, I built infrastructure for **SageMaker and Bedrock**, including asynchronous model hosting for long-running workloads. I also worked directly with enterprise customers to develop, train, and optimize models using **PyTorch and Hugging Face**, working through tradeoffs in model quality, training time, memory requirements, and inference cost.

| Work | Capability | Public reference |
| --- | --- | --- |
| **SageMaker inference** | Host multiple foundation models on shared endpoints with per-model resource allocation and independent scaling | [Launch announcement](https://aws.amazon.com/blogs/aws/amazon-sagemaker-adds-new-inference-capabilities-to-help-reduce-foundation-model-deployment-costs-and-latency/) |
| **Bedrock asynchronous invocation** | Start model work asynchronously and track the invocation separately from the initial request | [StartAsyncInvoke API](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_StartAsyncInvoke.html) |

[Engineering case study](https://github.com/Jaiashar/aws-inference)

## Selected builds

### [PennOS · An operating system in C](https://github.com/Jaiashar/penn-os)

I built a Unix-like operating system as part of a Penn team project: **preemptive scheduling, process management, a shell, and a FAT-style filesystem**. It switches execution contexts, manages process priorities and state, handles signals, and reads and writes files through PennFAT. The instructional OS runs in Linux userspace using timer signals and `ucontext`.

[Source and architecture](https://github.com/Jaiashar/penn-os) · [Build and validation](https://github.com/Jaiashar/penn-os/blob/main/VALIDATION.md)

### [Ziffyn · At-home chef service](https://github.com/Jaiashar/ziffyn)

I taught myself iOS development and built Ziffyn from scratch as **three connected applications: a marketplace app, a chef/driver app, and a consumer app**. The work spanned the different people involved in the service, from customers to the chefs and drivers fulfilling it. I learned the platform while carrying the implementation across all three applications.

[Project story and three-app overview](https://github.com/Jaiashar/ziffyn) · Case study; original source is not published.

### [Auricore · Identify and price luxury goods](https://github.com/Jaiashar/auricore-web)

Auricore helps answer **“What is this item, and what is it worth?”** A user starts with a photo or a manual description; the application identifies the item, finds comparable listings, and presents market-price research. The broader product includes inventory, mobile item intake, and borrower/lender application flows.

I contributed across the web and mobile applications and built product-data pipelines behind the catalog. The public code covers the user experience and the work of collecting, structuring, and matching inconsistent listings across marketplaces.

| Component | What it does |
| --- | --- |
| [Web application](https://github.com/Jaiashar/auricore-web) | Photo identification, comparable-listing research, valuation results and application intake |
| [Mobile application](https://github.com/Jaiashar/auricore-mobile) | Guided item intake, inventory, category-specific AI conversations and payment onboarding |
| [Product ingestion](https://github.com/Jaiashar/luxury-product-ingestion) | Multi-site listing collection, AI categorization, image processing and catalog storage |
| [Product canonicalization](https://github.com/Jaiashar/product-canonicalization) | Product matching, attribute extraction, enrichment and duplicate review |
| [Supporting services](https://github.com/Jaiashar/auricore-services) | API, payments and shared transaction types |

These are documented historical source snapshots with collaborator credits and validation notes.

### [PennShell · A Unix shell in C](https://github.com/Jaiashar/penn-shell)

A shell with **pipelines, I/O redirection, process groups, signal handling, and foreground/background jobs**. Mytreyi Narayanaswamy and I pair-programmed it, contributing roughly equally. It implements the process and terminal control behind commands such as `printf hello | wc -c`, `jobs`, `bg` and `fg`.

[Source, build instructions and examples](https://github.com/Jaiashar/penn-shell)

### Fine-wine traceability · Blockchain and IoT

I architected and developed an operational supply-chain platform connecting a custom blockchain network API with IoT trackers monitoring **temperature, humidity, and light exposure from vineyard to cellar**. It gave consumers, investors, distributors, and auction houses a shared way to verify wine provenance and storage conditions.

## Research and other systems work

I'm also part of **[Tréfo](https://github.com/Trefo)** and **[Open-UAV](https://github.com/Open-UAV)**, spanning agricultural computer vision and drone simulation. Public work includes [AgDSS](https://github.com/Trefo/agdss), an agricultural image-annotation and decision-support platform, and Open-UAV's PX4/ROS/Gazebo simulation projects.

[More research and team-project context](research-and-systems.md)
