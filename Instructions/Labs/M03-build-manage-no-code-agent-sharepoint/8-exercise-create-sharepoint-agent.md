As organizations rely more heavily on SharePoint to manage knowledge, projects, and team resources, the ability to create intelligent agents that interact with this content becomes a powerful productivity booster. Microsoft 365 Copilot makes it possible to build a SharePoint-based Copilot agent that can quickly surface information, answer questions, and assist users in navigating complex site content. This lab guides you through the process of creating your own SharePoint-connected Copilot agent, one that understands the structure and data of a real site you use every day.

Through this hands-on exercise, you learn how to create a SharePoint site, configure it as a data source, and customize your agent's behavior and responses. From onboarding support to project tracking or team resource assistance, you design and test an agent tailored to your needs. After you complete this lab, you should have a functioning SharePoint agent and a deeper understanding of how AI can make site content more accessible and actionable for users across your team or organization.

### Exercise

In this exercise, you want to create a SharePoint agent to help you get quick answers or perform useful actions that are related to a specific SharePoint site you already use. You can perform this exercise using one of the following options:

- If you have access to a SharePoint site, such as a team site, project site, or resource hub, then you can use that site.
- If you don’t have access to a SharePoint site, then you can still perform the steps in this exercise using a simulated lab environment. The simulation uses a fictitious SharePoint site for Fabrikam. 

1. If you have a site that you plan to use for this exercise, then navigate to the **Microsoft 365** home page, select **Apps** in the navigation pane, and then select **SharePoint**. Review the sites that appear in the navigation pane. The site that you select should ideally be one that contains documents, lists, or pages with project information, team resources, or other knowledge sources. For example:
   - A personal OneDrive site with shared documents.
   - A Teams-connected SharePoint site
   - A shared project or department site<br>

	Select the SharePoint site that you wish to use. 

1. If you don’t have a SharePoint site to use for this exercise, then select the following link to open the simulated lab environment in your browser: [Start the simulated SharePoint agent lab](https://cvsr8rrncj-imkzu8x04l.app.highlights.guide/sites/Mark8ProjectTeam).

    This simulation opens the Mark 8 Team Site for Fabrikam.
   
1. There are four places from which you can initiate the process to create a new agent for a site:
     - The SharePoint site's home page
     - The command bar of a document library
     - The context menu of the selected files in a document library
     - The agent chat pane

    Whether you're using your own SharePoint site or the simulated site, let's use the site's home page. On the site home page, select **+New,** and then in the drop-down menu that appears, select **Agent**.

1. On the **Create your new agent** window, the Copilot agent tool in SharePoint creates a draft version of your agent for the selected site. Notice how in the middle of the window, it indicates the source for this agent (which is your selected site). You now want to configure the agent, so select the **Edit** button. Doing so opens the **Edit agent** form. 
1. The **Create your new agent** form has three tabs - **Overview**, **Sources**, and **Behavior**. The **Overview** tab is opened first by default. From this tab, you must enter the agent's name and purpose. Default values are provided for each field, but you can change them now if you wish. 
1. The **Overview** tab also displays the default icon associated with the agent. If you’re using the simulated lab, you can’t change the agent’s icon. However, if you’re using your own personal site, you can select the **Change** option that appears below the icon if you wish to customize it. An agent icon must be a .png file that's doesn't exceed 1 MB in size. If you don't have an icon to use, proceed to the next step.
1. At this stage, notice how the **Save and close** button is enabled. You could select it at this point, but don’t do that just yet. If you did, the tool would accept the default knowledge sources and behavioral attributes for your agent. It would also make the agent live instead of keeping it in draft mode. While you could still make changes later, for the purposes of this lab, let’s continue working in draft mode to configure the remaining agent attributes. To do so, select the **Sources** tab.
1. The **Sources** tab enables you to define more sources to the draft version of your agent. The default source for a SharePoint agent is the entire SharePoint site. You can see this option in the source field, where the default value is **Sourced from entire site**. This option uses all the data sources in this site. However, if you want to select more granular sources, then select this field, and in the drop-down menu that appears, select **Sourced from document libraries, folders, or files**. You can decide which source option you prefer. If you select the **Sourced from document libraries, folders, or files** option, then complete the following steps:
   1. When you select the **Sourced from document libraries, folders, or files** option, the following option appears below it: **+Add document libraries, folders, or files**. Select this menu option, which displays the **Pick items** window.
   1. The **Pick items** window displays the **Documents** folder for the SharePoint site associated with the agent. You have two options for selecting files and folders:
      - **Select all the files and folders in the Documents library**. Choose the **Select** button to select the entire Documents library. Doing so returns you the **Sources** tab and displays **Documents** below the **Sourced from document libraries, folders, or files** field.
      - **Select specific files and folders within the Documents library**. When you select one or more files or folders, a check mark appears next to the selected files and folders. Doing so returns you the **Sources** tab and displays the selected files and folders below the **Sourced from document libraries, folders, or files** field.
1. Once you're back on the **Sources** tab, you can select the **+Add document libraries, folders, or files** option if you want to add more libraries, files, or folders.
1. Once you finish defining your sources, you should select the **Behavior** tab. The **Behavior** tab allows you to define a **Welcome** message, which is displayed when a user selects this agent in SharePoint. This message field is available in SharePoint agents, but not in Copilot Chat agents. 
1. From here, you can configure up to three starter prompts.
1. Finally, you can define the instructions for the agent using natural language text, just like you do when creating an agent in Copilot Chat.
1. Once you're done making your final changes to the SharePoint agent, select the **Save and close** button to save your changes. Since you were still in draft mode, saving the draft version of the agent converts it to a live SharePoint agent.
1. Select the **X** in the upper corner of the **Create your new agent** window to close it. Doing so returns you to the SharePoint site's home page, and the agent appears on the right side of the window. 
1. Take some time to test the agent. You can use any of the starter prompts or enter custom prompts.
1. If you’re using the simulation, then you’re now finished with this exercise. The simulation isn't programmed to edit the agent. However, if you’re using your own personal SharePoint site, then you can perform this final step if you want to make any changes to the agent. To do so, select the ellipsis icon in the upper corner of the agent pane. In the drop-down menu that appears, select **Edit agent**. Doing so opens the **Edit agent** window, which is basically a replica of the **Create your new agent** window. Navigate through the tabs to update whatever properties you want to change and then save your changes. 
