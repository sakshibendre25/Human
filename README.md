class Person {
 private string name;
 private int age;
 public Person(string name, int age) {
      this.name=name;
        this.age=age;
  }
       public string getName() {
           return name;
  }
         public int age() {
             return age;
  }
  }
          public class Main {
          public static void main (string[] ) {
              Person p1 = new Person("Karan",20);
               Person p2 = new Person("Anish" ,24);
       System.out.println(person1.getName() + "is" + person1.getAge() + "years old.");
       System.out.println(person2.getName() + "is" + person2.getAge() + "years old.");
    }
    }
