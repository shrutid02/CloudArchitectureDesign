## Problem Statement

Create an architecture design for a cloud application by evaluating different cloud providers, creating initial design drafts, validating designs using well-architected frameworks, and experimenting with Kubernetes. Demonstrate the effectiveness of the architectural design through a structured approach.Carefully consider factors like provider selection, design validation, and trade-offs to achieve a scalable, reliable, and cost-effective cloud architecture.

> The detailed design report can be found [here](https://github.com/shrutid02/CloudArchitectureDesign/blob/main/Cloud-Architecture-Design-Report.pdf).

### 🖥️ Application idea: Integrated Digital Content Catalog  
In today's digital era, an abundance of video content is accessible through various online streaming platforms such as Netflix, Amazon Video, Hulu, and many more. While the range of viewing options is vast, users often find themselves rummaging through multiple platforms to locate the specific content they desire, whether it's a movie or a web series. Furthermore, content is typically distributed across these platforms with minimal overlap, complicating the user's search for their preferred content.

This catalog will aggregate video content from all major streaming platforms, presenting it to users as a unified repository. Users will benefit from a one-stop platform, where they can effortlessly explore a comprehensive selection of content and make their viewing choices. Once a selection is made, the platform will seamlessly redirect the user to the corresponding streaming service for playback. The platform will also provide unbiased content recommendations by analyzing the user’s past ratings and viewing behaviors.

### ☁️ Choosing the most appropriate Cloud Provider for this solution (AWS / GCP/ Azure) 
Conducted a **comprehensive study of the major cloud providers** across multiple catregories and finalized **AWS** for architecting the solution. Comparision between different cloud providers:

![Image 04-02-24 at 1 52 PM](https://github.com/shrutid02/CloudArchitectureDesign/assets/42238433/aee244c0-3e4e-4e58-8082-05a5ba0de4a5)

### Initial Design Draft 
![Image 04-02-24 at 1 49 PM](https://github.com/shrutid02/CloudArchitectureDesign/assets/42238433/8b6373d4-213a-42b9-a75b-ae511fb557fa)

### Final Cloud Architecture Design
 Created using AWS CloudFormation.
 ![Image 04-02-24 at 1 49 PM](https://github.com/shrutid02/CloudArchitectureDesign/assets/42238433/624f34c2-b106-4bb0-ab55-7328b8ab8f60)
