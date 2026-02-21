import 'dart:io';

void main() {
  stdout.write('Enter a number: ');
  int n = int.parse(stdin.readLineSync()!);

  if (n == 0)
    print("Zero");
  else if (n > 0)
    print("Positive");
  else
    print("Negative");
}