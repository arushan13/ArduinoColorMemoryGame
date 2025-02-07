#**Arduino Simon Says Game**  

This project is an **Arduino-based memory game** inspired by the boardgame *Simon*. The game challenges players to memorize and replicate a randomly generated LED pattern. The system is programmed in **C++** and uses buttons, LEDs, and a Piezo buzzer for interactive gameplay.  

## **Gameplay & Features**  

### **🔄 Random LED Sequences**  
- Four **multicolored LEDs** blink in a randomly generated pattern.  
- The player must **imitate the sequence** using buttons corresponding to each LED.  

### **📈 Progressive Difficulty**  
- With each correct sequence, **one more LED is added**, making the pattern longer.  
- The game continues until the player successfully reaches the final level.  

### **❌ Incorrect Input Detection**  
- If the player enters the wrong pattern, a **Piezo buzzer** plays a sound indicating failure.  
- The game resets, generating a **new random pattern** for the player to try again.  

### **🔌 Hardware Integration**  
- **LEDs and buttons** are mapped to the Arduino, ensuring responsive inputs.  
- The system uses **C++** for logic control and pattern generation.  

This project showcases **embedded systems and interactive programming**, combining memory challenges with fun gameplay! 🚀  

