# Jai Ashar

I build machine-learning infrastructure, systems software, and consumer applications. I'm the cofounder of **Vora**. Previously, I led architecture and implementation of **SageMaker inference components** across teams and built **Bedrock asynchronous model-hosting infrastructure** at AWS. My research includes computer vision at Penn's **GRASP Lab**.

[Website and background](https://jaiashar.com/) · [LinkedIn](https://www.linkedin.com/in/jaiashar/) · [Email](mailto:jai.k.ashar@gmail.com)

## Systems and machine learning

### [PennOS](https://github.com/Jaiashar/penn-os)

A Unix-like operating system in C, built with a Penn team and running in Linux userspace. Implements preemptive scheduling, process management, a shell, and PennFAT storage. Includes a container build and automated smoke tests.

[Source](https://github.com/Jaiashar/penn-os) · [Build and validation](https://github.com/Jaiashar/penn-os/blob/main/VALIDATION.md)

### [PennShell](https://github.com/Jaiashar/penn-shell)

A Unix shell in C with pipelines, I/O redirection, process groups, signal handling, and foreground/background job control. Pair-programmed with Mytreyi Narayanaswamy, contributing roughly equally. Includes automated checks.

[Source and checks](https://github.com/Jaiashar/penn-shell)

### [AWS inference infrastructure](https://github.com/Jaiashar/aws-inference)

Led architecture and implementation of SageMaker inference components across teams, enabling models to share endpoint compute with per-model resource reservations and independent scaling. Built asynchronous model-hosting infrastructure for Bedrock and worked with enterprise customers to train and optimize models using PyTorch and Hugging Face.

[Architecture case study](https://github.com/Jaiashar/aws-inference) · [SageMaker launch](https://aws.amazon.com/blogs/aws/amazon-sagemaker-adds-new-inference-capabilities-to-help-reduce-foundation-model-deployment-costs-and-latency/) · [Bedrock API](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_StartAsyncInvoke.html)

### [GRASP Lab: agricultural vision](https://github.com/Jaiashar/grasp-fruit-counting)

Computer-vision models and fruit-counting research at Penn. The team's implementation combines TensorFlow segmentation, optical flow, Kalman filtering, and Hungarian assignment to track fruit across orchard imagery. The public extract includes historical FCN source, runnable tracking primitives, a synthetic demo, and automated tests, with original contributor credits preserved.

[Source and demo](https://github.com/Jaiashar/grasp-fruit-counting) · [Research walkthrough](research-and-systems.md)

## Other

**[Ziffyn](https://github.com/Jaiashar/ziffyn).** Cofounded a home-chef marketplace built around California's MEHKO framework for permitted home-kitchen businesses. We recruited hundreds of chefs; I taught myself iOS and built the consumer, marketplace, and chef/driver apps from scratch. The repository documents the product and architecture as a case study.

**[Auricore](https://github.com/Jaiashar/auricore-web).** Cofounded a platform for identifying and pricing luxury goods from photos. Built web and mobile product experiences and Python pipelines for product ingestion and catalog matching. Public source covers the historical web application, [multi-site product ingestion](https://github.com/Jaiashar/luxury-product-ingestion), and [catalog canonicalization](https://github.com/Jaiashar/product-canonicalization).

**Fine-wine traceability.** Architected and built a supply-chain platform connecting a blockchain network API with IoT sensors for temperature, humidity, and light exposure from vineyard to cellar.

Additional [research and systems notes](research-and-systems.md#open-uav-drone-simulation) cover my Open-UAV contribution and virtual-memory work.

Source repositories document their setup, checks, and limitations. AWS and Ziffyn are case studies; AWS implementation source is proprietary, and Ziffyn's original app source has not been recovered.
