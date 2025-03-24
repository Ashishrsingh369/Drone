# Drone
Navigation,Control and payload management
#include <iostream>
void setMotorSpeed(float pitch, int motor_id) {
    int speed = 1000 + (pitch * 10);  // Simplified adjustment
    std::cout << "Motor " << motor_id << " speed: " << speed << "\n";
}
int main() {
    setMotorSpeed(5.0, 1);
    return 0;
}
