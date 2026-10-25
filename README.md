# Real-Time Sign Language Recognition for Cashier to Customer Communication at Point-of-Sale

This project focuses on the communication challenges that are faced by Deaf Malaysian who use Malaysian Sign Language (BIM) when shopping and ordering. It explore how computer vision technology can help improve communication between deaf customers and the cashiers. This project is part of my CSC649 Assignment 1 as serves as the foundation for my Final Year Project (FYP)

## Problem statement

Malaysian Sign Language which are called Bahasa Isyarat Malaysia (BIM) is commonly used by Deaf individuals in Malaysia, but many hearing people including cashiers having a hard time to understand it. The problem is that there are only a few interpreters in Malaysia. According to Asia News Network (2025), there are only around 60 active interpreters for more than 44,000 deaf people. As a result, deaf customer may have no one to help them to ask for a price, choose how to pay or answer the cashier questions. It also reported that 66% of hearing-impaired respondents have found that the retail staff untrained in communicating with deaf customers (Gopan,2025).

Nowadays computer vision and deep learning are mostly used to recognize sign language in real time. Neural Network such as Long Short Term Memory (LSTM) are commonly used to track or process hand landmark data and to recognize sign language gesture (Kamble, 2025). It only required a webcam  while other commercial system are using sensor based and it is costly.However, vision based system are still facing challenges related to different signers, camera angles, lighting and backgrounds(Trabelsi et al., 2025).

## Documents
- [Problem statement](docs/problem-statement.md)
- [Requirements](docs/requirements.md)
- [User stories](docs/user-stories.md)

## Project structure
```
.
|-- README.md
|-- LICENSE
|-- .gitignore
|-- docs/
|   |-- problem-statement.md
|   |-- requirements.md
|   |-- user-stories.md
|   |-- sprint-log.md
|-- src/
    |-- README.md      (code will go here)
```

## Roadmap
- [x] Add acceptance criteria to each user story
- [x] Number the requirements and link each story to one
- [x] Add structure and roadmap to the README
- [ ] 
## Technology
Computer vision (with deep learning)

## Status
Sprint 1 completed (CSC649, Week 3)

## Author
Nurman Aiman, UiTM, CSC649

## References
- Asia News Network. (2025, October 3). Only 60 interpreters for 44,000 deaf Malaysians: why the community struggles. https://asianews.network/only-60-interpreters-for-44000-deaf-malaysians-why-the-community-struggles
- Chong, Y. T., Rao, Y. S. N., Khan, R. U., Teh, C. S., Barawi, M. H., Sunar, M. S., & Sim, J. J. J. (2026). A dynamic Malaysian sign language dataset for sign language recognition and translation. Data in Brief, 65, 112511. https://doi.org/10.1016/j.dib.2026.112511
- Gopan, G. (2025). Sensory inclusivity in retail environments: A design-oriented approach. https://doi.org/10.1177/10717641251327928
- Kamble, S. (2025). SLRNet: A real-time LSTM-based sign language recognition system. arXiv. https://arxiv.org/pdf/2506.11154
- Kumar, R., Bajpai, A., & Sinha, A. (2023). A comparative analysis of techniques and algorithms for recognising sign language. arXiv. https://arxiv.org/pdf/2305.13941
- Trabelsi, L., Harrouch, H., Mohamed, S., Jebali, M., & Sharma, A. (2025). Advancements and challenges in vision-based sign language recognition: A comprehensive review. https://www.sciencedirect.com/science/article/abs/pii/S1566253525006980
