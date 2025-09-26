# Agent Navigator Copilot Agent <img align="right" src="assets/agent-navigator-logo.png" alt="Agent Navigator logo" width="120">
Agent Navigator is a Copilot Agent built in Copilot Studio Lite designed to help users discover, learn and receive recommendations about Copilot agents.  

In it's current iteration it helps you explore:
- **Public agents** available in the Agent Store
- **Recommended agents** based on your job role/title
- **Build or use** an agent based on your requirements

Future iterations will bring:
- **Organisation/Shared agents** available within your organisation
- **Template** recommendations based on your requirements

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

- [Agent Instructions](docs/instructions.md) – Copy & paste these directly into your Copilot Studio agent
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

---

## 🏗️ Deploying Organization Wide

Should you wish to deploy the agent across your entire organization you have a few options:

- Build the agent in Copilot Studio Lite, download the manifest zip file (click the elipsis) and submit to an admin for approval in the MAC.
- Build the agent in Copilot Studio instead and use the out of the box share functionality to submit the agent for approval.

## 🤝 Contributing

Contributions are welcome!  

If you’d like to improve the documentation or share setup experiences, please open an issue or PR.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

