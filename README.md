# stepik-id-printer
Это проект для вывода моего персонального идентификатора на *образваотелньой платформе* `stepik.org`
## Возможности
Данный проект имеет следующий функциональ
- Выводит в **stdout** уникальный идентификаторю
- Без зависимостей
- Простой
## Запуск
`bash ./script.sh`
## Портирование 
Данный проект можно портировать на другие языки программированияю

На Java
```
class Main {
    public static void main(String[] args){
        System.out.println("777");
    }
}
```

На C++

```
#include <iostream>

using namespace tsd;

int main() {
  cout << 777 << endl;
  return 0;
}
```
> Попробуйте реализовать на Python, Go и JavaScript
