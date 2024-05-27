# friendly-octo-bassoon

import java.util.ArrayList;
import java.util.Arrays;

public class DifferenceArraysArrayLists {

    public static void main(String[] args) {
        // Arrays
        int[] intArray = {1, 2, 3, 4, 5};
        System.out.println("Array elements: " + Arrays.toString(intArray));

        // ArrayList
        ArrayList<Integer> intArrayList = new ArrayList<>();
        intArrayList.add(1);
        intArrayList.add(2);
        intArrayList.add(3);
        intArrayList.add(4);
        intArrayList.add(5);
        System.out.println("ArrayList elements: " + intArrayList);

        // Differences
        // 1. Arrays have a fixed size once declared, while ArrayLists can dynamically grow and shrink.
        // 2. Arrays can store primitive data types and objects, while ArrayLists can only store objects.
        // 3. Arrays use the [] syntax for element access, while ArrayLists use get() and set() methods.
        // 4. Arrays are more memory efficient compared to ArrayLists.
        // 5. Arrays can be initialized using the array literal syntax, while ArrayLists require instantiation.

        // Modify elements
        intArray[0] = 10;
        intArrayList.set(0, 10);

        // Display modified elements
        System.out.println("Array elements after modification: " + Arrays.toString(intArray));
        System.out.println("ArrayList elements after modification: " + intArrayList);
    }
}
