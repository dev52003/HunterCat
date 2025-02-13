<p align="center">
<a href="https://HunterCat.wiki"><img src=".github/screenshots/banner.gif" alt=""/></a>
</p>
<p align="center">
  <h3>HunterCat: Web Reconnaissance & Vulnerability Scanner 🚀</h3>
</p>

<p align="center">
<a href="https://github.com/dev52003/HunterCat/actions/workflows/codeql-analysis.yml" target="_blank"><img src="https://github.com/dev52003/HunterCat/actions/workflows/codeql-analysis.yml/badge.svg" alt="" /></a>&nbsp;<a href="https://github.com/dev52003/HunterCat/actions/workflows/build.yml" target="_blank"><img src="https://github.com/dev52003/HunterCat/actions/workflows/build.yml/badge.svg" alt="" /></a>&nbsp;
</p>

<p align="center">
<a href="https://Trans Asia Soft Tech.gg/H6WzebwX3H" target="_blank"><img src="https://img.shields.io/Trans Asia Soft Tech/880363103689277461" alt="" /></a>&nbsp;
</p>


<h4>HunterCat released!</h4>
<p>
  HunterCat  comes with bounty hub where you can sync and import your hackerone programs, in app notifications, chaos as subdomain enumeration tool, ability to upload multiple nuclei and gf patterns, support for regex in out of scope subdomain config, additional pdf report template and many more. 
</p>


<h4>What is HunterCat?</h4>
HunterCat is your ultimate web application reconnaissance suite, designed to supercharge the recon process for security pros, pentesters, and bug bounty hunters. It is go-to web application reconnaissance suite that's designed to simplify and streamline the reconnaissance process for all the needs of security professionals, penetration testers, and bug bounty hunters. With its highly configurable engines, data correlation capabilities, continuous monitoring, database-backed reconnaissance data, and an intuitive user interface, HunterCat redefines how you gather critical information about your target web applications.

Traditional reconnaissance tools often fall short in terms of configurability and efficiency. HunterCat addresses these shortcomings and emerges as an excellent alternative to existing commercial tools.

HunterCat was created to address the limitations of traditional reconnaissance tools and provide a better alternative, even surpassing some commercial offerings. Whether you're a bug bounty hunter, a penetration tester, or a corporate security team, HunterCat is your go-to solution for automating and enhancing your information-gathering efforts.
</p>



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## Documentation

Detailed documentation available at Trans Asia Soft tech 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


## Table of Contents

