# Pong-ProcessingArduino
Pong in Processing with Arduino Two Potentiometer Controller

TwoPotB is a very simple Arduino sketch which reads analog on AO and A1 of the Arduino. Serial is 9600 baud rate. Serial output is formatted as 0-1023 for the two analogReads which are separated by a ',' (comma).

Pong in processing picks up the serial output and applies the 0-1023 value as the height for each paddle.
