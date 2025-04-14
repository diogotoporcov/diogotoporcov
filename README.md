```java
import world.Brazil.Cities.SaoPaulo.Person;
import education.Status.Status;
import java.util.List;

public class Main {
  public static void main(String[] args) {
    Person diogo = new Person.Builder()
        .setName("Diogo Toporcov")
        .setEmail("diogotoporcov@gmail.com")
        .setAge(21)
        .setLanguages(List.of("Java", "Python"))
        .setEducation(
            Status.STUDYING,
            "Systems Analysis and Development",
            "Instituto Federal de Educação, Ciência e Tecnologia de São Paulo")
        .build();

    diogo.helloWorld();
  }
}

```

```bash
C:\diogotoporcov> java Main
Hello, World! I am still setting up my github page.
```

