<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Google_Summer_of_Code_logo_%282021%29.svg/2560px-Google_Summer_of_Code_logo_%282021%29.svg.png" />
</p>

# GSoC 2024: Extending The Artemis Scanner

## Personal Information

- **Name**: Kshitij Kapoor
- **Email**: kshitijkapoor0611@gmail.com
- **GitHub**: [@kshitijk4poor](https://github.com/kshitijk4poor)

## Project Information

- **Organization**: Honeynet
- **Mentors**: [Krzysztof Zając](https://kazet.cc)
- **Project Size**: Large

## Summary

[Artemis](https://github.com/CERT-Polska/Artemis) is a state-of-the-art modular vulnerability scanner developed by CERT Polska. As the cornerstone of CERT PL's scanning activities, Artemis performs comprehensive security assessments across various websites, producing actionable reports that are directly communicated to organizations for remediation.

The primary objective of my project was to significantly enhance the functionality and user experience of Artemis. This was achieved by developing advanced modules for subdomain enumeration and IP/domain validation, coupled with a thorough modernization of the user interface. These improvements not only expand Artemis's scanning capabilities but also enhance its operational efficiency and user-friendliness.

## Contributions

### Pre-GSoC Contributions

Before the commencement of Google Summer of Code, I laid the groundwork for my involvement in the Artemis project by addressing several critical issues:

- [X] **Windows Troubleshooting**: Addressed compatibility issues that restricted Artemis's operation on Windows platforms. Developed and applied fixes, enabling seamless cross-platform functionality and expanding user accessibility (PR [#827](https://github.com/CERT-Polska/Artemis/pull/827)).
- [X] **Favicon Serving**: Noticed a lack of favicon support, which diminished the user interface quality. Implemented favicon serving, enhancing the visual appeal and professional look of Artemis's scan reports (PR [#864](https://github.com/CERT-Polska/Artemis/pull/864)).

### GSoC Contributions

#### Merged Code

During Google Summer of Code, I made several significant contributions that are now integral to Artemis and actively used in real scans at CERT Polska, enhancing the security of the Internet:

- [X] **Subdomain Enumeration Module**: Developed a robust subdomain enumeration module that substantially enhances Artemis's ability to uncover potential vulnerabilities related to undiscovered subdomains, thereby improving the comprehensiveness of the security assessments. This module is now a critical component in real-world scans, directly contributing to the identification and mitigation of security risks (PR [#1054](https://github.com/CERT-Polska/Artemis/pull/1054)).
- [X] **User Interface Revamp**: Recognized the outdated UI as a barrier to usability. Led a comprehensive redesign, resulting in a more intuitive and user-friendly interface that enhances the user experience. This improvement has been pivotal in facilitating more effective security assessments, making it easier for users to navigate and utilize the tool (PR [#1197](https://github.com/CERT-Polska/Artemis/pull/1197)).

#### Code Under Review

- [ ] **Domain Validation Function**: Noticed that Artemis lacked domain validation capabilities, so I developed a new function to validate IPs and domains more accurately, which is currently under review. This function aims to bolster the reliability and accuracy of Artemis's scan results (PR [#1146](https://github.com/CERT-Polska/Artemis/pull/1146)).

### Contributions Beyond the Proposal

In addition to my proposed contributions, I identified and addressed several other areas for improvement, demonstrating my proactive approach and commitment to the project:

- [X] **Startup Process Optimization**: Identified slow startup times as a pain point for users. Streamlined the startup process, reducing initialization times and improving operational efficiency, leading to a faster, more reliable user experience (PR [#1195](https://github.com/CERT-Polska/Artemis/pull/1195)).
- [X] **Routine Dependency Upgrades**: Identified that Artemis lacked up-to-date dependencies, which posed potential security and performance risks. To address this, I created a CI/CD pipeline that automates the regular upgrading of dependencies. This initiative ensures that Artemis consistently remains secure, robust, and aligned with the latest industry standards (PR [#1122](https://github.com/CERT-Polska/Artemis/pull/1122)).
- [X] **Non-x86 Compatibility Improvement**: Identified compatibility issues with non-x86 architectures, limiting Artemis's usability across different hardware. Improved compatibility, expanding Artemis's deployment across a wider range of platforms (PR [#1021](https://github.com/CERT-Polska/Artemis/pull/1021)).

## Future Work

I will address the domain validation function in our tests, update the Karton repository to enhance UI/UX coherence, and continue debugging Artemis for improved compatibility with non-x86 machines. My summer work on Artemis was incredibly fulfilling, and I remain committed to contributing to the project.

## Challenges and Learnings


## Acknowledgements

I express my sincere gratitude to Google, the Honeynet organization, and my mentor, Krzysztof Zając, for the invaluable opportunity to contribute to the Artemis project. Krzysztof helped me throughout the coding period and resolved any doubts that I had. He was very supportive and understanding until the end. His ability to provide clear and insightful feedback while fostering a collaborative and supportive environment greatly enhanced my learning experience. I look forward to the possibility of future collaborations and continued contributions to the project.
