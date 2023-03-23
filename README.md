# Authorization-service-REST
## Реализовано:

Сервис авторизации пользователей по логину и паролю.
Ключевое в этом задании то, как приложение будет реагировать на ошибки,
которые наш сервис будет выбрасывать в разных случаях.

Написаны обработчики ошибок, которые выкидывает сервис AuthorizationService.

Задачи обработчиков ошибок:

1. InvalidCredentials отсылает обратно клиенту HTTP-статус сообщения с кодом 400 и телом в виде исключения;
2. UnauthorizedUser отсылает обратно клиенту HTTP-статус сообщения с кодом 401 и телом в виде исключения написаное в консоли сообщения из исключения.