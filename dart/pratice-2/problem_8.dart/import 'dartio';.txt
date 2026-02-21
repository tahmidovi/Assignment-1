import 'dart:io';

void main() {
  stdout.write('Enter first number: ');
  double n1 = double.parse(stdin.readLineSync()!);

  stdout.write('Enter second number: ');
  double n2 = double.parse(stdin.readLineSync()!);

  stdout.write('Enter operator: ');
  String o = stdin.readLineSync()!;

  if (o == '+')
    print("Result = ${n1 + n2}");
  else if (o == '-')
    print("Result = ${n1 - n2}");
  else if (o == '*')
    print("Result = ${n1 * n2}");
  else if (o == '/') {
    if (n1 > n2)
      print("Result = ${n1 / n2}");
    else
      print("Not Possible without points");
  } else
    print("Invalid");
}