# switch-case-implentation-on-street-lamps-
This project is street lamp turn on off automatically where is it save much more energy and increase lamps effiency 

 #include <stdio.h>

int main() {
    int lightSensor; 
    // 0 = dark (night), 1 = bright (day)

    printf("Enter Light Sensor Value (0 = Dark, 1 = Bright): ");
    scanf("%d", &lightSensor);

    if (lightSensor == 0) {
        printf("It is Dark → Street Lamp is ON\n");
    } 
    else if (lightSensor == 1) {
        printf("It is Bright → Street Lamp is OFF\n");
    } 
    else {
        printf("Invalid Input! Please enter 0 or 1.\n");
    }

    return 0;
}
