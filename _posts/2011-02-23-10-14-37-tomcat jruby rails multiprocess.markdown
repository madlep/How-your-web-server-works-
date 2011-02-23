# Tomcat / JRuby / Rails #
- Can single thread - sort of like Apache/Passenger. Set JRuby instance count to max concurrent requests
- OR you can configure it with 1 instance, and multithread Rails
- **Newbie error** : default is 1 JRuby instance, Rails multithread *off* - single threaded execution == *Slow*
