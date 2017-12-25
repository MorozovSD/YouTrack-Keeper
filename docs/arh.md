## *Архитектура*

### YouTrackDAO  
Вся логика работы с RestAPI сервиса Youtrack сосредоточена в классе YouTrackDAO, основные методы:
```java
public void login(String baseUri, String login, String password)
```  
Производит авторизацию пользователя по заданным параметрам:  
_baseUri_ - URI требуемого Youtrack'а  
_login_ - Логин пользователя  
_password_ - Пароль пользователя  


```java
public Map<String, String> getIssue(String issueUri)
```  
Запрашивает все таски для конкретного пользователя.  
_issueUri_ - URI требуемых задач
### IssueActivity
### IssueListAdapter
### YouTrackActivity
### YouTrackPreference
### Cache
### RequestFailedException

[К содержанию](./index.md)
