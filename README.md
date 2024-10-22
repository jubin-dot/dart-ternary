void main() {
   // program using conditional operations
  int age = 20;
  String status = age >= 18 ? 'Adult' : 'Minor';

  print(status);

   // program using cascade notation index operator
    Map<String, String> scores = {
    'Alice': '85',
    'Bob': '92',
    'Charlie': '78',
  };

  // Using cascade notation with the index operator to modify map values
  scores
    ..['Alice'] = '90'
    ..['Bob'] = '95'
    ..['Charlie'] = '80';

  print(scores);
 }
 
