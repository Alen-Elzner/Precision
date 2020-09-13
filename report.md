## Краткое описание

12.09.2020 - 12.09.2020 было проведено санитарное тестирование приложения Precision.

### На тестирование затрачено: 5мин

### В результате тестирования выявлены следующие дефекты:

* [Производится не верный подсчет бонуса](https://github.com/Alen-Elzner/Precision/issues/1);

## Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты:

1. [Описание задания](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)

### В качестве тестовых данных использовались данные из [Описание задания](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):

```java
public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}
```

### Тестирование производилось в следующем окружении:

* Windows 8.1 професиональная build 9600
* openjdk version "11.0.8" 2020-07-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* IntelliJ IDEA Community 2020.2.1

