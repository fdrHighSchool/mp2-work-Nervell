# Letter Grade
#### Respond to the following:

1. Write a plan for the following extension:
  * Attach a "+" on their grade if the grade ends in a 7, 8 or 9 (eg: 78 -> C+, 89 -> B+)
  * Attach a "-" on their grade if the grade ends in a 0, 1 or 2 (eg: 92 -> A-, 61 -> D-)

    * **YOUR WRITING HERE**
        if (7 > firstDigit  && firstDigit  >= 3) {
            sign = "";
        } else if (10 > firstDigit  && firstDigit  >= 7) {
            sign = "+";
        }

2. Discuss how you would make sure 100 is not misrepresented as an A-.
  * **YOUR WRITING HERE**
        if (num >= 90) {
            letter = "A";
            if (num >= 100) {
                sign = "+";
            }
        }

3. Discuss how you would make sure grades that are an F are not mislabeled as F- or F+ (eg: 49 -> F+ and 52 -> F-)
  * **YOUR WRITING HERE**
  
  } else if (num >= 60) {
            letter = "D";
        } else {
            letter = "F"; sign = "";
        }
