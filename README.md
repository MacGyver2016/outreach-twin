# outreach-twin
2025 Global AI Hackathon Project: Hackathon Sponsor & Participant Outreach AI

## Project Description
AI-powered outreach system built with CrewAI to streamline sponsor and participant recruitment for hackathons and non-profit events. Agents identify mission-aligned corporate sponsors worldwide and target colleges with ideal student participants, generating tailored communication plans in minutes. Designed to be easily adapted for other events—especially for resource-limited non-profits—this tool runs free of AI credit costs while keeping the organization’s mission at the forefront.

## Quick Start
*I created the project and have only had the chance to run it on GoogleColab.*
1. Open the Fundraising_and_Recruitment_Outreach.ipynb file.
2. Input your api keys in the third cell.
3. Run all cells in order.
*The output of the last cell in the Sponsorship section with have a detailed sponsorship plan for each of the potential sponsors identified. The output of the last cell in the Participant section with have a detailed recruitment plan for each college identified.*

## Not-As-Quick Start
After completing steps 1 and 2 from the quick start, there are a few quick things you can do to change up the models you want to use or **customize the project to work for your company**.
- If you want to add image creation functionality, instead of a description of an image, go to the first cell in the Sponsorship section and add "dalle_tool" to the list where indicated. Keep in mind that you must have OpenAI credits for this to work.
- If you'd prefer to use a different AI than Gemini, go to the 5th cell and change model to your preferred LLM.
- If you have the AI credits to spare and would like your output to happen faster, you can go to the third cell in both the Sponsorship and Participant sections and change the max_rpm to your model's max_rpm.
- To **customize this project for your company or event**, go to cell four. Comment out the lines that show "company_name" through "company_event" and uncomment the alternative lines of code. Now when you run the code, you will prompted to input information about your organization that the AI agents will use to customize your results.
