# PowerBI

PL-300

# Azure Animations



## About

At Azure Animations, we believe that understanding complex cloud technologies doesn't have to be difficult or boring. That's why we've reimagined learning with a fresh approach—by turning intricate concepts into engaging, fun Animations. Our platform brings the worlds of Devevlopers 💻, DevSecOps - Security 🔐, Cloud ☁️, and AI 🤖 to life, making it easier for everyone, from beginners to experts, to grasp essential ideas and stay up-to-date with the latest in technology.

Our Animations are crafted by Microsoft Technical Trainers 👨‍🏫👩‍🏫 , ensuring that the content is not only accurate but also creatively presented to hold your attention. Whether you're looking to demystify cloud architecture, explore security best practices, or dive into AI innovations, Azure Animations is here to help you visualize and understand the most important concepts in the tech world.

Get ready to learn, engage, and have fun with Azure Animations where cloud technology comes to life! 🚀

Don't forget to star (🌟) this repo to find it easier later.

# Content

## AI 

Azure AI is your gateway to transforming ideas into reality! Whether it's building intelligent apps, automating processes, or gaining insights from your data, Azure's cutting-edge AI services are here to supercharge your innovation 🚀. With powerful tools like Azure Cognitive Services, Machine Learning, and AI-powered analytics, the future is in your hands. Ready to turn your data into smart solutions? Let's redefine what's possible with AI in Azure! 💡✨

### Azure OpenAI - Provisioning and Deployment Creation



Above illustrates the process of provisioning Azure OpenAI, we start by using the Azure Portal. First, navigate to the Azure OpenAI Studio where you can select the appropriate model for your needs, such as GPT-4, GPT-4o, etc. Before users can consume the model, they need to select the model and create a deployment. There are several types of deployments available:

1. Azure Portal: Start by using the Azure Portal to navigate to Azure OpenAI Studio.
2. Select Model: Choose the right model (e.g., GPT-4, GPT-4o) 🧠.
3. Create Deployment:
   - Global-Batch: For offline scoring 🕒.
   - Global-Standard: Recommended starting point 🌍.
   - Global-Provisioned: For real-time scoring with high volume 📈.
   - Standard: General-purpose deployment.
   - Provisioned: For high-volume workloads.
   - Data Zone Standard: Leverages Azure global infrastructure for best availability and higher default quotas.
   - Data Zone Provisioned: Global infrastructure, best availability, reserved capacity for high and predictable throughput.
4. Deploy: Once deployed, the application calls the Azure OpenAI endpoint using the deployment ID 🔗, using the SDK REST API.

### Azure AI Containers



🚀 Embrace On-Premises AI with Azure: Dive into the world of on-site artificial intelligence with Azure AI containers. Our guide outlines the steps to integrate Azure's powerful AI features into your own infrastructure, ensuring control and customization.

Key Benefits and Steps:

1. 🧩 Seamless Integration: Deploy Azure's Docker containers on-premises to bring a myriad of AI services into your applications, enhancing them with capabilities like language processing and image recognition.
2. 🔒 Data Privacy & Speed: Maintain the confidentiality of your data and enjoy the benefits of quick processing by running AI services locally.
3. 🛠️ Customized AI Solutions: Tailor AI to fit your business needs with these capabilities:
   - 📝 Language Processing: Equip your apps with sophisticated text analysis and language comprehension.
   - 🗣️ Speech Recognition: Convert speech to text for voice-driven interactions.
   - 👁️ Vision Analytics: Analyze visual information for insights and automation.
   - 💡 Decision Intelligence: Build applications that make smart decisions.
4. 🔐 Secure Communication: Adjust your firewall settings to safely connect with Azure endpoints, ensuring secure operations and precise billing.
5. 💸 Flexible Pricing Options: Select the best pricing model for your needs:
   - 💳 Pay-As-You-Go: Ideal for variable workloads, pay only for what you consume.
   - 📦 Commitment Plans: Enjoy reduced rates with a set usage agreement.
   - 🌐 Disconnected Mode: Use AI services offline at a discounted rate.
