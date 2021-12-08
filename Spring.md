@Controller - программный модуль, который, допустим, по указанному пути слушает запросы от пользователя и возвращает какие-то данные(может возвращать какой-нибудь файл-шаблон html и т.д.)

@SpringBootApplication - аннотация, содержащая в себе три дополнительные:
  1. @SpringBootConfiguration
  2. @ComponentScan
  3. @EnableAutoConfiguration
