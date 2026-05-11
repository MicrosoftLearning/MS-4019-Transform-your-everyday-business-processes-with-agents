---
lab:
  title: Analyze survey data with the Microsoft 365 Copilot Analyst agent
  description: In this scenario-based exercise, you learn how to use the Analyst agent to explore trends, identify anomalies, and generate visuals that enhance data storytelling. Whether you're reporting on team performance, customer feedback, or operational metrics, this lab shows you how to go from raw numbers to a clear summary or stakeholder-ready charts. It's a powerful way to save time, reduce manual effort, and build confidence in your analytical decision-making with AI-powered support.
  duration: 32 minutes
  level: 100
  islab: true
---

As organizations become more data-driven, the ability to quickly interpret and communicate insights from raw information is a critical skill. Microsoft 365 Copilot's Analyst agent empowers users to do just that by analyzing and visualizing data directly within familiar tools like Excel and Forms. This lab provides a practical walkthrough of how to use the Analyst agent to make sense of existing datasets—whether from surveys, spreadsheets, or poll results—and turn them into actionable insights with minimal effort.

In this scenario-based exercise, you learn how to use the Analyst agent to explore trends, identify anomalies, and generate visuals that enhance data storytelling. Whether you're reporting on team performance, customer feedback, or operational metrics, this lab shows you how to go from raw numbers to a clear summary or stakeholder-ready charts. It's a powerful way to save time, reduce manual effort, and build confidence in your analytical decision-making with AI-powered support.

### Exercise 1: Analyze survey results with the Analyst agent

You're tasked with analyzing the survey results that pertain to an internal company initiative called "Project Nexus," a six-week pilot program aimed at improving cross-departmental collaboration through a new digital workspace platform. The project involved employees from various departments including IT, HR, Marketing, and Operations, who were asked to use the platform for daily communication, document sharing, and task management. The project's goal was to evaluate the platform's effectiveness in enhancing productivity, streamlining communication, and meeting project deadlines.

After the pilot concluded, participants were surveyed to assess their satisfaction with the project, the clarity and effectiveness of communication, adherence to the proposed timeline, and their overall experience with the new system. You plan to use the Microsoft 365 Copilot's prebuilt Analyst agent to explore the survey results from Project Nexus. As with any prebuilt agent, you can enter your own custom prompts, or you can use the agent's starter prompts. The Analyst agent's starter prompts are designed to produce quantitative, qualitative, and visualization analysis, and overall project insights and recommendations.

Perform the following steps to direct the Analyst agent to interpret and visualize the survey results regarding Project Nexus:

1. Select the following link to download a copy of the [Project Nexus Survey Results](https://github.com/MicrosoftLearning/MS-4004-Empower-workforce-copilot-use-cases/raw/refs/heads/master/ResourceFiles/Project_Nexus_survey_results.xlsx). Select the **Download file** button at the top of the screen to download the file to your device.

1. In **Microsoft Edge**, open a new tab and enter the following URL: [**https://m365.cloud.microsoft.com**](https://m365.cloud.microsoft.com)

1. In **Microsoft 365**, in the navigation pane, select **Analyst** under the **Agents** section. If the **Analyst** agent doesn't appear, select **All agents** in the navigation pane, and then in the **Agent Store** window, select **Analyst** under the **Built by Microsoft** section.

1. The **Analyst** agent window appears. In the prompt field, select the **Add and manage sources** icon, which is the plus sign (**+**) icon.

1. In the menu that appears, select **Upload images and files**. In **File Explorer**, navigate to the **Downloads** folder,select the **Project Nexus Survey Results** file that you downloaded earlier, and then select **Open**.

1. In the prompt field, enter the following prompt next to the linked Project Nexus Survey Results file: `Analyze this spreadsheet and tell me the top three trends`.

   > [!NOTE]
   > Note how Analyst runs several Python commands to come up with its final list of trends. You might have to wait a minute or so for it to complete all the commands so that it can aggregate the results and determine the top three trends. Below each command is a description of the results of that command. Continue to scroll down through the results to see the top three trends.

1. To drill deeper into each category, enter the following prompt: `What is the average rating for each survey category?`

1. Review the results. If the Analyst agent suggests a next step, such as
   "Would you like a visual comparison of these averages?", enter `Yes` in
   the prompt field.

   > [!NOTE]
   > A large amount of blank space might appear between the agent's
   > response and the prompt field. If so, scroll up to find the response
   > and scroll to the bottom of the page to find the prompt field. This
   > is a known display issue that might be resolved by the time you
   > complete this exercise.

1. If necessary, scroll up to the results of the prior prompt and review them.

1. At this point, feel free to spend as much time as you want to analyze the survey results using the Analyst agent. You can enter your own custom prompts, or if you wish, try any of these prompts depending on the type of analysis you want to perform:
   - Quantitative analysis prompts:
      - `Which category received the highest average rating, and which received the lowest?`
      - `How many participants rated the project satisfaction as 4 or higher?`
      - `What percentage of participants rated timeline adherence below 3?`
      - `Can you identify any correlations between communication effectiveness and overall experience?`
   - Qualitative analysis prompts:
      - `Summarize the most common themes in the comments section.`
      - `Are there any recurring concerns or suggestions mentioned in the comments?`
      - `Identify any comments that mention issues with communication or timeline.`
   - Insight and recommendation prompts:
      - `Based on the survey data, what are the top three strengths of Project Nexus?`
      - `What are the key areas for improvement suggested by the participants?`
      - `Provide a summary report of the survey findings with actionable recommendations.`
   - Quantitative visualization prompts:
      - `Generate a pie chart of overall ratings distribution.`
      - `Create a bar chart comparing the average ratings for Project Satisfaction, Communication Effectiveness, Timeline Adherence, and Overall Experience.`
      - `Plot a histogram of the satisfaction ratings to see the distribution of ratings.`
      - `Generate a scatter plot to analyze the relationship between Communication Effectiveness and Overall Experience.`
      - `Create a correlation heatmap for all numeric rating categories.`
      - `Make a box plot for each rating category to show the range and quartiles.`
      - `Plot a line graph showing timeline adherence ratings over participants ordered by Participant ID.`
