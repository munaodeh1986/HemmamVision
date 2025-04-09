
---

## **Hemma Vision - Smart Solution for Empowering People with Disabilities in Sports Arenas**

### **Project Overview**
Hemma Vision is a groundbreaking project designed to enhance the sports experience for individuals with disabilities. By leveraging cutting-edge technology, this system creates an inclusive and accessible environment for fans with mobility impairments and autism, enabling them to enjoy sporting events with comfort and ease. The project integrates Arduino-based solutions for line-following navigation and sensory stimulation, aiming to provide a seamless and dignified experience for every spectator.

### **Key Features**
- **Smart Wheelchair Navigation:** The system uses a line-following mechanism powered by Arduino, which guides wheelchairs autonomously to designated seats in the stadium. The wheelchair is equipped with infrared sensors and motors that ensure smooth and accurate navigation based on line detection.
  
- **Sensory Rooms for Autism Spectrum Disorder (ASD) Spectators:** Specialized rooms are equipped with interactive sensory tools, such as touch sensors that trigger soothing music, calming sounds, and dynamic RGB lighting. These sensory rooms are designed to improve the game experience for fans with autism and sensory sensitivities.

- **Integrated Feedback Mechanisms:** The sensory rooms provide a multi-sensory experience, helping individuals feel comfortable and engaged. For instance, users can trigger specific reactions like music or lighting changes by interacting with sensors, allowing them to tailor their experience.

- **Inclusive Environment:** The entire setup aims to create a socially inclusive environment where individuals with disabilities can enjoy the excitement of sports events without facing the challenges of accessibility or sensory overload.

### **Technologies Used**
- **Arduino Uno:** The main controller of the entire system, handling sensor inputs, motor control, and communication.
- **IR Line Tracking Sensors:** These sensors detect the lines drawn on the floor, guiding the wheelchair automatically to the designated seating area.
- **Motor Driver (L298N):** Controls the movement of the wheelchair’s motors, enabling it to move forward, backward, and turn.
- **Touch Sensors:** Located in sensory rooms, they interact with users to trigger different reactions like music, vibrations, and lighting changes.
- **RGB Lighting:** Used in sensory rooms to create calming and immersive experiences by changing colors based on user interaction.

### **How It Works**
1. **Line-Following System for Wheelchairs:** The wheelchair is equipped with two IR sensors. When the sensors detect the line, the wheelchair follows it autonomously to guide the user to their seat. The system adjusts the wheelchair's direction based on sensor readings, turning left or right if necessary.
  
2. **Sensory Room Interaction:** In sensory rooms, users can activate different sensory experiences by interacting with touch sensors. When a sensor is touched, the room responds by playing cheerful music, relaxing sounds, or changing the lighting to create a soothing environment for individuals with autism.

3. **User-Friendly and Inclusive Design:** The system automatically detects the user’s identity via fingerprint recognition (optional) and uses motors to adjust the wheelchair’s path, ensuring easy and fast navigation to the seat. Additionally, it’s designed to prevent individuals from feeling overwhelmed during the game, offering them a balanced and comfortable experience.

### **Components Used**
- **Arduino Uno or compatible board**
- **IR Line Tracking Sensors**
- **2x DC Motors**
- **L298N Motor Driver**
- **RGB LED Strips**
- **Touch Sensors**
- **Fingerprint Scanner (optional for security/authentication)**

### **Applications**
- **Sports Arenas:** Hemma Vision transforms traditional sports arenas into accessible, inclusive spaces for fans with disabilities, ensuring everyone can experience the thrill of the game.
- **Public Events:** This system can also be adapted for other public venues such as shopping malls, museums, and theaters, where accessibility and sensory needs are essential.

### **Future Improvements**
- **Enhanced Accessibility Features:** Future iterations could include features like real-time voice guidance, multi-language support, and advanced user profiles for a more personalized experience.
- **Obstacle Detection and Avoidance:** Adding ultrasonic sensors to the wheelchair system to prevent collisions and enhance navigation accuracy.
- **Mobile App Integration:** Developing a mobile app for remote monitoring and control of the wheelchair, as well as allowing users to customize their sensory room experience.

### **Installation**
To use this system:
1. Upload the provided Arduino code to the Arduino board.
2. Connect the sensors, motors, and components according to the provided wiring diagram.
3. Power up the system and activate the line-following feature for wheelchair navigation.

### **Contributing**
We welcome contributions from the community! If you have ideas, improvements, or bug fixes, feel free to fork this repository and submit pull requests. Your feedback and collaboration are much appreciated.

---

