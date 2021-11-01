###### @Setter - генерирует сеттеры для полей
###### @Getter - генерирует геттеры для полей

###### @AllArgsConstructor – конструктор, который будет юзать все поля класса по очереди
###### @RequiredArgsConstructor – конструктор, использующий все final поля класса
###### @NoArgsConstructor – конструктор без параметров

###### @ToString - определяет метод toString()
###### @EqualsAndHashCode - генерирует методы equals() и hashcode()

###### @Data - объединяет аннотации @Getter, @Setter, @ToString, @EqualsAndHashCode, и @RequiredArgsConstructor, а также @NoArgsConstructor(если нет @AllArgsConstructor) в одну
