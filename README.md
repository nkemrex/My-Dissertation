# Dissertation
Certainly! Here is a complete README file based on the provided information:
Artificial Intelligence-Driven Honeypot-Enabled Active Defense Mechanisms for Healthcare Internet of Things Devices against Ransomware from Advanced Persistent Threats
Introduction & Background

This research investigates the development of AI-driven honeypot-enabled active defense mechanisms for healthcare IoT devices against ransomware from advanced persistent threats. The main objective is to develop an AI-driven honeypot-enabled active defense mechanism for healthcare IoT devices to detect, prevent, and respond to ransomware attacks from advanced persistent threats. By addressing the security vulnerabilities of healthcare IoT devices, this project aims to protect patient data, ensure uninterrupted healthcare services, and mitigate the financial and reputational risks faced by healthcare organizations.
IoT Devices in Healthcare

Honeypots are proposed as an active defense mechanism to gather information about attackers. This research explores the use of machine learning-based honeypots, federated learning, and IoT testbeds to improve cybersecurity in IoT networks. Specifically, the focus is on IoT devices in healthcare, known as HIoT, which are used to monitor patients' health and collect data for analysis.
Research Methodology

The research methodology involved the following steps:

    Data preprocessing: The IoT Healthcare Security Dataset and ransomware dataset were analyzed through preprocessing techniques to ensure data quality and consistency.
    Exploratory data analysis (EDA): EDA techniques were applied to gain insights into the datasets, identify patterns, and understand the characteristics of the data.
    Feature selection and engineering: Relevant features were selected, and new features were engineered to enhance the effectiveness of the proposed defense mechanism.
    Architecture design: The proposed architecture incorporated honeypots, anti-ransomware mechanisms, AI algorithms, and interaction with existing security systems.
    Test environment: A suitable test environment was set up to simulate attacks on ECG devices. Network traffic data captured from the honeypots was used for analysis.

System Design & Data Analysis

A system was designed to study ECG attacks, utilizing Mirth Connect as the underlying middleware. Statistical analysis of attack incidents was performed using Hawkes, which simulated temporal intervals between events and enhanced the depiction of attack patterns using the K bot notation. Additionally, a probability model was constructed to predict new sessions based on historical data. The IoT healthcare security dataset was analyzed to identify relationships between features, detect anomalies, outliers, and characterize legitimate and malicious traffic in healthcare IoT devices.
Results and Findings

The study on proactive defensive strategies for healthcare IoT devices against ransomware attacks yielded the following key results and findings:

    Attacks primarily targeted port 5000, with additional focus on ports like 22, 23, 8088, and 1433.
    ECG devices were particularly vulnerable to attacks.
    Cloud IP addresses were persistently targeted by malicious actors.
    Long-standing vulnerabilities like CVE-2001-0540 were still exploited.
    The DoublePulsar Backdoor was observed in use by attackers.
    Different attack patterns were identified between automated programs and human attackers.
    Effective processing of attack logs, combined with the use of honeypots and AI, can significantly enhance preventive security measures for healthcare IoT devices.

Installation

To install and set up the project, follow these steps:

    Clone the project repository from [GitHub link].
    Install the required dependencies, including [list of dependencies] using package manager [e.g., pip].
    Configure Git and clone the TPOT honeypot repository.
    Modify the honeypot's configuration to suit your environment.
    Capture network traffic data for analysis using the configured honeypot.
    Set up the necessary tools for simulating an ECG device, such as socat for creating a virtual serial port and ecgsyn for generating fake ECG data.

Usage

To use the project, follow these guidelines:

    Ensure the project dependencies are installed and the environment is properly set up.
    Run the main program [filename.py] to initiate the AI-driven honeypot-enabled active defense mechanism.
    Monitor the system for any detected ransomware attacks on healthcare IoT devices.
    Analyze the captured network traffic data and logs to gain insights into the attacks and identify patterns.
    Take appropriate actions based on the analysis to prevent, detect, and respond to ransomware attacks effectively.

Contributing

Contributions to the project are welcome. If you wish to contribute, please follow these guidelines:

    Fork the project repository.
    Create a new branch for your contributions.
    Make your changes and ensure they adhere to the project's coding style and guidelines.
    Test your changes thoroughly.
    Submit a pull request, clearly describing the changes made and their purpose.

Credits

We would like to acknowledge the following resources, libraries, and tutorials that contributed to this project:

    [https://github.com/telekom-security/tpotce]
    [Azure Honeypot]
    [https://www.youtube.com/watch?v=ub4kpXofLK4]

License

This project is not yet licensed . Please see the LICENSE file for more details.
Contact Information

For any questions, issues, or feedback related to this project, please contact REX at nkemrex@yahoo.com.

Feel free to modify or expand upon these sections based on your project's specific needs and requirements
