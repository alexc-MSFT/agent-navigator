# Agent Navigator Copilot Agent <img align="right" src="icon.png" alt="Agent Navigator logo" width="70">

Agent Navigator is a **Proof of Concept Agent** built in Copilot Studio Lite designed to help users discover, learn and receive recommendations about Copilot agents. 

It essentially acts like an 'Agents directory' helping users to find agents. 

In it's current iteration it helps you explore:
- **Public agents** available in the Agent Store
- **Recommended agents** based on your job role/title
- **Build or use** an agent based on the users' requirements

Future iterations will bring:
- **Organisation/Shared agents** available within your organisation
- **Template** recommendations based on the users' requirements

**Note - Whilst this is a Copilot Studio Lite agent, it can equally be built in Copilot Studio and rolled out across your Organization.**

This repository contains **setup documentation and instructions** for building the agent in your own Copilot environment.  

No code is included.

---

## 🌐 Knowledge Sources

By default, **Agent Navigator is web grounded** only, allowing it to be used by all Copilot users for free including Copilot Chat (unlicensed users). 
It uses the following site to list available Copilot agents:

👉 [Copilot Agent Directory](https://agentdirectory.sharepointalex.uk/index.html)

⚠️ **Important Note:**  
This is **not an official Microsoft website**. It is a community-driven GitHub pages project maintained in a [separate GitHub repository](https://github.com/alexc-msft/copilot-agent-directory).  

For production use, customers are strongly advised to **create and host their own version** of this site (or an equivalent internal resource - ideally web hosted so it can be used by unlicensed users) and ground Agent Navigator in that data source. 

Should a Microsoft official website containing all agents in the store become available, this agent will be updated.

---

## 📖 Documentation

- [Agent Instructions](docs/Instructions.md) – Copy & paste these directly into your Copilot Studio agent
- [Customization](docs/customization.md) – Adapt Agent Navigator for your organisation

---

## 🚀 Getting Started

1. Create a new agent in Copilot Studio Lite (Agent Builder).
2. Click the '**Configure**' tab and fill out the details as follows (feel free to adjust the Name/Description for your organisation):

- **Name**: Agent Navigator
- **Description**: Agent to recommend and help users understand which agents are available for them to use, as well as providing installation and usage instructions.

3. Copy the [Agent Instructions](docs/instructions.md) and paste these into your agent.
4. Add the website as a knowledge source - https://agentdirectory.sharepointalex.uk/index.html.
5. Configure the following 'Suggested prompts' (feel free to adjust to your needs):

| Title | Message |
|----------|----------|
| Agent Recommendations 💡 👥   | I work in HR, can you recommend me some agents to use?  |
| Data & Insights 📈   | I need help with data analysis - what agents can I use?   |
| Build vs. Use 🧭    | I want to build an agent for our Project Managers - does something similar already exist?   |

6. Check the agent is working by selecting one of the suggested prompts or ask a question in the builder chat pane.
7. Click '**Create**'.
8. View and use the agent in Copilot.
9. (Optional) - Share your agent with your team/colleagues or deploy as an organization wide agent (see below).
10. (Optional) - Exclude specific agents in responses (see below). 

---

## 🏗️ Deploying Organization Wide

Should you wish to deploy the agent across your entire organization you have a few options:

- Build the agent in Copilot Studio Lite, download the manifest zip file (click the elipsis) and submit to an admin for approval in the MAC.
- Build the agent in Copilot Studio instead and use the out of the box share functionality to submit the agent for approval.

## Excluding Agents

Should you wish to exclude specific agents from being recommended or being returned in responses e.g. if an agent is blocked or not approved for use in your organization, this can be done by updating the dedicated section in the instructions. 

Simply add the names of these agents to the **Agents to Exclude** section at the bottom of the instructions.

## 🤝 Contributing

Contributions are welcome!  

If you’d like to improve the documentation or share setup experiences, please open an issue or PR.

---

## Support

This solution is open-source and community provided with no active community providing support for it. This solution is maintained by both Microsoft employees and community contributors and is not a Microsoft provided solution so there is no SLA or direct support for this from Microsoft. Please report any issues by raising an issue.

## 📜 License

This project is licensed under the [MIT License](LICENSE).

