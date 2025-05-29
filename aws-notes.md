# Cloud Computing & Amazon EC2 Basics

## Cloud Computing
Cloud computing is the on-demand delivery of IT resources via the internet with **pay-as-you-go** pricing.

### Deployment Models
1. **On-Premises (Traditional)**  
   - Everything is hosted locally (your own servers).  
   - You manage everything: hardware, software, updates.

2. **Cloud**  
   - Fully managed by a cloud provider (like AWS, Azure, GCP).  
   - No hardware or local infrastructure needed.

3. **Hybrid**  
   - A mix of on-premises and cloud resources.  
   - Often used for sensitive data or legacy systems.

### Service Models
1. **IaaS (Infrastructure as a Service)**  
   - Renting infrastructure (e.g., servers, storage, networking).  
   - Examples: AWS EC2, Azure VM.

2. **PaaS (Platform as a Service)**  
   - Renting OS and tools/platform (e.g., runtime, databases).  
   - Examples: AWS Elastic Beanstalk, Google App Engine.

3. **SaaS (Software as a Service)**  
   - Renting the software itself (no need to manage infra or OS).  
   - Examples: Gmail, Salesforce.


## Amazon Elastic Compute Cloud (EC2)
Amazon EC2 is a **virtual server** in the cloud. It acts like a server in a **client-server environment**, handling requests whether it’s code, a video, or a file.

### EC2 Instance Types
EC2 offers different types of instances (servers), optimized for various workloads:
- **General Purpose**: balanced CPU, memory, and networking (e.g., t2.micro).
- **Compute Optimized**: for CPU-intensive tasks.
- **Memory Optimized**: for memory-heavy tasks.
- **Accelerator Optimized**: for GPU-based tasks (like ML/AI).
- **Storage Optimized**: for data-heavy tasks.

added first AWS notes
