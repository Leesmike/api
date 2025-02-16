# Тестирование API

Коллекции в postman с тестированием REST API приложения интернет-магазин [demoshopping.ru](https://demoshopping.ru/) и тестирование некоторых SOAP запросов сервиса [CountryInfoService](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL), используя парсер WSDL wizdler.

---

- [API коллекция в Postman](https://www.postman.com/espar/workspace/g9-mikhail-li/collection/20541504-221da1cb-c50a-40e8-9b17-bc563e13f3e8?action=share&creator=20541504&active-environment=20541504-3d77f342-3802-45e6-9b35-3cadfc21182f) | [JSON альтернатива](https://github.com/Leesmike/api/blob/main/DemoShopping.postman_collection.json) с тестированием методов GET, POST, PUT, PATCH, DELETE согласно документации [swagger demoshopping.ru](https://demoshopping.ru/api-docs/).
- [Результат выполнения автотестов](https://github.com/Leesmike/api/blob/main/G9_DemoShopping_postman_test_run.json), проверяющих время ответа, статус-код ответа, наличие нужных данных и их тип в ответе для некоторых методов в коллекции demoshopping.
- [Тест-кейсы для API тестирования](https://github.com/Leesmike/api/blob/main/G9%20Mikhail%20Li%20API%20test%20suite.pdf) методов GET, POST, PUT, PATCH, DELETE приложения интернет-магазин.
- [SOAP коллекция в Postman](https://www.postman.com/espar/workspace/g9-mikhail-li/collection/20541504-9432f65f-d22d-49e4-9eee-8fb39b7d70cf?action=share&creator=20541504) | [JSON альтернатива](https://github.com/Leesmike/api/blob/main/SOAP.postman_collection.json) для тестирования некоторых методов сервиса [CountryInfoService](http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL).
