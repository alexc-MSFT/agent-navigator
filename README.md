# Agent Navigator Copilot Agent <img align="right" src="assets/agent-navigator-logo.png" alt="Agent Navigator logo" width="120">
Agent Navigator is a Copilot Agent built in Copilot Studio Lite designed to help users discover and learn about Copilot agents.  

It helps you explore:
- **Public agents** available in the Agent Store
- **Organisation/Shared agents** available within your organisation

This repository contains **setup documentation and instructions** for building the agent in your own Copilot environment.  
No code is included.

---

## 🌐 Knowledge Sources

By default, **Agent Navigator is web grounded** only, allowing it to be used by all Copilot users for free including Copilot Chat (unlicensed users). 
It uses the following site to list available Copilot agents:

👉 [Copilot Agent Directory](https://agentdirectory.sharepointalex.uk/index.html)

⚠️ **Important Note:**  
This is **not an official Microsoft website**. It is a community-driven project maintained in a [separate GitHub repository](https://github.com/alexc-msft/copilot-agent-directory).  

For production use, customers are strongly advised to **create and host their own version** of this site (or an equivalent internal resource - ideally web hosted so it can be used by unlicensed users) and ground Agent Navigator in that data source.

---

## 📖 Documentation

- [Agent Instructions](docs/instructions.md) – Copy & paste these directly into your Copilot Studio agent
- [Usage Guide](docs/usage.md) – Practical examples once the agent is live
- [Customization](docs/customization.md) – Adapt Agent Navigator for your organisation
- [FAQ](docs/faq.md) – Troubleshooting

---

## 🚀 Getting Started

1. Create a new agent in Copilot Studio Lite (Agent Builder).
2. Click the 'Configure' tab and fill out the details as follows (feel free to adjust the Name/Description for your organisation):

Name: Agent Navigator
Description: Agent to recommend and help users understand which agents are available for them to use, as well as providing installation and usage instructions.

3. Copy the [Agent Instructions](docs/instructions.md) and paste these into your agent.
4. Add the website as a knowledge source - https://agentdirectory.sharepointalex.uk/index.html.
5. Configure the following 'Suggested prompts' (feel free to adjust to your needs):

Title:
Agent recommendations
Message: I work in HR, can you recommend me some agents to use?

Title:
Installation guidance
Message: How do I install the Prompt Coach agent?

   

---

## 🤝 Contributing

Contributions are welcome!  
If you’d like to improve the documentation or share setup experiences, please open an issue or PR.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

