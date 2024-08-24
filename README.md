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
- **Mentors**: [Krzysztof Zając](kazet.cc)
- **Project Size**: Large

## Summary
[Artemis](https://github.com/CERT-Polska/Artemis) is a modular vulnerability scanner by CERT PL. It's the tool that powers CERT PL's scanning activities by checking various aspects of website security and building easy-to-read messages ready to be sent to the scanned organizations.

The aim of the project was to enhance the Artemis scanner by developing new modules for subdomain enumeration and IP/domain validation, and modernizing the user interface. These improvements will boost Artemis's capabilities, efficiency, and user experience.

## Contributions
### Contributions before GSoC
  - [x] Windows Troubleshooting (PR [#827](https://github.com/CERT-Polska/Artemis/pull/827))
  - [x] Serving the favicon (PR [# 864](https://github.com/CERT-Polska/Artemis/pull/864))
### Proposed Contributions
#### Merged Code
  - [x] Subdomain Enumeration Module (PR [# 1054](https://github.com/CERT-Polska/Artemis/pull/1054))
  - [x] UI revamp (PR [#1197](https://github.com/CERT-Polska/Artemis/pull/1197))
#### Code under review
  - [ ] Domain Validation Function (PR [#1146](https://github.com/CERT-Polska/Artemis/pull/1146))

### Contributions beyond the proposal
  - [x] Better User Experience allowing no interference by the user to start artemis (PR [#1195](https://github.com/CERT-Polska/Artemis/pull/1195))
  - [x] Implemented routienly dependabot dependency upgradation(PR [#1122](https://github.com/CERT-Polska/Artemis/pull/1122))
  - [x] Troubleshooting non-x86 artemis compatibility (PR [#1021](https://github.com/CERT-Polska/Artemis/pull/1021))

## Future Work
fix the tests domain validation function, also to update the Karton repo to serve the UI/UX much more coherently, will continue to debug Artemis to make it much more compatible for non x86 machines. Working over `Artemis` over the summer was amazing, and I will keep contributing to the project.

## Acknowledgements
I want like to express my gratitude to Google, the honeynet organization and my mentor for giving me the opportunity to work on this project. Krzysztof helped me throughout the coding period, and solved any doubts that I had. he was very supportive and understanding till the end, I really appreciate him for the same and would love to work with him again.
