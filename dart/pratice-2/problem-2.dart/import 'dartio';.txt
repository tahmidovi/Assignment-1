import 'dart:io';

void main() {
  stdout.write('Enter a alphabet: ');
  String al = stdin.readLineSync()!; 

  if(al=='a' || al=='e' || al=='i'|| al=='o'||al=='u'|| al=='A'|| al=='E' || al=='I' || al=='O' || al=='U'){
    print("Vowel");
  }
  else{
    print("Consonent"); 
  }
}