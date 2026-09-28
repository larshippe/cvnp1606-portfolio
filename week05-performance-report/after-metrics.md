Before:
<img width="962" height="1020" alt="week5step1-proof" src="https://github.com/user-attachments/assets/86db0089-e29c-4988-bafb-c1caceb3c3b6" />
<img width="957" height="1020" alt="week5step1a-proof" src="https://github.com/user-attachments/assets/341adb91-b235-4f85-9c9b-539e344bb9ec" />
<img width="962" height="1021" alt="week5step1b-proof" src="https://github.com/user-attachments/assets/aa1c94d4-d83a-49a7-b984-3e374bf4225a" />
CPU Usage was displayed at 100% for several minutes and showed no signs of decreasing. Suspected culprit was powershell processes that were taking up all of the CPU resources available.

Change:
<img width="961" height="1025" alt="week5step5-proof" src="https://github.com/user-attachments/assets/f5e726cc-ec0a-40a6-9cab-4a57f71387d9" />
Used the task manager to end the programs and CPU usage cleared up as showed above.

After:
<img width="962" height="1020" alt="week5step6-proof" src="https://github.com/user-attachments/assets/3a12be8b-6b1b-400d-a36c-71205d7a6ac3" />
<img width="955" height="1017" alt="week5step6a-proof" src="https://github.com/user-attachments/assets/8c2c9fb9-dde7-4993-a18a-d251d1785d7f" />
<img width="961" height="1022" alt="week5step6b-proof" src="https://github.com/user-attachments/assets/8ffb2ae2-5b96-4d61-86ff-2cc09c7f1679" />
CPU Usage has returned to normal and all other resources are reading normal as well. Removing these powershell processes immediately freed up the CPU and stopped it from running at full the whole time

Advice:
Do not run powershell programs that you don't know what they do. Or powershell programs your friends give you and say 'trust me bro'.