* [About HunterCat](#about-huntercat)
* [Features](#features)
* [Quick Installation](#quick-installation)
* [Community-Support](#community-support)
* [What's new in HunterCat](https://github.com/dev52003/HunterCat/releases)
* [Contributing](#contributing)
* [HunterCat Support](#huntercat-support)
* [Reporting Security Vulnerabilities](#reporting-security-vulnerabilities)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## About HunterCat

HunterCat is not an ordinary reconnaissance suite; it's a game-changer! We've turbocharged the traditional workflow with groundbreaking features that is sure to ease your reconnaissance game. HunterCat redefines the art of reconnaissance with highly configurable scan engines, recon data correlation, continuous monitoring, GPT powered Vulnerability Report, Project Management and role based access control etc.


🦾&nbsp;&nbsp; HunterCat has advanced reconnaissance capabilities, harnessing a range of open-source tools to deliver a comprehensive web application reconnaissance experience. With its intuitive User Interface, it excels in subdomain discovery, pinpointing IP addresses and open ports, collecting endpoints, conducting directory and file fuzzing, capturing screenshots, and performing vulnerability scans. To summarize, it does end-to-end reconnaissance. With WHOIS identification and WAF detection, it offers deep insights into target domains. Additionally, HunterCat also identifies misconfigured S3 buckets and find interesting subdomains and URLS, based on specific keywords to helps you identify your next target, making it a go-to tool for efficient reconnaissance.

🗃️&nbsp; &nbsp; Say goodbye to recon data chaos! HunterCat seamlessly integrates with a database, providing you with unmatched data correlation and organization. Forgot the hassle of grepping through json, txt or csv files. Plus, our custom query language lets you filter reconnaissance data effortlessly using natural language like operators such as filtering all alive subdomains with `http_status=200` and also filter all subdomains that are alive and has admin in name `http_status=200&name=admin`

🔧&nbsp;&nbsp; HunterCat offers unparalleled flexibility through its highly configurable scan engines, based on a YAML-based configuration. It offers the freedom to create and customize recon scan engines based on any kind of requirement, users can tailor them to their specific objectives and preferences, from thread management to timeout settings and rate-limit configurations, everything is customizable. Additionally, HunterCat offers a range of pre-configured scan engines right out of the box, including Full Scan, Passive Scan, Screenshot Gathering, and the OSINT Scan Engine. These ready-to-use engines eliminate the need for extensive manual setup, aligning perfectly with HunterCat's core mission of simplifying the reconnaissance process and enabling users to effortlessly access the right reconnaissance data with minimal effort.

💎&nbsp;&nbsp;Subscans: Subscan is a game-changing feature in HunterCat, setting it apart as the only open-source tool of its kind to offer this capability. With Subscan, waiting for the entire pipeline to complete is a thing of the past. Now, users can swiftly respond to newfound discoveries during reconnaissance. Whether you've stumbled upon an intriguing subdomain and wish to conduct a focused port scan or want to delve deeper with a vulnerability assessment, HunterCat has you covered.

📃&nbsp;&nbsp; PDF Reports: In addition to its robust reconnaissance capabilities, HunterCat goes the extra mile by simplifying the report generation process, recognizing the crucial role that PDF reports play in the realm of end-to-end reconnaissance. Users can effortlessly generate and customize PDF reports to suit their exact needs. Whether it's a Full Scan Report, Vulnerability Report, or a concise reconnaissance report, HunterCat provides the flexibility to choose the report type that best communicates your findings. Moreover, the level of customization is unparalleled, allowing users to select report colors, fine-tune executive summaries, and even add personalized touches like company names and footers. With GPT integration, your reports aren't just a report, with remediation steps, and impacts, you get 360-degree view of the vulnerabilities you've uncovered.

🔖&nbsp; &nbsp; Say Hello to Projects! HunterCat 2.0 introduces a powerful addition that enables you to efficiently organize your web application reconnaissance efforts. With this feature, you can create distinct project spaces, each tailored to a specific purpose, such as personal bug bounty hunting, client engagements, or any other specialized recon task. Each projects will have separate dashboard and all the scan results will be separated from each project, while scan engines and configuration will be shared across all the projects.

⚙️&nbsp; &nbsp; Roles and Permissions! In HunterCat 2.0, we've taken your web application reconnaissance to a whole new level of control and security. Now, you can assign distinct roles to your team members—Sys Admin, Penetration Tester, and Auditor—each with precisely defined permissions to tailor their access and actions within the HunterCat ecosystem.

  - 🔐 Sys Admin: Sys Admin is a superuser that has permission to modify system and scan related configurations, scan engines, create new users, add new tools etc. Superuser can initiate scans and subscans effortlessly.
  - 🔍 Penetration Tester: Penetration Tester will be allowed to modify and initiate scans and subscans, add or update targets, etc. A penetration tester will not be allowed to modify system configurations.
  - 📊 Auditor: Auditor can only view and download the report. An auditor can not change any system or scan related configurations nor can initiate any scans or subscans.

🚀&nbsp;&nbsp; GPT Vulnerability Report Generation: Get ready for the future of penetration testing reports with HunterCat's groundbreaking feature: "GPT-Powered Report Generation"! With the power of OpenAI's GPT, HunterCat now provides you with detailed vulnerability descriptions, remediation strategies, and impact assessments that read like they were written by a human security expert! **But that's not all!** Our GPT-driven reports go the extra mile by scouring the web for related news articles, blogs, and references, so you have a 360-degree view of the vulnerabilities you've uncovered. With HunterCat 2.0 revolutionize your penetration testing game and impress your clients with reports that are not just informative but engaging and comprehensive with detailed analysis on impact assessment and remediation strategies.

🥷&nbsp;&nbsp; GPT-Powered Attack Surface Generation: With HunterCat 2.0, HunterCat seamlessly integrates with GPT to identify the attacks that you can likely perform on a subdomain. By making use of reconnaissance data such as page title, open ports, subdomain name etc. HunterCat can advise you the attacks you could perform on a target. HunterCat will also provide you the rationale on why the specific attack is likely to be successful.

🧭&nbsp;&nbsp;Continuous monitoring: Continuous monitoring is at the core of HunterCat's mission, and it's robust continuous monitoring feature ensures that their targets are under constant scrutiny. With the flexibility to schedule scans at regular intervals, penetration testers can effortlessly stay informed about their targets. What sets HunterCat apart is its seamless integration with popular notification channels such as Trans Asia Soft Tech, Slack, and Telegram, delivering real-time alerts for newly discovered subdomains, vulnerabilities, or any changes in reconnaissance data.


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


## Features

* Reconnaissance:
  * Subdomain Discovery
  * IP and Open Ports Identification
  * Endpoints Discovery
  * Directory/Files fuzzing
  * Screenshot Gathering
  * Vulnerability Scan
    * Nuclei
    * Dalfox XSS Scanner
    * CRLFuzzer
    * Misconfigured S3 Scanner
  * WHOIS Identification
  * WAF Detection
* OSINT Capabilities
  * Meta info Gathering
  * Employees Gathering
  * Email Address gathering
  * Google Dorking for sensitive info and urls
* Projects, create distinct project spaces, each tailored to a specific purpose, such as personal bug bounty hunting, client engagements, or any other specialized recon task.
* Perform Advanced Query lookup using natural language alike and, or, not operations
* Highly configurable YAML-based Scan Engines
* Support for Parallel Scans
* Support for Subscans
* Recon Data visualization
* GPT Vulnerability Description, Impact and Remediation generation
* GPT Attack Surface Generator
* Multiple Roles and Permissions to cater a team's need
* Customizable Alerts/Notifications on Slack, Trans Asia Soft Tech, and Telegram
* Automatically report Vulnerabilities to HackerOne
* Recon Notes and Todos
* Clocked Scans (Run reconnaissance exactly at X Hours and Y minutes) and Periodic Scans (Runs reconnaissance every X minutes/- hours/days/week)
* Proxy Support
* Screenshot Gallery with Filters
* Powerful recon data filtering with autosuggestions
* Recon Data changes, find new/removed subdomains/endpoints
* Tag targets into the Organization
* Smart Duplicate endpoint removal based on page title and content length to cleanup the reconnaissance data
* Identify Interesting Subdomains
* Custom GF patterns and custom Nuclei Templates
* Edit tool-related configuration files (Nuclei, Subfinder, Naabu, amass)
* Add external tools from GitHub/Go
* Interoperable with other tools, Import/Export Subdomains/Endpoints
* Import Targets via IP and/or CIDRs
* Report Generation
* Toolbox: Comes bundled with most commonly used tools during penetration testing such as whois lookup, CMS detector, CVE lookup, etc.
* Identification of related domains and related TLDs for targets
* Find actionable insights such as Most Common Vulnerability, Most Common CVE ID, Most Vulnerable Target/Subdomain, etc.
* You can now use local LLMs for Attack surface identification and vulnerability description (NEW: HunterCat 2.1.0)
* BountyHub, a central hub to manage your hackerone targets

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## Quick Installation

### Quick Setup for Ubuntu/VPS

1. Clone the repository

    ```bash
    git clone https://github.com/dev52003/HunterCat && cd HunterCat
    ```

1. Configure the environment

    ```bash
    nano .env
    ```

    **Ensure you change the `POSTGRES_PASSWORD` for security.**

1. (Optional) For non-interactive install, set admin credentials in `.env`

    ```bash
    DJANGO_SUPERUSER_USERNAME=yourUsername
    DJANGO_SUPERUSER_EMAIL=YourMail@example.com
    DJANGO_SUPERUSER_PASSWORD=yourStrongPassword
    ```
    If you need to carry out a non-interactive installation, you can setup the login, email and password of the web interface admin directly from the .env file (instead of manually setting them from prompts during the installation process). This option can be interesting for automated installation (via ansible, vagrant, etc.).

    * `DJANGO_SUPERUSER_USERNAME`: web interface admin username (used to login to the web interface).

    * `DJANGO_SUPERUSER_EMAIL`: web interface admin email.

    * `DJANGO_SUPERUSER_PASSWORD`: web interface admin password (used to login to the web interface).

1. Adjust Celery worker scaling in `.env`

    ```bash
    MAX_CONCURRENCY=80
    MIN_CONCURRENCY=10
    ```

    `MAX_CONCURRENCY`: This parameter specifies the maximum number of HunterCat's concurrent Celery worker processes that can be spawned. In this case, it's set to 80, meaning that the application can utilize up to 80 concurrent worker processes to execute tasks concurrently. This is useful for handling a high volume of scans or when you want to scale up processing power during periods of high demand. If you have more CPU cores, you will need to increase this for maximised performance.

    `MIN_CONCURRENCY`: On the other hand, MIN_CONCURRENCY specifies the minimum number of concurrent worker processes that should be maintained, even during periods of lower demand. In this example, it's set to 10, which means that even when there are fewer tasks to process, at least 10 worker processes will be kept running. This helps ensure that the application can respond promptly to incoming tasks without the overhead of repeatedly starting and stopping worker processes.

    These settings allow for dynamic scaling of Celery workers, ensuring that the application efficiently manages its workload by adjusting the number of concurrent workers based on the workload's size and complexity.

    Here is the ideal value for `MIN_CONCURRENCY` and `MAX_CONCURRENCY` depending on the number of RAM your machine has:

    * 4GB: `MAX_CONCURRENCY=10`
    * 8GB: `MAX_CONCURRENCY=30`
    * 16GB: `MAX_CONCURRENCY=50`

    This is just an ideal value which developers have tested and tried out and works! But feel free to play around with the values.
    Maximum number of scans is determined by various factors, your network bandwidth, RAM, number of CPUs available. etc

1. Run the installation script:

    ```bash
    sudo ./install.sh
    ```

    For non-interactive install: `sudo ./install.sh -n`

    *Note: If needed, run `chmod +x install.sh` to grant execution permissions.*

**HunterCat can now be accessed from <https://127.0.0.1> or if you're on the VPS <https://your_vps_ip_address>**

**Unless you are on development branch, please do not access HunterCat via any ports**


## Updating

1. To update HunterCat, run:

    ```bash
    cd HunterCat &&  sudo ./update.sh
    ```

    If `update.sh` lacks execution permissions, use:

    ```bash
    sudo chmod +x update.sh
    ```

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## Community Support

HunterCat has a vibrant community that often creates helpful content about installation, features, and usage.
Always refer to the official documentation for the most up-to-date and accurate information. If you've created a video about HunterCat and would like it featured here, please send a pull request updating this table.

We appreciate the community's contributions in creating these resources.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


## Contributing

We welcome contributions of all sizes! The open-source community thrives on collaboration, and your input is invaluable. Whether you're fixing a typo, improving UI, or adding new features, every contribution matters.

How you can contribute:
  * Code improvements
  * Documentation updates
  * Bug reports and fixes
  * New feature suggestions and implementations
  * UI/UX enhancements

To get started:

  1. Check our [Contributing Guide](.github/CONTRIBUTING.md)
  2. Pick an [open issue](https://github.com/dev52003/HunterCat/issues) or propose a new one
  3. Fork the repository and create your branch
  4. Make your changes and submit a pull request

Remember, no contribution is too small. Your efforts help make HunterCat better for everyone!

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## Submitting issues

When submitting issues, provide as much valuable information as possible to help developers resolve the problem quickly. Follow these steps to gather detailed debug information:

1. Enable Debug Mode:
   - Edit `web/entrypoint.sh` in the project root
   - Add `export DEBUG=1` at the top of the file:
     ```bash
     #!/bin/bash

     export DEBUG=1

     python3 manage.py migrate
     python3 manage.py runserver 0.0.0.0:8000

     exec "$@"
     ```
   - Restart the web container: `docker-compose restart web`

2. View Debug Output:
   - Run `make logs` to see the full stack trace
   - Check the browser's developer console for XHR requests with 500 errors

3. Example Debug Output:
    ```
    web_1          |   File "/usr/local/lib/python3.10/dist-packages/celery/app/task.py", line 411, in __call__
    web_1          |     return self.run(*args, **kwargs)
    web_1          | TypeError: run_command() got an unexpected keyword argument 'echo'
    ```

4. Submit Your Issue:
    - Include the full stack trace in your GitHub issue
    - Describe the steps to reproduce the problem
    - Mention any relevant system information

5. Disable Debug Mode:
    - Set `DEBUG=0` in `web/entrypoint.sh`
    - Restart the web container

By providing this detailed information, you significantly help developers identify and fix issues more efficiently.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## First-time Open Source contributors

HunterCat is an open-source project that welcomes contributors of all experience levels, including beginners. If you've never contributed to open source before, we encourage you to start here!

* We're proud to support your first Pull Request (PR)
* Check our [open issues](https://github.com/dev52003/HunterCat/issues) for starter-friendly tasks
* Don't hesitate to ask questions in our community channels

Your contribution, no matter how small, is valuable to us.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## HunterCat Support

Before seeking support:

* Please carefully read the README and documentation .
* Most common questions and issues are addressed there.

If you still need assistance:

* Do not use GitHub issues for support requests.


Please note:
* The Trans Asia Soft Tech support is maintained by the community.
* While we strive to help, there's no guarantee of support or response time.
* For confirmed bugs or feature requests, consider opening a GitHub issue.


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


## Reporting Security Vulnerabilities

We appreciate your efforts to responsibly disclose your findings and will make every effort to acknowledge your contributions.

To report a security vulnerability, please follow these steps:

1. **Do Not** disclose the vulnerability publicly on GitHub issues or any other public forum.

2. Go to the [Security tab](https://github.com/dev52003/HunterCat/security) of the HunterCat repository.

3. Click on "Report a vulnerability" to open GitHub's private vulnerability reporting form.

4. Provide a detailed description of the vulnerability, including:
   - Steps to reproduce
   - Potential impact
   - Any suggested fixes or mitigations (if you have them)

5. I will review your report and respond as quickly as possible, usually within 48-72 hours.

6. Please allow some time to investigate and address the vulnerability before disclosing it to others.

We are committed to working with security researchers to verify and address any potential vulnerabilities reported to us. After fixing the issue, we will publicly acknowledge your responsible disclosure, unless you prefer to remain anonymous.

Thank you for helping to keep HunterCat and its users safe!

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


<p align="right"><i>Note: Parts of this README were written or refined using AI language models.</i></p>
