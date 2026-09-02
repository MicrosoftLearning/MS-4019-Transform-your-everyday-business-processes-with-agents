---
lab:
  title: Create a SharePoint agent
  description: 'In this exercise, you want to create a SharePoint agent to help you get quick answers or perform useful actions that are related to a specific SharePoint site you already use.'
  duration: 20 minutes
  level: 100
  islab: true
---

# Create a SharePoint agent

As organizations rely more heavily on SharePoint to manage knowledge, projects, and team resources, the ability to create intelligent agents that interact with this content becomes a powerful productivity booster. Microsoft Copilot makes it possible to build a SharePoint-based Copilot agent that can quickly surface information, answer questions, and assist users in navigating complex site content. This lab guides you through the process of creating your own SharePoint-connected Copilot agent, one that understands the structure and data of a real site you use every day.

Through this hands-on exercise, you learn how to create a SharePoint agent from an existing SharePoint site, configure its sources, and customize the agent's behavior and responses. From onboarding support to project tracking or team resource assistance, you design and test an agent tailored to your needs. After you complete this lab, you should have a functioning SharePoint agent and a deeper understanding of how AI can make site content more accessible and actionable for users across your team or organization.

### Exercise - Create a SharePoint agent

In this exercise, you want to create a SharePoint agent to help you get quick answers or perform useful actions that are related to a specific SharePoint site you already use.

To complete this exercise, you must have access to a SharePoint site that contains pages, documents, or other content that can be used as agent knowledge sources.

Use a SharePoint site that contains content such as documents, pages, or lists. Examples include:
- A team site
- A project site
- A resource hub site
- A Teams-connected SharePoint site

1. Navigate to the **Microsoft Copilot** home page at `https://m365.cloud.microsoft.com`, select the **App Launcher** icon (grid icon) on the top left, and then select **SharePoint**.

1. If welcome messages appear, skip them.

   Review the sites that appear in the navigation pane. The site that you select should ideally be one that contains documents, lists, or pages with project information, team resources, or other knowledge sources. For example:
   - A personal OneDrive site with shared documents
   - A Teams-connected SharePoint site
   - A shared project or department site

   Select the SharePoint site that you want to use.

1. If you don't have a SharePoint site available, ask your trainer or lab administrator whether a sample site has been provisioned for this course. Otherwise, you can create a new SharePoint site (or use a personal OneDrive site) with a few sample documents so that you have content to work with for the rest of this exercise.

1. There are four places from which you can initiate the process to create a new agent for a site:
   - The SharePoint site's home page
   - The command bar of a document library or list
   - The context menu of the selected files in a document library
   - The agent chat pane

   For this exercise, use the site's home page. On the site home page, select **+ New**, and then in the drop-down menu that appears, select **Agent**.

1. On the **Create your new agent** window, SharePoint creates a draft version of the agent for the selected site. You can review and modify the agent's configuration before creating it.

1. The **Create your new agent** window includes three tabs: **Overview**, **Sources**, and **Behavior**. The **Overview** tab is displayed by default. From this tab, you can review or update the agent's name, icon, and purpose. Select the **Sources** tab to review and modify the content sources included in the agent, and select the **Behavior** tab to customize the agent's behavior.

1. The **Overview** tab also displays the default icon associated with the agent. If you want to customize it, select the **Change** option that appears below the icon. An agent icon must be a `.png` file that doesn't exceed 1 MB in size. If you don't have an icon to use, proceed to the next step.

1. The **Create agent** button is already available. While you could create the agent now using the default settings, continue configuring the agent in the remaining steps so that you can review and customize its sources and behavior before creating it. Select the **Sources** tab.

1. The **Sources** tab lets you review and manage the knowledge sources used by the agent. By default, the SharePoint site from which you created the agent is included as a source.

   To add more sources, you can use one of the following options:

   - Enter a site name or URL in the **Search by site title or enter a URL** field.

   - Select **From OneDrive** to add content from OneDrive.

   - Select the **ellipsis (...)** next to the SharePoint site and then select **Add contents from this site** to add document libraries, folders, files, pages, or lists from the current site.

   You can add up to 20 sources. Review the configured sources and add any additional sources that you want the agent to use.

   1. On the **Sources** tab, select the **ellipsis (...)** next to the SharePoint site, and then select **Add contents from this site**.

   1. The **Pick items** window opens. Browse the available libraries and lists for the site. Select the document library, folder, file, page, or list that you want to add as a knowledge source for the agent.

      - **Select all the files and folders in the Documents library**. Open the **Documents** library, select the checkbox to toggle selection for all items, and then select **Select**. You return to the **Sources** tab, where the selected files and folders appear below the SharePoint site source.

      - **Select specific files and folders within the Documents library**. Select one or more files or folders. A check mark appears next to each selected item. Select **Select** to return to the **Sources** tab, where the selected files and folders appear below the SharePoint site source.

1. Once you're back on the **Sources** tab, you can select the **+ Add contents from this site** option if you want to add more libraries, files, or folders.

   > [!NOTE]
   > You can add content from other SharePoint sites or from OneDrive by using the options available on the **Sources** tab.

1. After you finish defining your sources, select the **Behavior** tab. The **Behavior** tab allows you to define a Welcome message, which is displayed when a user selects this agent in SharePoint. This message field is available in SharePoint agents, but not in Copilot Chat agents.

1. From here, you can configure up to three starter prompts.

1. Finally, you can define the instructions for the agent using natural language text, just like you do when creating an agent in Copilot Chat.

1. After you finish making your changes to the SharePoint agent, select **Create agent** to save your changes. The draft configuration is saved and the agent is created.

   > [!NOTE]
   > If you experience any issues when creating the agent, select the **Documents** library in the navigation pane, select the folders or files that you want to use as the agent source, and then select **Copilot** &gt; **Create an agent**. This action opens the **Create your new agent** window, where you can continue to configure the agent.

1. Review the **Your agent is ready to use** confirmation message. Select **Chat with agent** to open the newly created agent. The SharePoint site's home page reappears, and the agent chat pane opens on the right side of the page.

1. Take some time to test the agent. You can use any of the starter prompts or enter custom prompts.

1. If you want to make any changes to the agent, select the **ellipsis (...)** icon in the upper-right corner of the agent pane. In the drop-down menu that appears, select **Edit agent**. The **Edit agent** window opens, which is a replica of the **Create your new agent** window. Navigate through the tabs to update the properties you want to change and then save your changes.
