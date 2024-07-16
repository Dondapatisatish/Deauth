<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">DEAUTH</h1>
</p>
<p align="center">
    <em><code>► Wi-Fi deauthentication, often abbreviated as Wi-Fi deauth, refers to a technique used in network security to disconnect devices from a Wi-Fi network forcefully. This method is typically employed to mitigate security risks by terminating unauthorized or suspicious connections.

In practical terms, Wi-Fi deauthentication works by sending specially crafted packets (deauthentication frames) to targeted devices, prompting them to disconnect from the network. This process does not require authentication credentials but exploits the inherent vulnerability of Wi-Fi communication protocols.
<br>
Common applications of Wi-Fi deauthentication include network monitoring, testing network security defenses, and enforcing policies on network access. It serves as a valuable tool for administrators and security professionals to maintain the integrity and confidentiality of Wi-Fi networks against potential threats and unauthorized access attempts.</code></em>

</p>
<p align="center">
	<img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="license">
	<img src="https://img.shields.io/github/last-commit/Dondapatisatish/Deauth.git?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Dondapatisatish/Deauth.git?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Dondapatisatish/Deauth.git?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)
</details>
<hr>

##  Overview

<code>► Overview of Wi-Fi Deauthentication with Python <br>
Wi-Fi deauthentication using Python involves leveraging the capabilities of Python programming to perform network security tasks, specifically disconnecting devices from Wi-Fi networks through deauthentication attacks. This technique is typically used for ethical hacking, network testing, or ensuring network security.
Understanding Wi-Fi Deauthentication
<br>
Wi-Fi deauthentication is a method that exploits the IEEE 802.11 protocol to force devices connected to a Wi-Fi network to disconnect. It works by sending specially crafted deauthentication packets to targeted devices, which effectively terminate their connection to the network. This can be done without requiring authentication credentials, making it a potent tool for network administrators and security professionals.
Python for Wi-Fi Deauthentication
<br>
Python provides several libraries and frameworks that facilitate the implementation of Wi-Fi deauthentication attacks. Some of the commonly used libraries include:
<br>
   > 1. Scapy: A powerful Python library used for crafting and sending packets, including deauthentication frames. It allows precise control over packet contents and network interactions.

   > 2. Wireless: A Python module that provides access to wireless network interfaces, enabling operations such as scanning for networks, connecting to networks, and sending deauthentication packets.

   > 3. Aircrack-ng: Although primarily a suite of tools for auditing wireless networks, Aircrack-ng can be scripted in Python for automating Wi-Fi deauthentication attacks among other tasks.
<br>
Applications of Python for Wi-Fi Deauthentication

   > 1. Penetration Testing: Security professionals use Python scripts to assess the resilience of Wi-Fi networks against unauthorized access attempts and attacks.

   > 2. Network Monitoring: Python scripts can continuously monitor Wi-Fi networks for suspicious activities and initiate defensive actions like deauthentication when anomalies are detected.

   > 3. Security Research: Researchers and developers use Python to experiment with new techniques for securing Wi-Fi networks or developing countermeasures against deauthentication attacks.
<br>
Getting Started with Python for Wi-Fi Deauthentication
<br>
To get started with Python for Wi-Fi deauthentication:

   > 1. Install Python: Ensure Python is installed on your system. Python 3.x is recommended.

   > 2. Choose a Library: Select a Python library like Scapy or Wireless based on your requirements for crafting and sending deauthentication packets.

   > 3. Write Scripts: Develop Python scripts that utilize the chosen library to send deauthentication frames to specific devices or across a network.

   > 4. Execute Scripts: Run your Python scripts to initiate and monitor Wi-Fi deauthentication attacks, observing their impact on target devices and network behavior.
<br>
Conclusion
<br>
Python empowers security professionals and developers with a versatile toolkit for implementing Wi-Fi deauthentication attacks and related network security tasks. By leveraging Python's capabilities, practitioners can enhance their understanding of network vulnerabilities and strengthen defenses against malicious activities in Wi-Fi environments.</code>

---

##  Features

