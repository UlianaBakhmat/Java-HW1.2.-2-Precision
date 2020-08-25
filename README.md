# Отчет о тестировании приложения Precision

## Краткое описание:

25.08.2020 было создано и протестировано java-приложение Precision с кодом:

 public class Main {
 
    public static void main(String[] args) {
    
        double regularBonus = 0.3;
        
        double specialBonus = 0.6;
        
        double totalBonus = regularBonus + specialBonus;
        
        System.out.println(totalBonus);
    }
}

## Описание теста:

Было выполнено smoke-тестирование, запуск кода в среде IntelliJ IDEA, процесс завершился с кодом 0 без ошибок.

## Результат:

Приложение запустилось и вернуло в консоли "0.8999999999999999". Ожидалось значение "0.9".

Оформлен баг-репорт https://github.com/UlianaBakhmat/Java-HW1.2.-2-Precision/issues/1
