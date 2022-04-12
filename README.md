# Room Wizard Calendar for Home
## Technology, language, libraries, architecture:
This app is running as a system app.
1. Kotlin + Coroutines + Flows
2. Compose (State Handlers, Local Compose LifeCycle)
3. MVVM + Clean Architecture
4. HILT
5. Modules: stats, common
6. Foreground service, Bound Service, Content Providers, Retrofit + GSON/Mocha, Alarm Manager, WorkManager
7. More device settings possible because of the app type: system app
8. Unit Tests, Instrumentation Tests 

##### Front Home Screen - Now Event and Next Events. 14 is a day with other more events in calendar.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-events-front-page.png)
##### Events list from current day.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-events-events-page.png)
##### Events list from current 14th day.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-events-events-2-page.png)
##### An event from today wich will happen soon.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-events-front-page-soon.png)
##### No Events found.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-no-events-events-page.png)
##### No Events for Today.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-no-events-front-page.png)
##### Extra menu with any future options.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-no-events-front-page-left-menu-opened.png)
##### Google Calendar Intergration I.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-google-calendar-add-event.png)
##### Google Calendar Intergration II.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-google-calendar-list-event.png)
##### Sample of the source code
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/sample-of-code-architecture-2.png)
##### Real device with the app. Red color Light means that a current event is happening NOW. There is also GREEN when no event is happening now.
![alt text](https://roomwizard.hagau.ro/roomwizard-screens/roomwizard-realdevice-led-red-event-in-progress.jpg)
