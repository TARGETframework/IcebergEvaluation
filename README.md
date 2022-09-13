# IcebergEvaluation

## File description:
[userData.csv](https://github.com/TARGETframework/IcebergEvaluation/blob/main/userData.csv): Anonymized raw data in csv format
[userData.xlsx](https://github.com/TARGETframework/IcebergEvaluation/blob/main/userData.xlsx): Anonymized raw data in xlsx format

## Columns of data set:

| Column                 | Type    | Range       | Description                                                                                       |
|------------------------|---------|-------------|---------------------------------------------------------------------------------------------------|
| pre_all_avg            | float64 | [0;1]       | Average of all pretest questions                                                                  |
| pre_attack_1           | int64   | {0;1}       | What is a Man-In-The-Middle (MiTM) attack?                                                        |
| pre_attack_2           | int64   | {0;1}       | What effect does MitM attack possibly have on an industrial system?                               |
| pre_attack_3           | int64   | {0;1}       | How does ARP spoofing work?                                                                       |
| pre_attack_avg         | float64 | [0;1]       | Average from pre_attack_1, pre_attack_2 and pre_attack_3                                          |
| pre_def_1              | int64   | {0;1}       | What is the purpose of a SIEM system?                                                             |
| pre_def_2              | int64   | {0;1}       | What is a SIEM event?                                                                             |
| pre_def_3              | int64   | {0;1}       | What is the difference between a SIEM system and an Intrusion Detection   System (IDS)?           |
| pre_def_4              | int64   | {0;1}       | What is Incident Response mainly concerned with?                                                  |
| pre_def_5              | int64   | {0;1}       | What is the first step of Incident Response?                                                      |
| pre_def_6              | int64   | {0;1}       | What is an incident response playbook?                                                            |
| pre_def_avg            | float64 | [0;1]       | Average from pre_def_1, pre_def_2, pre_def_3, pre_def_4, pre_def_5 and,   pre_def_6               |
| pre_non_sec_1          | int64   | {0;1}       | What is the ARP protocol?                                                                         |
| pre_non_sec_2          | int64   | {0;1}       | What is a PLC (SPS)?                                                                              |
| pre_non_sec_3          | int64   | {0;1}       | What is an Industrial Control System (ICS)?                                                       |
| pre_non_sec_avg        | float64 | [0;1]       | Average from pre_non_sec_1, pre_non_sec_2 and pre_non_sec_3                                       |
| pre_skills_1           | int64   | {0;1}       | How can you identify the attacking host during an ARP-based MiTM attack?                          |
| pre_skills_2           | int64   | {0;1}       | How can you make an ARP cache static                                                              |
| pre_skills_3           | int64   | {0;1}       | How can you take down the interface of a network device?                                          |
| pre_skills_avg         | float64 | [0;1]       | Average from pre_skills_1, pre_skills_2 and pre_skills_3                                          |
| post_all_avg           | int64   | {0;1}       | Average of all posttest questions                                                                 |
| post_attack_1          | int64   | {0;1}       | What is a Man-In-The-Middle (MiTM) attack?                                                        |
| post_attack_2          | int64   | {0;1}       | What effect does MitM attack possibly have on an industrial system?                               |
| post_attack_3          | int64   | {0;1}       | How does ARP spoofing work?                                                                       |
| post_attack_avg        | float64 | [0;1]       | Average from post_attack_1, post_attack_2 and post_attack_3                                       |
| post_def_1             | int64   | {0;1}       | What is the purpose of a SIEM system?                                                             |
| post_def_2             | int64   | {0;1}       | What is a SIEM event?                                                                             |
| post_def_3             | int64   | {0;1}       | What is the difference between a SIEM system and an Intrusion Detection   System (IDS)?           |
| post_def_4             | int64   | {0;1}       | What is Incident Response mainly concerned with?                                                  |
| post_def_5             | int64   | {0;1}       | What is the first step of Incident Response?                                                      |
| post_def_6             | int64   | {0;1}       | What is an incident response playbook?                                                            |
| post_def_avg           | float64 | [0;1]       | Average from post_def_1, post_def_2, post_def_3, post_def_4, post_def_5   and, post_def_6         |
| post_non_sec_1         | int64   | {0;1}       | What is the ARP protocol?                                                                         |
| post_non_sec_2         | int64   | {0;1}       | What is a PLC (SPS)?                                                                              |
| post_non_sec_3         | int64   | {0;1}       | What is an Industrial Control System (ICS)?                                                       |
| post_non_sec_agv       | float64 | [0;1]       | Average from post_non_sec_1, post_non_sec_2 and post_non_sec_3                                    |
| post_skills_1          | int64   | {0;1}       | How can you identify the attacking host during an ARP-based MiTM attack?                          |
| post_skills_2          | int64   | {0;1}       | How can you make an ARP cache static                                                              |
| post_skills_3          | int64   | {0;1}       | How can you take down the interface of a network device?                                          |
| post_skills_avg        | float64 | [0;1]       | Average from post_skills_1, post_skills_2 and post_skills_3                                       |
| post_attention1        | int64   | {1;2;3;4;5} | The scenario and context of the training were interesting.                                        |
| post_attention2        | int64   | {1;2;3;4;5} | I wanted to successfully finish the training and complete all the tasks.                          |
| post_attention_avg     | float64 | [1;5]       | Average from post_attention1 and post_attention2                                                  |
| post_relevance1        | int64   | {1;2;3;4;5} | To me, the scenario and context seemed to be realistic.                                           |
| post_relevance2        | int64   | {1;2;3;4;5} | The tasks I performed represent skills that are required in real Incident   Repsonse work.        |
| post_relevance_avg     | float64 | [1;5]       | Average from post_relevance1 and post_relevance2                                                  |
| post_confidence1       | int64   | {1;2;3;4;5} | During the training, I felt I was in control over my actions.                                     |
| post_confidence2       | int64   | {1;2;3;4;5} | During the training, I had a sense that I made good progress.                                     |
| post_confidence_avg    | float64 | [1;5]       | Average from post_confidence1 and post_confidence2                                                |
| post_satisfaction1     | int64   | {1;2;3;4;5} | During the training, I experienced excitement.                                                    |
| post_satisfaction2     | int64   | {1;2;3;4;5} | I was satisfied with my performance during the training.                                          |
| post_satisfaction_avg  | float64 | [1;5]       | Average from post_satisfaction1 and post_satisfaction2                                            |
| post_metacognition1    | int64   | {1;2;3;4;5} | In my opinion, I have reached the learning objectives of the cyber range   training.              |
| post_metacognition2    | int64   | {1;2;3;4;5} | In my opinion, I have gained security skills and knowledge that might be   helpful in the future. |
| post_metacognition_avg | float64 | [1;5]       | Average from post_metacognition1 and post_metacognition2                                          |
| post_difficulty1       | int64   | {1;2;3;4;5} | I was overwhelmed by the complexity of the tasks                                                  |
| post_difficulty2       | int64   | {1;2;3;4;5} | During large parts of the the training, I felt stressed or frustrated.                            |
| post_difficulty_avg    | float64 | [1;5]       | Average from post_difficulty1 and post_difficulty2                                                |
| points                 | int64   | [-8;24]     | Points the participant scored during the training                                                 |
| duration               | int64   |             | Total time the participant took to finish the training                                            |
