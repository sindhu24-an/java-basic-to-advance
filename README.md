import java.util.TreeSet;

public class TreeSetExample {
    public static void main(String[] args) {

        TreeSet<String> animals = new TreeSet<>();

        // add elements
        animals.add("Lion");
        animals.add("Tiger");
        animals.add("Elephant");
        animals.add("Dog");

        System.out.println("Animals: " + animals);

        // first()
        System.out.println("First Animal: " + animals.first());

        // last()
        System.out.println("Last Animal: " + animals.last());

        // remove()
        animals.remove("Dog");
        System.out.println("After removing Dog: " + animals);

        // size()
        System.out.println("Size: " + animals.size());

        // contains()
        System.out.println("Contains Tiger? " + animals.contains("Tiger"));
    }
}
