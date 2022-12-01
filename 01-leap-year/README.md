# Leap Year
#### Respond to the following:

1. Rewrite the following nested `if()` statements in a single line:
  ```
  if (year % 4 == 0) {
      if (year % 100 != 0) {
        // DO STUFF
      } // end inner if statement
   } // end outer if statement
  ```
  * **YOUR WRITING HERE**
(((year % 100 != 0) && (year % 4 == 0)) || (year % 400 == 0))

2. Label each as either correct or incorrect syntax. If incorrect, rewrite below:
  * if (x == y) {

    * **YOUR WRITING HERE**
correct
  * if [x == 10] {

    * **YOUR WRITING HERE**
incorrect
  * if x = 10 then {

    * **YOUR WRITING HERE**
incorrect
  * if (x equals 42) {

    * **YOUR WRITING HERE**
incorrect
  * if (x => y) {

    * **YOUR WRITING HERE**
correct

3. Fix the error in the code below:

  ```
  Scanner console = new Scanner(System.in);
  System.out.print("What is your favorite color? ");
  String name = console.next();
  if (name == "blue") {
      System.out.println("Mine, too!");
  }
  ```

String name = console.nextLine();
  if (name.equals("blue")) {
      System.out.println("Mine, too!");
  }
  ```
