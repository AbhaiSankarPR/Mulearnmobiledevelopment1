import 'dart:io';

void main() {
  stdout.write("Enter a number: ");
  String? input = stdin.readLineSync();

  if (input == null || input.trim().isEmpty) {
    print("Invalid input. Please enter a number.");
    return;
  }

  int number = int.parse(input);
  int sum = 0;

  for (int i = 1; i <= 10; i++) {
    int product = number * i;
    print("$number × $i = $product");
    sum += product;
  }

  print("Sum of all values in the table: $sum");
}
