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
- [X] **User Interface Revamp](https://youtu.be/fuRQHZuUOsw)**: Recognized the outdated UI as a barrier to usability. Led a comprehensive redesign, resulting in a more intuitive and user-friendly interface that enhances the user experience. This improvement has been pivotal in facilitating more effective security assessments, making it easier for users to navigate and utilize the tool (PR [#1197](https://github.com/CERT-Polska/Artemis/pull/1197)).

[![Watch the video](https://img.youtube.com/vi/fuRQHZuUOsw/0.jpg)](https://youtu.be/fuRQHZuUOsw)
  
#### Code Under Review

- [ ] **Domain Validation Function**: Noticed that Artemis lacked domain validation capabilities, so I developed a new function to validate IPs and domains more accurately. This function checks the existence of queried domains on the web, ensuring that the scans are accurate and reliable, helping to prevent errors and improve the quality of the security assessments (PR [#1146](https://github.com/CERT-Polska/Artemis/pull/1146)).

### Contributions Beyond the Proposal

In addition to my proposed contributions, I identified and addressed several other areas for improvement, demonstrating my proactive approach and commitment to the project:

- [X] **Startup Process Optimization**: Identified slow startup times as a pain point for users. Streamlined the startup process, reducing initialization times and improving operational efficiency, leading to a faster, more reliable user experience (PR [#1195](https://github.com/CERT-Polska/Artemis/pull/1195)).
  
- [X] **Routine Dependency Upgrades**: Created a CI/CD pipeline that automates the regular upgrading of dependencies. This initiative ensures that Artemis consistently remains secure, robust, and aligned with the latest industry standards, protecting users from potential vulnerabilities (PR [#1122](https://github.com/CERT-Polska/Artemis/pull/1122)).
  
- [X] **Non-x86 Compatibility Improvement**: Improved compatibility with non-x86 architectures, expanding Artemis's usability across different hardware. This enhancement allows a wider range of users to benefit from the tool, making it more accessible (PR [#1021](https://github.com/CERT-Polska/Artemis/pull/1021)).

## Future Work

I will address the domain validation function in our tests, update the Karton repository to enhance UI/UX coherence, and continue debugging Artemis for improved compatibility with non-x86 machines. My summer work on Artemis was incredibly fulfilling, and I remain committed to contributing to the project.

## Challenges and Learnings

> **DISCLAIMER:** [notes to self, what worked for me might not work for you](https://slatestarcodex.com/2014/03/24/should-you-reverse-any-advice-you-hear/)

Throughout my journey with the Artemis project, I encountered various challenges that significantly contributed to my growth as a developer. One of the most valuable lessons I learned was the importance of iterative development and embracing imperfection in the initial stages of implementation.

A key insight that proved instrumental in my progress was:

> Don't be afraid to implement an imperfect solution; iterate over it until it works.

This approach taught me the value of starting with a basic implementation, even if flawed, and progressively refining it. By adopting this mindset, I was able to overcome analysis paralysis and make tangible progress on complex features. It allowed me to gather feedback earlier, identify issues more quickly, and ultimately arrive at more robust solutions.

My mentor, [Krzysztof Zając](https://kazet.cc), played a crucial role in this process. His guidance and support helped me navigate challenges and encouraged me to embrace iterative development. He provided constructive feedback that allowed me to refine my work effectively, reinforcing the importance of continuous improvement.

This iterative methodology not only accelerated my development process but also enhanced my problem-solving skills. It encouraged a more flexible and adaptive approach to coding, which proved especially beneficial when tackling the diverse challenges presented by the Artemis project.

Building upon this lesson, I discovered another crucial principle:

> There are high chances that what you're trying to do is already out there, if not completely, then at least partially. The Internet is your oyster.

This realization helped me overcome the common pitfall of reinventing the wheel. I learned to balance my desire for original implementation with the practicality of using existing solutions. This approach not only saved time but also exposed me to industry-standard practices and well-tested code.

By embracing this mindset, I was able to:

1. Accelerate development by building upon existing libraries and frameworks.
2. Focus more energy on the unique aspects of Artemis that truly required custom solutions.
3. Gain exposure to a wider range of coding practices and architectural designs.

It's important to note that while implementing things from scratch can be an excellent learning experience, during my time at GSoC, I often had to make strategic decisions to prioritize speed and efficiency. This trade-off between deep, ground-up learning and rapid, effective development was a valuable lesson in project management and pragmatic coding.

These principles of iterative development, writing clean code, and strategic use of existing solutions complement each other well. The former encourages experimentation and continuous improvement, while the latter prevents unnecessary reinvention and promotes efficiency. Together, they form a powerful approach to tackling complex software development challenges.

Moving forward, I plan to continue applying these principles, balancing the pursuit of perfection with the pragmatism of incremental improvement and leveraging existing resources. This experience has reinforced the idea that progress often emerges from imperfect beginnings, and that continuous iteration, combined with strategic use of existing solutions, is key to achieving high-quality, functional code.

## Acknowledgements

I express my sincere gratitude to Google, the Honeynet organization, and my mentor, Krzysztof Zając, for the invaluable opportunity to contribute to the Artemis project. Krzysztof helped me throughout the coding period and resolved any doubts that I had. He was very supportive and understanding until the end. His ability to provide clear and insightful feedback while fostering a collaborative and supportive environment greatly enhanced my learning experience. I look forward to the possibility of future collaborations and continued contributions to the project.