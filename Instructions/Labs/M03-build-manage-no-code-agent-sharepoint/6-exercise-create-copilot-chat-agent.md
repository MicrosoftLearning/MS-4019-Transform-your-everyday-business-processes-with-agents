In this exercise, you're encouraged to be creative and design an agent that's of significant interest to you. For example, you might want to solve a real-world business problem, improve productivity in a specific area at your company, or address a personal topic that interests you. Because each student creates their own personal agent, the instructions in this exercise focus on the structure and order of how to configure an agent rather than specifying actual values to enter in each field. It's up to you to decide what you want to enter in each field as you create your agent.

1. In your Microsoft Edge browser, sign in to the **Microsoft 365** home page (**https://www.microsoft365.com**).

1. In Microsoft 365, select **New agent** in the navigation pane. Doing so opens Agent Builder and displays the **New Agent** page. 

1. On the **New Agent** page, enter a prompt that asks Agent Builder to create your new agent. In the prompt, enter the agent’s name along with a brief description that explains what the agent is for, who its target audience is, and what you want it to do. Although you can choose a template at the bottom of the page to base your agent on, don't select a template for this exercise. The purpose of this exercise is to create a fully custom agent from scratch. 

1. After you enter a description and select the forward arrow, the **Agent Builder** form should appear for your new agent. At the top of the form is a **Describe** tab and a **Configure** tab.

    - The **Describe** tab enables you to carry on a conversation with Agent Builder. This tab is displayed by default.

    - The **Configure** tab enables you to define the detailed settings that drive the agent.

    Wait a minute or two for Agent Builder to create the agent, at which time it displays the agent’s name and description in the **Agent preview** pane.

1. If you didn't provide a name for your agent in the description that you just entered, then Agent Builder typically provides a suggested name and asks you to either confirm the name or provide a new one. You should reply accordingly.

1. At this point, Agent Builder typically prompts you to refine the description for your agent. It does so through a series of questions or suggested prompts. You can optionally respond to each question or select certain prompts until the agent's description is to your liking. 

   > [!IMPORTANT]
   > The beauty of the Agent Builder process is that it automatically translates your basic, natural language description into a complex set of instructions. This process saves you from creating this detailed instruction set on your own.

1. Once you're satisfied with the agent's description, select the **Configure** tab at the top of the form. Let’s see what Agent Builder did based on your finalized description.

1. On the **Configure** tab, ignore the **Template** and **Agent icon** options for now. In a real-world scenario, you can optionally select a template that you want to base your agent upon, and you can assign your agent a custom icon. Notice how the **Name** and **Description** fields are filled in based on your finalized description. 

1. Scroll down to the **Instructions** field. Agent Builder generated these instructions based on your initial description and the updates that you made to it on the **Describe** tab. Review the detailed level of instructions that Agent Builder generated.

1. If you wish to change the instructions, you can either manually edit them directly in the **Instructions** field, or you can ask Agent Builder to update the instructions for you.  

1. While the current instructions look good, you wonder if they could be improved upon. You aren't sure how to improve them, so you decide to ask Agent Builder what it thinks.  
    <br/>To do so, select the **Describe** tab. In the **Describe** tab, enter a prompt that asks Agent Builder what other instructions it would recommend that could improve this agent.

1. Review Agent Builder’s recommendations. If you’re pleased with its suggestions, ask Agent Builder to add them to the agent’s instructions.

1. Once Agent Builder responds that it updated the instructions, select the **Configure** tab and scroll through the **Instructions**. Note the new items that Agent Builder added.

1. Now that you’re satisfied with the instructions, you’re ready to configure the agent’s knowledge sources and suggested prompts. On the **Configure** tab, scroll down to the **Knowledge** section. You should assign any relevant data sources, such as SharePoint sites, documents, or non-Microsoft integrations, that your agent should reference.

   > [!WARNING]
   > If you don't add any public websites or work data to your agent, it might still be able to respond to your requests, but only using general capabilities of the underlying large language model (LLM), such as answering common knowledge questions, basic reasoning, or generating generalized text. As such, it's recommended that you ground your agents in specific work data or public websites; otherwise, the agent's responses might lack the context or relevance needed for business-specific tasks.

1. In the **Capabilities** section, you can optionally enable the **Code interpreter** and **Image generator** tools by selecting their toggle switches. Both tools are turned Off by default.

1. In the **Suggested prompts** section, Agent Builder Studio displays the suggested prompts that it automatically created when you entered the agent's description back on the **Describe** tab. You can edit or delete any of the existing prompts or add new ones.

1. In the **Agent preview** pane on the right side of the page, you can optionally test the agent by selecting several of the suggested prompts or submitting custom prompts. Verify the agent is correctly pulling in data from the knowledge source documents. 

1. You can test your agent as long as you want and refine your configuration if it isn't working or responding as you intended. You can do so by either manually updating the **Instructions**, or by updating the **Description**, in which case Agent Builder automatically updates the **Instructions** based on the changes you made to the **Description**.

1. Once you feel the agent is configured properly and you're satisfied with the results of the suggested prompts, select the **Create** button at the top of the page.  

1. Once the agent is created, a dialog box appears that indicates the agent was successfully created. In this dialog box, you can either go to the agent or share it. Select the **Go to agent** option.

   > [!NOTE]
   > At this stage, the agent is private and accessible only to you. In a real-world scenario where the agent needs to be used by multiple team members, you would share it with those individuals. For this training exercise, sharing isn’t required since you’re working within your own tenant.

1. On your agent's window, note how the agent appears in the navigation pane. Feel free to enter any of the starter prompts or enter any other custom prompts to run the agent. 

1. When you're done using the agent, select **All agents** in the navigation pane. In your **Agent Store** window that appears, note how your agent is displayed in the **Your agents** section. You can access this agent from the Agent Store, or you can select the pin icon that appears next to the agent in the navigation pane if you want the agent to always display under the list of agents in the pane. 
