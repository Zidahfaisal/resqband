# resqband
In emergency situations, victims often cannot make phone calls quickly.  
RESQBAND provides a one-click alert system that instantly shares live location to trusted contacts.
RESQBAND is an IoT-based emergency safety wristband built using ESP8266 and GPS technology. 

When the emergency button is pressed:
1. An alert message is sent instantly via Telegram.
2. Live GPS location is shared as a Google Maps link.
3. A buzzer alert is activated locally.

The system is designed for personal safety, especially for women, students, elderly individuals, and lone workers.
IoT based emergency alrt system using ESP8266 and GPS
| S.No | Component                                     | Qty   | Description / Notes                    |
| ---- | --------------------------------------------- | ----- | -------------------------------------- |
| 1    | **esp8266**                                   | 1     | Main controller                        |
| 3    | **Push Button (Tactile)**                     | 1     | Panic trigger                          |
| 4    | **10kΩ Resistor**                             | 1     | Pull-down for button                   |
| 5    | **green LED (Optional)**                      | 1     | Feedback indicator                     |
| 6    | **220Ω Resistor**                             | 1     | LED protection                         |
| 7    | **Buzzer (Optional)**                         | 1     | Audible alarm                          |
| 8    | **3.7V Li-ion / Li-Po Battery**               | 1     | Power supply                           |
| 9    | **TP4056 Charging Module**                    | 1     | Safe battery charging                  |
| 10   | **Breadboard (Recommended)**                  | 1     | For prototyping                        |
| 11   | **Jumper wires / Short insulated wires**      | ~10   | Connect components                     |

https://drive.google.com/drive/folders/1iKNtSDqQ318aWPdKQc-tvOG5qLhpsz5O

 How It Works

1. Device powers ON.
2. ESP connects to WiFi.
3. GPS searches for satellite lock.
4. When button is pressed:
   - Telegram sends: "🚨 Emergency Alert!"
   - GPS coordinates are fetched.
   - Google Maps link is generated.
   - Live location is sent.
   - Buzzer activates.

team members : Zidah Faisal PK
               Fidha Fathima TJ
This project is licensed under the MIT License.  
Open-source for educational and research purposes.               