6. 🏁 Getting Started: Initiate your AI journey with three essential elements:
   - 🔑 API Key: Obtain the API key for Azure AI services.
   - 💳 Billing Endpoint: Set up your billing endpoint for resource management.
   - ✅ EULA: Accept the End User License Agreement to proceed.

Azure AI containers provide an optimal blend of performance, privacy, and cost-effectiveness. Integrate these AI services into your on-premises setup and elevate your business operations today.


## Compute Options 

Azure offers a world of compute options designed to power anything from your small apps to global-scale services. With virtual machines for full control, serverless computing with Azure Functions, and containers through Kubernetes, you're equipped to build and scale faster than ever ⚡. Whether you're optimizing performance or reducing costs, Azure's flexible compute solutions have got you covered—ready to take your projects to the next level? Let Azure Compute lead the way! 🌟

### App Service Animations Overview


Above illustrates the process of using Azure App Service. We start by provisioning the App Service and App Service Plan. Here’s a step-by-step breakdown:

1. **🚀 App Service & App Service Plan**
   - **App Service**: A fully managed platform for building, deploying, and scaling web apps.
   - **App Service Plan**: Defines the region, number of instances, and pricing tier for your App Service.

2. **📈 Autoscaling**
   - **Autoscaling**: Automatically adjusts the number of instances based on demand to ensure optimal performance and cost-efficiency.

3. **🔄 Continuous Deployment**
   - **Continuous Deployment**: Seamlessly deploy updates from your favorite source control systems:
     - **Git**: Version control system for tracking changes.
     - **GitHub**: Hosting service for Git repositories.
     - **Azure DevOps**: Comprehensive suite for DevOps practices.
     - **Bitbucket**: Git repository management solution.

4. **🔐 Authentication**
   - **Built-in Authentication**: Easily enable authentication using:
     - **Microsoft Account**: Secure login with Microsoft credentials.
     - **Facebook**: Social login with Facebook.
     - **Apple Account**: Secure login with Apple ID.
     - **And more**: Support for various other identity providers.

5. **🛡️ Security**
   - **TLS/SSL**: Ensure secure communication with Transport Layer Security (TLS) and Secure Sockets Layer (SSL) certificates.

6. **🚀 Deployment Slots**
   - **Deployment Slots**: Create staging environments to test new versions before going live. Easily promote new versions with zero downtime.

7. **🌐 Traffic Manager**
   - **Traffic Manager**: Distribute traffic across multiple instances and regions. Specify the percentage of traffic for each instance to manage load effectively.

## Storage Options

Azure provides a variety of storage solutions to meet the diverse needs of modern applications. These options are designed to handle different types of data, access patterns, and performance requirements.

### Storage Account



Above illustrates the process of using an Azure Storage Account. We start by understanding the pricing tiers and the various services it offers. Here’s a step-by-step breakdown:

1. Pricing Tier: Choose the appropriate pricing tier based on your needs. Azure Storage offers different tiers to optimize cost and performance 💰.
2. Services: Azure Storage provides several services to store different types of data:
   - Blob Storage: For storing large amounts of unstructured data 📦.
   - File Storage: Managed file shares for cloud or on-premises deployments 📁.
   - Table Storage: NoSQL key-value store for rapid development 📋.
   - Queue Storage: Messaging queue for communication between application components 📬.
3. Blob Types: Understand the different types of blobs available:
   - Block Blobs: For storing text and binary data 📝.
   - Append Blobs: Optimized for append operations, such as logging 📜.
   - Page Blobs: For random read/write operations, often used for virtual hard disks 💾.
4. Access Tiers: Select the appropriate access tier based on how frequently you need to access the data:
   - Hot: For data that is accessed frequently 🔥.
   - Cool: For data that is infrequently accessed and stored for at least 30 days ❄️.
   - Cold: For data that is infrequently accessed and stored for at least 90 days 🧊.
   - Archive: For data that is rarely accessed and stored for at least 180 days 🗄️.

> **Penalties**: Be aware of the penalties associated with moving data between access tiers. For example, moving data from the Archive tier to the Hot tier may incur additional costs ⚠️.

## Security

Azure offers robust security features to protect your data and applications. These features are designed to ensure the confidentiality, integrity, and availability of your resources.

### Managed Identities in Azure: Enhancing Security Part 1



