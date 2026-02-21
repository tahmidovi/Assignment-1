import 'dart:io';

void main() {
  int distance = 25;
  int travelSpeed = 40;

  double formula = distance / travelSpeed;

  print(formula);

  print("Reaching in Minutes: ${formula * 60} ");
}