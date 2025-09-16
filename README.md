# Agent Navigator Copilot Agent <img align="right" src="assets/agent-navigator-logo.png" alt="Agent Navigator logo" width="120">
Agent Navigator is a Copilot Agent built in Copilot Studio Lite designed to help users discover and learn about Copilot agents.  

It helps you explore:
- **Public agents** available in the Agent Store
- **Internal/Shared agents** available within your organisation

This repository contains **setup documentation and instructions** for building the agent in your own Copilot environment.  
No code is included.

---

## 🌐 Web Grounding

By default, **Agent Navigator is web grounded** to provide up-to-date information.  
It uses the following site to list available Copilot agents:

👉 [Copilot Agent Directory](https://alexc-msft.github.io/copilot-agent-directory/index.html)

⚠️ **Important Note:**  
This is **not an official Microsoft website**. It is a community-driven project maintained in a [separate GitHub repository](https://github.com/alexc-msft/copilot-agent-directory).  

For production use, customers are strongly advised to **create and host their own version** of this site (or an equivalent internal resource) and ground Agent Navigator in that data source.

---

## 🏢 Organisation-Specific Customisation

Agent Navigator can also be customised to return details of **agents available in your organisation**.  

- In the **initial version**, this data is **manually maintained** in a SharePoint list.  
- The [Customization Guide](docs/customization.md) explains how to configure this option.  
- In the future, when Microsoft Graph API endpoints for agent discovery become available, this process can be automated.

---

## 📖 Documentation

- [Setup Guide](docs/setup.md) – how to configure and publish Agent Navigator
- [Agent Instructions](docs/instructions.md) – copy & paste these directly into your Copilot Studio agent
- [Usage Guide](docs/usage.md) – practical examples once the agent is live
- [Customization](docs/customization.md) – adapt Agent Navigator for your organisation
- [FAQ](docs/faq.md) – troubleshooting

---

## 🚀 Getting Started

1. Follow the [Setup Guide](docs/setup.md).
2. Copy the [Agent Instructions](docs/instructions.md) into your Copilot Studio agent.
3. Publish and start exploring agents available to you and your team.

---

## 🤝 Contributing

Contributions are welcome!  
If you’d like to improve the documentation or share setup experiences, please open an issue or PR.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