Above illustrates the process of using Managed Identities, comparing the traditional old-school way of using shared credentials to the modern approach of managed identities in Azure, highlighting enhanced security and simplified access management

1. **Traditional Approach: Shared Secrets and Credentials 🔑**

   Using shared secrets or credentials to access Azure resources has several drawbacks:
   - **Security Risks**: Potential exposure and misuse. ⚠️
   - **Maintenance Overhead**: Regularly rotating secrets is cumbersome. 🔄
   - **Complexity**: Securely distributing secrets adds complexity. 🧩

2. **Modern Approach: Managed Identities in Azure 🌐**

   Managed identities provide a secure and streamlined way to access Azure resources without managing secrets.

3. **Key Benefits 🌟**

   1. **No Secret Management**: Reduces risk of exposure. 🚫🔑
   2. **Simplified Access Control**: Integrated with Azure Active Directory (AAD). 🔐
   3. **Automatic Credential Management**: Azure handles credential rotation. 🔄🔒
   4. **Enhanced Security**: Aligns with the principle of least privilege. 🛡️

4. **Example Use Case 💡**

   Azure AI Services need to access Azure Blob Storage:
   - Assigned a managed identity. 🆔
   - Granted access (RBAC) to the Blob Storage. 🔐
   - Authenticates and accesses data without managing credentials. 🔑

5. **Conclusion 📈**

   Adopting managed identities enhances security, reduces overhead, and simplifies access management. This approach aligns with best practices for secure application development in Azure.

### Managed Identities in Azure: Enhancing Security Part 2



The animation on the left illustrates the use of system-assigned managed identities in various scenarios:

1. **Application Running in a VM** 🖥️
   - A system-assigned managed identity is created and tied to the VM.
   - This identity is used to securely access Azure resources like Azure Blob Storage.

2. **PaaS Compute Services** ☁️
   - PaaS compute services, such as Azure App Service or Azure Functions, each have their own system-assigned managed identity.
   - These identities are automatically managed by Azure and can be used to access other Azure resources securely.

3. **Document Intelligence** 📄
   - Document intelligence services also utilize system-assigned managed identities.
   - Each service has its own identity, ensuring secure and streamlined access to necessary resources.

The animation on the right illustrates the use of user-assigned managed identities:

4. **Shared Identity Across Multiple Resources** 🔄
   - A user-assigned managed identity can be created and assigned to multiple Azure resources.
   - This identity can be shared among different services, such as VMs, PaaS compute services, and Document Intelligence.

5. **Centralized Identity Management** 🛠️
   - User-assigned managed identities provide a centralized way to manage identities.
   - This approach simplifies the management of permissions and access controls across multiple resources.

6. **Flexible and Reusable** 🔄
   - User-assigned managed identities are flexible and can be reused across different resources.
   - This reduces the need to create multiple identities for different services, streamlining identity management.

7. **Key Points**

   - **Automatic Identity Management**: Each Azure resource (VM, PaaS compute, Document Intelligence) gets its own system-assigned managed identity.
   - **Secure Resource Access**: These identities can be used to connect to Azure Blob Storage without managing credentials.
   - **Isolation and Security**: Each identity is tied to a specific resource, enhancing security and isolation.

8. **Example Use Case** 💡

   - **Azure Blob Storage Access**:
      - The application in the VM, PaaS compute services, and Document Intelligence services each use their respective system-assigned managed identities.
      - These identities are granted the necessary permissions (RBAC) to access Azure Blob Storage.
      - This setup ensures secure and seamless access to storage without the need for managing secrets.

   - **Shared Identity for Multiple Resources**:
      - A user-assigned managed identity is created and assigned to the VM, PaaS compute services, and Document Intelligence services.
      - This shared identity is granted the necessary permissions (RBAC) to access Azure Blob Storage.
      - This approach simplifies identity management and provides a flexible way to manage access across multiple resources.

9. **Conclusion** 📈

   System-assigned managed identities simplify identity management and enhance security by providing each Azure resource with its own identity. User-assigned managed identities offer flexibility and centralized management by allowing a single identity to be shared across multiple resources. Both approaches align with best practices for secure application development in Azure.

# Help Wanted 📒




