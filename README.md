📌 What is an Operator?
operator is a symbol used to perform specific operations.

🧮 Types of Operators in Java with Symbols
     1. Arithmetic Operators → +, -, *, /, %

     2. Assignment Operators → =, +=, -=, *=, /=, %=, &=, |=, ^=, >>=, <<=

     3. Unary Operators → +, -, ++, --, !

     4. Relational Operators (Comparison) → ==, !=, >, <, >=, <=

     5. Logical Operators → &&, ||, !

     6. Ternary Operator → ? :

     7. Bitwise Operators → &, |, ^, ~, <<, >>, >>>


🔹Arithmetic operator-It is used to perform arithemetic operations like 
             +(Addition)
             -(Subtraction)
             *(Multiplication)
             /(Division)
             %(Modulus)
🧪 Example:
public class OperatorPractice {
    public static void main(String[] args) {
        int i = 10, j = 20;
        int add = i + j;
        System.out.println("Addition of i and j: " + add);
        int sub = i - j;
        System.out.println("Subtraction of i and j: " + sub);
        int mul = i * j;
        System.out.println("Multiplication of i and j: " + mul);
        int div = i / j;
        System.out.println("Division of i and j: " + div);
        int mod = i % j;
        System.out.println("Modulus of i and j: " + mod);
        
    }
}

🔹Assignment operators:It is used to assign values to the variables.
=,+=,-=,*=,/=,%=.

🧪 Example:
public class AssignmentOperators {
    public static void main(String[] args) {
        int a = 10;
        a += 5;  // a = a + 5
        System.out.println("a += 5: " + a);

        a -= 2;  // a = a - 2
        System.out.println("a -= 2: " + a);

        a *= 3;  // a = a * 3
        System.out.println("a *= 3: " + a);

        a /= 2;  // a = a / 2
        System.out.println("a /= 2: " + a);

        a %= 4;  // a = a % 4
        System.out.println("a %= 4: " + a);
    }
}

🔹 3. Unary Operators
Used with a single operand.

Operators: +, -, ++, --, !

🧪 Example:
public class UnaryOperators {
    public static void main(String[] args) {
        int x = 5;
        System.out.println("x: " + x);
        System.out.println("++x: " + (++x)); // Pre-increment
        System.out.println("x++: " + (x++)); // Post-increment
        System.out.println("x: " + x);
        System.out.println("--x: " + (--x)); // Pre-decrement
        System.out.println("x--: " + (x--)); // Post-decrement
        System.out.println("x: " + x);

        boolean flag = true;
        System.out.println("!flag: " + (!flag)); // Logical NOT
    }
}

🔹 4. Relational (Comparison) Operators
Compare two values and return a boolean result.

Operators: ==, !=, >, <, >=, <=

🧪 Example:
public class RelationalOperators {
    public static void main(String[] args) {
        int a = 10, b = 20;

        System.out.println("a == b: " + (a == b));
        System.out.println("a != b: " + (a != b));
        System.out.println("a > b: " + (a > b));
        System.out.println("a < b: " + (a < b));
        System.out.println("a >= b: " + (a >= b));
        System.out.println("a <= b: " + (a <= b));
    }
}

🔹 5. Logical Operators
Used to combine multiple boolean conditions.

Operators: && (AND), || (OR), ! (NOT)

🧪 Example:
public class LogicalOperators {
    public static void main(String[] args) {
        int a = 10, b = 20;

        System.out.println("a < b && b > 15: " + (a < b && b > 15)); // true
        System.out.println("a < b || b < 10: " + (a < b || b < 10)); // true
        System.out.println("!(a == b): " + !(a == b)); // true
    }
}

🔹 6. Ternary Operator
Shorthand for if-else condition.

Operator: condition ? trueValue : falseValue

🧪 Example:
public class TernaryOperator {
    public static void main(String[] args) {
        int age = 18;
        String result = (age >= 18) ? "Eligible" : "Not Eligible";
        System.out.println("Result: " + result);
    }
}

🔹 7. Bitwise Operators
Perform operations at the bit level.

Operators: &, |, ^, ~, <<, >>

🧪 Example:
public class BitwiseOperators {
    public static void main(String[] args) {
        int a = 5, b = 3;

        System.out.println("a & b = " + (a & b));
        System.out.println("a | b = " + (a | b));
        System.out.println("a ^ b = " + (a ^ b));
        System.out.println("~a = " + (~a));
        System.out.println("a << 1 = " + (a << 1));
        System.out.println("a >> 1 = " + (a >> 1));
    }
}


