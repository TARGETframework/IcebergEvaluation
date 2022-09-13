# IcebergEvaluation

# Content
1. [Detailed evaluation results](#detailed-evaluation-results)
2. [File description](#file-description)
3. [Columns of data set](#columns-of-data-set)

# Detailed evaluation results
- **LI.1 Willingness for continuous education and training:**
Sample feedback we received from the trainees was "The training was very interesting and gave me some interesting insights how this tool works and how attacks do look like in real life. Please more of this!", "The Cyber Range was great, motivated to go deeper into IT-Sec" and "A very cool interface with a lot of useful and probably realistic tools. I really liked the playful idea of teaching and having like a competition against the attacker. A great training that definitely grew my interest in those areas". None of the participants' feedback indicated that they found the training uninteresting or irrelevant. 21 out of the 50 students (42\%) participating in the user study actively signed up to our mailing list to get informed about future CRXs. These results indicate, that Iceberg CRX generally has the potential to raise students' interest in cybersecurity. However, the long-term impact needs to be measured by further studies.
- **LO.1 Offensive security knowledge:** Offensive security knowledge significantly increased by 42% from pretest (𝑀 = .61, 𝑆𝐷 = .25) to posttest (𝑀 = .87, 𝑆𝐷 = .20), 𝑡 (49) = −6, 38, 𝑝 < 0.001.
- **LO.3 Defensive security knowledge:** Defensive security knowledge significantly increased by 19% from pretest (𝑀 = .69, 𝑆𝐷 = .26) to posttest, (𝑀 = .82, 𝑆𝐷 = .20), 𝑡 (49) = −4.39, 𝑝 < 0.001.
- **LO.4 Defensive security skills:** With a significant increase 70% from pretest (𝑀 = .56, 𝑆𝐷 = .28) to posttest (𝑀 = .95, 𝑆𝐷 = .17), the highest impact of Iceberg CRX regarding a change in the participants’ skills and knowledge was observed for this criterion, 𝑡 (49) = −9.31, 𝑝 < 0.001. This specifically highlights Iceberg CRX’s potential to convey hands-on cybersecurity skills
- **LO.7 Non security-related knowledge:** Non security-related knowledge significantly increased by 29% from pretest
(𝑀 = .55, 𝑆𝐷 = .30) to posttest, (𝑀 = .71, 𝑆𝐷 = .24), 𝑡 (49) = −3.63, 𝑝 < 0.001

![image](https://user-images.githubusercontent.com/56884203/189810612-a0959270-87be-4ec2-9960-ab5a8492361d.png)
- **LE.2 Engagement of trainees:** With an overall mean of 4.09 (𝑆𝐷 = .84, 𝑀𝑑𝑛 = 4), the participants’ intrinsic motivation for the training can be considered high. The results for each category are listed below:

<center>

|                      | Mean | Median | Standard Deviation |
|----------------------|------|--------|--------------------|
|     Attention        | 4.64 |    5   |         0.6        |
|     Relevance        |   4  |    4   |        0.75        |
|     Confidence       | 3.99 |    4   |         0.8        |
|     Satisfaction     | 3.75 |    4   |        0.96        |
|     Metacognition    | 4.07 |    4   |        0.77        |

</center>

![image](https://user-images.githubusercontent.com/56884203/189811647-4b3d5731-eb93-4db0-b41c-4edf79817a27.png).

- **LE.3 Appropriate duration:** Participants took an average of 01:02:24 hours to finish the training (𝑆𝐷 = 00:15:03, 𝑀𝑑𝑛 = 01:01:56), which demonstrates that Iceberg CRX can be completed within the regular 90 minutes lecture of the weekly slot of a course at our university
- **LE.4: Appropriate difficulty:** On average, the participants scored 15.9 out of 24 points (𝑆𝐷 = 6.17, 𝑀𝑑𝑛 = 17) indicating that participants were in general able to solve a majority of the tasks. The participants’ mean rating of the statement if they found the tasks of the CRX overwhelming was 2.43 (𝑆𝐷 = .94) and a median of 2 ("disagree"). The relatively high standard deviation, however, suggests that some participants were overwhelmed by the difficulty of the training. This was also reflected in the feedback from the participants, who felt put off by the complexity of the SIEM dashboard at the beginning of the training. It can be concluded from this that the difficulty level of Iceberg CRX, in part, is too high for the target group.
- **T.2 Dynamic teaming role configuration:** As outlined before, Iceberg CRX was designed for trainees to participate individually from home. In order to strengthen the collaborative character of the CRX, it would also be possible for the trainees to participate in small teams solving the tasks together. However, this training modality has not yet been evaluated by the user study and therefore requires further evaluation.
- **S.5 Adaptability of difficulty:** For every task, trainees can "buy" a hint by lowering their score by one point. The hint reduces the difficulty of a task by providing the trainee with further information on how to proceed to solve the task. In this way, the trainees can decide to adjust the difficulty of a task if they have problems solving it. However, the fact that they lose points, as a result, creates an incentive not to use all hints across the board to make the CRX as easy as possible but only use hints when necessary.
- **S.6 Immediate feedback for trainees:** For each task, the trainees have three attempts to solve the task correctly. For each attempt, the LMS directly displays whether the trainee’s solution is correct or incorrect. If a trainee cannot solve the task in three attempts, the correct solution is displayed.
- **MG.6 Automation of attacks:** The MITM attack is executed automatically without a trainer’s intervention when the trainee reaches a certain level in the CRX and stops again after the trainee successfully eliminates the attacker from the network.
- **MO.2 Automated monitoring of trainees:** Participants’ scores are stored in a document-based database that provides a user interface for displaying and filtering the documents. This user interface can be used to monitor trainees’ progress during training, for example, to display how many trainees have already reached a certain level in training. This type of monitoring was sufficient for the training sessions in the user study with a maximum of 15 participants. However, to be able to monitor a larger number of trainees, a better automated monitoring system would be neces
- **E.4 Reliability:** During the dry run, the composition of the Docker container failed at two machines. This could be fixed, however, by simply restarting the infrastructure. Once the Docker containers were running on each machine, the Iceberg CRX instances were functioning correctly for the whole duration of the dry run. Hence, the reliability of the system was considered to be sufficient, which was confirmed in the user study, as none of the participants faced any technical difficulties related to the infrastructure. The only problem we faced was monitoring the trainees, as the time recording was incomplete for ten participants.
- **E.9 Fidelity of tools:** The SIEM tool Dsiem is part of the CRX by Vielberth et al. [ 61] which we utilized as a base for Iceberg CRX. To date, Dsiem is no more actively developed, and technical support is limited. For this reason, Dsiem is now highly unlikely to be used in practice, why the fidelity of the tool is limited.

# File description:
- [userData.csv](https://github.com/TARGETframework/IcebergEvaluation/blob/main/userData.csv): Anonymized raw data in csv format
- [userData.xlsx](https://github.com/TARGETframework/IcebergEvaluation/blob/main/userData.xlsx): Anonymized raw data in xlsx format

# Columns of data set:

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


