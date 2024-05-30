# SNMP
SNMP service จะถูกใช้งานเพื่อแชร์สถานะ (Status) ของเครื่องให้กับเครื่องอื่นๆที่ต้องการจะเฝ้าระวังสถานะของเครื่องๆนั้น โดยปกติจะเป็นอุปกรณ์จำพวก network monitoring ต่างๆ ซึ่งจะพลาดในการตั้ง key ในการเข้าถึงเป็น default อย่าง private, public เป็นต้น นั่นทำให้ผู้โจมตีสามารถเข้าถึงข้อมูลของเครื่องได้

Lab : โจทย์นี้จะเป็นการหัดดึงข้อมูลจาก SNMP service 

149.28.159.195:161

How to:

sudo apt-get update

sudo apt-get install snmp

Command : SNMP

![image](https://github.com/thanawut2903/SNMP/assets/159118913/a4f1a606-699e-401a-bd04-a960f787bff3)

snmpwalk -v 2c -c public (target ip)

snmpwalk -v 2c -c public 149.28.159.195:161

![image](https://github.com/thanawut2903/SNMP/assets/159118913/9e39c292-b2e3-4d81-8ec1-d9d43e1a0548)

Ans : recon{rnYsicEYHM*SYrmq1StPAU4L38S}









