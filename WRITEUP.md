# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

**App Service:** The costs, scalability, and availability for deploying a CMS app via an App Service are favorable. Given the app's lightweight nature, it doesn't require substantial computational resources. Although the billing for service plans is continuous, even during inactive periods, the minimal compute needs of the CMS app keep expenses low. The integration of continuous deployment with GitHub workflows in the Azure portal simplifies updates, making maintenance effortless.

**VM:** Deploying a CMS app on a Virtual Machine (VM) also offers reasonable costs, scalability, and availability. The VM platform provides greater flexibility in customizing the app’s capabilities. This setup is particularly advantageous for developers with pre-existing CMS applications not supported by App Service, as the VM allows for detailed customization to fine-tune the app for optimal performance.

**My Choice:** I opted for the App Service because the CMS app is lightweight, requiring minimal computational power, and benefits from the straightforward deployment capabilities of Azure. The CMS app, which utilizes a Python codebase, is well-supported by App Service. This made the choice quite straightforward.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If we decided to work with the new coding language or some new technology that does not supported by Azure. I will be very difficult to keep using App Service. 

