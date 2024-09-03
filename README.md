# Dependency-injection-simple-Examples
## Task1:NotificationService
Create a simple notification system that can send messages via different channels (e.g., Email and SMS). Use dependency injection to allow the notification system to work with any channel without hardcoding the channel type.

### Requirements:
1.Define an interface INotificationChannel with a method sendMessage(const std::string& message).

2.Implement two classes: EmailChannel and SMSChannel that inherit from INotificationChannel.

3.Create a NotificationService class that takes an INotificationChannel object through its constructor.

4.The NotificationService should have a method notify(const std::string& message) that uses the injected channel to send the message.

5.In the main function, demonstrate the use of NotificationService with both EmailChannel and SMSChannel.

