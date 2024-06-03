<h1 align="center">Creating a Resource Group (for IAM user)</h1>

<h2>Links:</h2>

- [Google Doc](https://docs.google.com/document/d/1uvH1xt40GQVH9PJe3dRQ7eJF6HBQaVdKAmTkoXzQQXY/edit?usp=sharing)
- [Github Repo](https://github.com/ImranHuhn/AzureRGIAM)
- [Blog](http://www.techdeficient.com/2024/06/creating-resource-group-for-iam-user.html)

<h2>TLDR: Create “Resource group” (for IAM User)</h2>

- <b>Introduction: </b>Essential step for efficient Azure resource management; simplifies administration, enhances security, and incurs no cost unless resources are added.

- <b>Navigate and Create: </b>Access the Azure portal, navigate to "Resource Groups", and click "Create" to set up a new resource group.

- <b>Project and Resource Details: </b>Enter a unique name, choose a location, and review all details in the "Basic" section before proceeding.

- <b>Review Information: </b>Skip the Tags section, review and validate all inputs, and finalize the creation once validation is passed.

- <b>Completion: </b>Confirm the new resource group is listed and matches the setup details; make adjustments if necessary for accuracy.

<h2>How to read each section (in this order)</h2>

<b>Section-Intro</b> 
- <b>Title: </b>Name of the section.
- <b>Description: </b>Describe what the section entails. Some sections won’t have descriptions. 

<b>Image</b> 
- <b>Numbering: </b>Within the images are sequential numbers, with corresponding text explanations directly below each image.
- <b>Yellow highlights: </b>Yellow highlights are navigation aids to help identify your current section in the Azure portal.

<b>Text numbers</b> 
- <b>Numbers: </b>Each number provides a brief explanation of the image directly above it.

<b>Side notes</b> 
- <b>Notes: </b>Any extra details you should be aware of.

<h2>Introduction</h2>

&nbsp;&nbsp;&nbsp;&nbsp;Creating a Resource Group for an IAM user is a fundamental step in managing Azure resources efficiently. By organizing resources into groups, you can simplify management, streamline access control, and enhance security. This guide will walk you through the process of setting up a new resource group in the Azure portal, ensuring that all necessary details are accurately entered. Remember, creating resource groups incurs no cost unless resources are added to them. Following these steps will help you establish a well-structured environment for your IAM users.

Note: Creating resource groups should not incur costs. Costs are only incurred when resources are added into the resource group.

<h2>Navigate and create a Resource Group</h2>

<b>Description: </b>We will start by navigating to the relevant section in the Azure portal. From there, we will proceed with the steps to add a new resource group, entering the necessary details and finalizing the process.

![01_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/53f4e086-7aea-438c-a0ca-1fb44edcd56b)

1.  After reaching the "Resource Groups" section, click on "Create" to set up a new resource group.

<h2>Project details & Resource details</h2>

<b>Description: </b>In this section, you will be in the "Basic" area, which includes fields for project details and resource details. You need to provide a unique name for the resource group and choose a location from the available list. Additionally, you may be required to select a subscription and specify a resource group tag if necessary. After filling out these fields, review the information to ensure accuracy before proceeding to the next step.

![02_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/f621b17e-5584-4f96-a176-9b21e37e8911)

1.  Enter a unique name for the resource group.
2.  Select the location nearest to you.
3.  Click "Next: Tags" once you're satisfied with your entries.

<h2>Review information</h2>

<b>Description: </b>You will skip the Tags section and proceed directly to the "Review + Create" section. In this step, your main task is to review all the information you have entered to ensure it is correct. Azure will automatically validate your inputs during this process. Once the validation is complete and everything looks good, you can proceed to finalize the creation of your resource group.

![03_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/c33f5a67-61ba-479e-8c74-41d4ee52b84e)

1.  Once you see "Validation passed," click "Next."

<h2>Resource group creation completed</h2>

<b>Description: </b>We have successfully created the resource group. The next step is to confirm that everything has been set up correctly. This involves checking the newly added resource group to ensure that the details align with the information provided during the setup process. If everything matches, the resource group is ready for use. If discrepancies are found, adjustments may be needed to ensure accuracy.

![04_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/09b02899-cc02-4751-b6f0-cac7bd92e1d9)

1.  Click the bell notification icon to check the status of the build in the right panel.
2.  Ensure the right panel displays "Resource group created."
3.  Verify if the new resource group you created is listed in the center of the dashboard. If it is not visible, click on the refresh button.
4.  As you can see, the resource group is listed, confirming that it has been successfully set up.

<h2>Conclusion</h2>

&nbsp;&nbsp;&nbsp;&nbsp;Successfully setting up a resource group is crucial for organizing and managing Azure resources effectively. By following the outlined steps, you can ensure that your resource group is configured correctly, providing a solid foundation for further resource management. This process not only simplifies administration but also enhances security and access control for IAM users. Regularly verifying and reviewing your resource groups ensures they remain aligned with your project needs. With this setup, you are well-prepared to manage your Azure environment efficiently and securely.
