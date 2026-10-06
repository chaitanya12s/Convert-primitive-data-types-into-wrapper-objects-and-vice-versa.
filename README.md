import java.util.ArrayList;

public class AutoboxingUnboxing {
    public static void main(String[] args) {


        ArrayList<Integer> numbers = new ArrayList<>();

        int a = 10;
        int b = 20;
        int c = 30;

        numbers.add(a);
        numbers.add(b);
        numbers.add(c);

        System.out.println("ArrayList: " + numbers);

        int x = numbers.get(0);
        int y = numbers.get(1);

        int sum = x + y;

        System.out.println("First number: " + x);
        System.out.println("Second number: " + y);
        System.out.println("Sum: " + sum);
    }
}