<code> ► 
<br>
Wi-Fi deauthentication, as a technique in network security, encompasses several key features and functionalities that make it a valuable tool for both defensive and offensive purposes. Here are the main features of Wi-Fi deauthentication:

   1. Forceful Disconnection: Wi-Fi deauthentication allows for the forceful disconnection of devices from a Wi-Fi network without requiring authentication credentials. This is achieved by sending deauthentication frames (packets) to targeted devices.

   2. Protocol Exploitation: It exploits vulnerabilities in the IEEE 802.11 protocol to send specially crafted management frames that appear legitimate to the devices, prompting them to disconnect from the network.

   3. Stealth Operations: Deauthentication attacks can be performed discreetly, without alerting users or administrators of the network, making them suitable for testing network defenses and security posture.

   4. Network Monitoring: It serves as a means to monitor network security by detecting unauthorized devices or preventing unauthorized access attempts. Administrators can use deauthentication to enforce security policies and ensure compliance.

   5. Penetration Testing: Security professionals use deauthentication as part of penetration testing (pen testing) to evaluate the resilience of Wi-Fi networks against attacks and to identify potential vulnerabilities.

   6. Defense Mechanism: While primarily used for offensive security practices, understanding deauthentication helps in developing defensive strategies against such attacks, such as implementing intrusion detection systems (IDS) or network monitoring tools.

   7. Scriptable Automation: Deauthentication attacks can be automated through scripting languages like Python, allowing for the creation of custom tools and frameworks for testing and security research.

   8. Legal Considerations: It's important to note that performing Wi-Fi deauthentication attacks without proper authorization is illegal in many jurisdictions unless conducted under controlled conditions for legitimate security testing and research purposes.

   9. Impact Assessment: By initiating deauthentication attacks, security professionals can assess the impact on network performance, device behavior, and user experience, helping to refine network security policies and configurations.

   10. Educational Purposes: Understanding how deauthentication attacks work and their potential impact helps in educating network administrators, developers, and security practitioners about Wi-Fi security best practices and defense strategies.
<br>
Overall, Wi-Fi deauthentication plays a crucial role in the realm of network security by providing insights into vulnerabilities, enabling proactive defense measures, and supporting responsible security testing and research efforts. </code>

---

##  Repository Structure

```sh
└── Deauth/
    ├── requirements.txt
    └── wifi_deauth.py
```

---

##  Modules

<details closed><summary>.</summary>

| File                                                                                           | Summary                         |
| ---                                                                                            | ---                             |
| [requirements.txt](https://github.com/Dondapatisatish/Deauth.git/blob/master/requirements.txt) | <code>► 
scapy==2.4.5
colorma==0.9.2 </code> |
| [wifi_deauth.py](https://github.com/Dondapatisatish/Deauth.git/blob/master/wifi_deauth.py)     | <code>► wifi_deauth.py</code> |

</details>

---

##  Getting Started

**System Requirements:**

* **Python**: `version 3.7 above`

###  Installation

<h4>From <code>source</code></h4>

> 1. Clone the Deauth repository:
>
> ```console
> $ git clone https://github.com/Dondapatisatish/Deauth.git
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd Deauth
> ```
>
> 3. Install the dependencies:
> ```console
> $ pip install -r requirements.txt
> ```

###  Usage

<h4>From <code>source</code></h4>

> Run Deauth using the command below:
> ```console
> $ python wifi_deauth.py
> ```

###  Tests

> Run the test suite using the command below:
> ```console
> $ pytest
> ```

---

##  Project Roadmap

`Objective: Establish the foundational structure and basic functionality of the Wi-Fi deauthentication tool.

- [X] `► Set up project repository and version control.`
- [X] `► Define project scope and objectives.`
- [X] `► Research and select necessary libraries and tools (e.g., Scapy for packet manipulation).`
- [X] `► Implement basic command-line interface (CLI) for initiating deauthentication attacks.`


---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/Dondapatisatish/Deauth.git/issues)**: Submit bugs found or log feature requests for the `Deauth` project.
- **[Submit Pull Requests](https://github.com/Dondapatisatish/Deauth.git/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Dondapatisatish/Deauth.git/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/Dondapatisatish/Deauth.git
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/Dondapatisatish/Deauth.git/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=Dondapatisatish/Deauth.git">
   </a>
</p>
</details>

---

##  License

This project is protected under the [MIT](https://github.com/Dondapatisatish/Deauth/blob/main/LICENSE) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/mit/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-overview)

---
