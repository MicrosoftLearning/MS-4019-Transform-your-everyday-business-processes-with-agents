---
lab:
  title: Use the Analyst agent
  description: In this scenario-based exercise, you learn how to use the Analyst agent to explore trends, identify anomalies, and generate visuals that enhance data storytelling. Whether you're reporting on team performance, customer feedback, or operational metrics, this lab shows you how to go from raw numbers to a clear summary or stakeholder-ready charts. It's a powerful way to save time, reduce manual effort, and build confidence in your analytical decision-making with AI-powered support.
  duration: 15 minutes
  level: 100
  islab: true
---

# Use the Analyst agent

As organizations become more data-driven, the ability to interpret raw data and communicate meaningful insights is increasingly important. The Analyst agent in Microsoft Copilot helps you analyze and visualize data from sources such as Excel and Forms by using natural-language prompts. In this scenario-based lab, you'll use the Analyst agent to explore trends, identify anomalies, and create visualizations from survey data. You'll see how the agent can turn raw data into clear summaries and stakeholder-ready charts, reducing the time and manual effort required to analyze results.

In this scenario-based exercise, you learn how to use the Analyst agent to explore trends, identify anomalies, and generate visuals that enhance data storytelling. Whether you're reporting on team performance, customer feedback, or operational metrics, this lab shows you how to go from raw numbers to a clear summary or stakeholder-ready charts. It's a powerful way to save time, reduce manual effort, and build confidence in your analytical decision-making with AI-powered support.

### Exercise - Analyze survey results with the Analyst agent

You're tasked with analyzing the survey results from an internal company initiative called Project Nexus, a six-week pilot program designed to improve collaboration between departments through a new digital workspace platform. Employees from IT, HR, Marketing, and Operations used the platform for daily communication, document sharing, and task management.

The goal of the pilot was to evaluate whether the platform could improve productivity, streamline communication, and help employees complete project work on time. After the pilot, participants completed a survey about their satisfaction with the project, the effectiveness of communication, adherence to the project timeline, and their overall experience with the platform.

You'll use the prebuilt Analyst agent in Microsoft Copilot to explore the survey results stored in an Excel workbook. You can enter your own prompts or use the agent's starter prompts to analyze the data, create visualizations, identify useful insights, and generate recommendations.

Complete the following steps to interpret and visualize the Project Nexus survey results using the Analyst agent.

1. In a web browser, go to the following link to access a copy of the **Project Nexus Survey Results**: `https://github.com/MicrosoftLearning/MS-4004-Empower-workforce-copilot-use-cases/raw/refs/heads/master/ResourceFiles/Project_Nexus_survey_results.xlsx`. Select the **Download file** button at the top of the screen to save the file to your device.

1. Open a new browser tab, navigate to **Microsoft Copilot** at `https://m365.cloud.microsoft.com`, and sign in using your credentials for this exercise.

1. If prompted, choose the option to stay signed in.

1. Skip any Welcome messages that appear.

1. In **Microsoft Copilot**, in the navigation pane, select **Analyst** under the **Agents** section. If the **Analyst** agent doesn't appear, select **More agents**, and then in the **Agent Store** window, select **Analyst** under the **Built by Microsoft** section.

1. The **Analyst** agent window appears. In the prompt field, select the **Add and manage sources** icon, which is the plus sign (**+**) icon.

1. In the menu that appears, select **Upload images and files**. In **File Explorer**, navigate to the **Downloads** folder, select the **Project Nexus Survey Results** file that you downloaded earlier, and then select **Open**.

1. In the prompt field, enter the following prompt next to the linked Project Nexus Survey Results file: `Analyze this spreadsheet and tell me the top three trends`.

   > [!NOTE]
   > Note how Analyst runs several Python commands to come up with its final list of trends. You might have to wait a minute or so for it to complete all the commands so that it can aggregate the results and determine the top three trends. Below each command is a description of the results of that command. Continue to scroll down through the results to see the top three trends.

1. To drill deeper into each category, enter the following prompt: `What is the average rating for each survey category?`

1. Review the Analyst agent's response. If the agent suggests a follow-up action or asks whether you want to create a visual comparison, enter `Yes` in the prompt field and submit your response. If the agent doesn't offer to create a visual comparison, enter the following prompt: `Create a bar chart comparing the average ratings for Project Satisfaction, Communication Effectiveness, Timeline Adherence, and Overall Experience.`

   > [!NOTE]
   > A large amount of blank space might appear between the agent's
   > response and the prompt field. If so, scroll up to find the response
   > and scroll to the bottom of the page to find the prompt field. This
   > is a known display issue that might be resolved by the time you
   > complete this exercise.

1. If necessary, scroll up to the results of the prior prompt and review them.

1. At this point, you can spend as much time as you want analyzing the survey results using the Analyst agent. You can enter your own custom prompts, or try any of these prompts depending on the type of analysis you want to perform:
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
      - `Create a radar chart comparing the average ratings across all survey categories.`
      - `Plot a histogram of the satisfaction ratings to see their distribution.`
      - `Generate a scatter plot to analyze the relationship between Communication Effectiveness and Overall Experience.`
      - `Create a correlation heatmap for all numeric rating categories.`
      - `Make a box plot for each rating category to show the range and quartiles.`
      - `Plot a line graph showing timeline adherence ratings over participants ordered by Participant ID.`
