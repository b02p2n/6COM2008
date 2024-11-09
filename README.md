java c
Assignment Briefing Sheet (2024/25 Academic Year) 
Section A: Assignment title, important dates and weighting 
Assignment title: 6COM2008 Coursework 
Group or individual: Individual 
Module title: Internet of Things 
Module code: 6COM2008 
Section B: Student(s) to complete 
Notes for students 
•     For undergraduate modules, a score of 40% or above represents a pass performance at honours level. 
•     For postgraduate modules, a score of 50% or above represents a pass mark. 
•     Late submission of any item of coursework for each day or part thereof (or for hard copy 
submission only, working day or part thereof) for up to five days after the published deadline, 
coursework relating to modules at Levels 0, 4, 5, 6 submitted late (including deferred 
coursework, but with the exception of referred coursework), will have the numeric grade 
reduced by 10 grade points until or unless the numeric grade reaches or is 40. Where the 
numeric grade awarded for the assessment is less than 40, no lateness penalty will be applied. 
•     Late submission of referred coursework will automatically be awarded a grade of zero (0). 
•     Coursework (including deferred coursework) submitted later than five days (five working days in the case of hard copy submission) after the published deadline will be awarded a grade of zero (0). 
•     Regulations governing assessment offences including Plagiarism and Collusion are available 
fromhttps://www.herts.ac.uk/about-us/governance/university-policies-and-regulations-uprs/uprs (please refer to UPR AS14) 
•     Guidance on avoiding plagiarism can be found here: 
https://herts.instructure.com/courses/61421/pages/referencing-avoiding- plagiarism?module_item_id=779436 
• Modules may have several components of assessment and may require a pass in all elements. 
For further details, please consult the relevant Module Handbook (available on Studynet/Canvas, under Module Information) or ask the Module Leader. 
This Assignment assesses the following module Learning Outcomes (from Definitive Module Document): 
Successful students will typically:
Demonstrate knowledge and a critical understanding of the principles (standards, architectures and interoperability) of loT.
Demonstrate knowledge and understanding of the policies and regulations relating to the loT.
Demonstrate knowledge and understanding of data security, privacy and trust requirements of loT devices and networks and be aware of solutions.
Be able to design, configure and use loT networks, such as LoRaWAN.
Be able to design and programme for the Web of Things.
Be able to implement controls to secure an loT infrastructure.
Assignment Brief: 
Please see the attached file
Submission Requirements: 
Please submit the following components via StudyNet module website.
• Report. You are required to submit the report via StudyNet in a PDF format using your student number as the filename.
The final report structure is expected:
1. Report – Must have the code you used in the Appendix. Report must be in a word format.
2. ZIP folder
a. IoT Sensor Sender code
b. IoT Receiver code
c.Screenshots /MISC
Marks awarded for: 
Please see the attached file
Type of Feedback to be given for this assignment: 
Formative feedback will be given for the coursework during the scheduled sessions as per the module delivery plan. Individual personalised summative feedback will be given through StudyNet for the final submission. Feedback is not just the marks and the commentary at the end of the module – it is also the regular advice about your work as you undertake the practical activities. If you fail to undertake the practical activities and you fail to engage with the class and with the instructors, you will disadvantage yourself.
School of Physics, Engineering and Computer Science 6COM2008 - Internet of Things 
ASSIGNMENT BRIEFING SHEET (2024/25 Academic Year) ANONYMOUS MARKING – INDIVIDUAL ASSIGNMENT 
You have been hired to design, test, secure, and evaluate an IoT network for a new manufacturing plant aimed at designing and developing Integrated Circuits. The IoT network would ideally connect a clean room in the manufacturing plant to the head office. Due to the sensitivity of the experiments being conducted in the clean room, you have been t代 写6COM2008 Internet of Things 2024/25R
代做程序编程语言asked to create an IoT solution to protect the integrity of the experiment. The scenario can be explained in four tasks.  

Task 1 Network Design 
One Arduino MKR WAN 1310 will emulate the functionality of the “IoT sensor”, whilst the second will emulate the “IoT Receiver”. The network must adhere to the following requirements.
a.   “IoT sensor” must have the following capabilities.
i.   The device must be equipped with a DHT 22 module.
ii.   The device must be equipped with a MHR Sensor (TCRT5000).
iii.   The device must be equipped with an antenna that is capable of transmitting information.
iv.   The device must be compliant with LoRa WAN protocol.
b.   “IoT Receiver” must have the following capabilities.
i.   The device must be compliant with LoRa WAN protocol.
ii.   One L.E.D light (you may use the in-built L.E.D).
iii.   The device must be equipped with an antenna that can receive information.
Task 2 Configurations for the Sensor 
“IoT sensor” must have the following configurations programmed.
a.   A DHT 22 sensor that collects both temperature and humidity.
b.  TCRT5000 MHR Sensor that is capable of detecting an intruder.
c.   A programmable clock in 24hr format to maintain the time of the day.
i.   When an intrusion is registered by the TCRT5000, the sensor must conduct the following.
1.   Register that an intrusion had occurred.
2.   Print the time it occurred.
3.   Print the temperature and the humidity.
4.   Encrypt the message using the given Key.
5.   Send the aforementioned (Time, Temperature, and humidity) to IoT Receiver.    (Note: Serial Monitor of the sender should not print anything if an intrusion had not been registered)
Task 3 Configurations for the Receiver 
“IoT Receiver” must conduct the following to ensure that the communication is secure.
a.   A programmable clock to keep the time.
b.   Print the time every at every 1s interval and the message, “No Intrusion” .
c.   Ability to receive messages from the IoT Sensor.
i.   When a message is received, blink the L.E.D to alert the administrator.
d.   Use the given key to decrypt the messages sent by the IoT Sensor Sender. - You may use the XOR function to achieve decryption.
e.   Display the messages for the Administrator to view.
Task 4 Evaluation 
1.    Explain the advantages and the disadvantages that LoRa WAN protocol provides for the above
scenario. Provide introductory information of LoRa, LoRa WAN, Arduino MKR WAN 1310, DHT22, and MHR Sensor TCRT5000.
2.    Provide a detailed discussion outlining the use of the above technologies or a sub-set of them, in an industry or an academic research project. You must provide citations to support claims.
3.    “NB IoT and 5G can be used to replace LoRa WAN protocol” . Provide an argument for this. You may accept or reject the hypothesis by providing an evaluation of the three communication protocols/methods for IoT. You must provide citations to support claims.
4.   What improvements would you suggest for the above scenario to protect the clean room from intruders. Provide an evaluation between your suggested approach against the existing system.
Report Structure and Academic Conventions 
1.   Font size 12 with Normal margins under Layout. Harvard referencing style. must be used as per the
UH guidelines. (https://www.herts.ac.uk/__data/assets/pdf_file/0004/335173/Referencing- Guide.pdf).
2.   Submission type: MSWord (docx)
3.   Sample structure
Title Page 
Contents Page 
Abstract 
Introduction 
Experiments and Evidence for Establishing IoT in a Clean Room 
Analysis 
Conclusion 
References 
Appendix A: Sender Code 
Appendix B: Receiver Code 
Word count Excluding Title page, Contents page, References and Appendix: 3500 (+/- 10%)
Usage of AI-generated content for reports or code in this coursework is strictly prohibited. Any submission found to have employed such technologies will receive a mark of zero, and the matter will be referred to the academic misconduct board for further action. 
Submission Checklist 
1.   Report – Must have the code you used in the Appendix. Report must be in a word format. 
2. ZIPfolder 
a.   IoT Sensor Sender code 
b.   IoT Receiver code 
c.   Screenshots /MISC 





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
