# spring-boot-quartz-scheduler [WIP]

Sample project demonstrating how to use quartz scheduler in spring boot for sending an email at a certain time in the future. Quartz library offers much broader possibilities for scheduling jobs in Java applications and can be used to execute different tasks at a pre-determined time or when the scheduled time arrives.

Start application and execute a POST request on http://localhost:8080/scheduleEmail with body:
{
    "email": "YOUR_EMAIL_ADDRESS",
    "subject": "Email subject",
    "body": "Email body",
    "dateTime": "DATE_TIME",
    "timeZone": "Europe/Chisinau"
}

Please use this format for DATE_TIME: yyyy-MM-ddThh:mm:ss ( for example 2022-02-23T23:00:00).
