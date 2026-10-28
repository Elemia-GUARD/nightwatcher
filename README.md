# Nightwatcher
The backend server that processes the commands and outputs of GUARD services/solutions in real-time to be rendered on a web application using the frontend techniques.

**This solution is tailored from the User Experience team to the audience.** They are mainly deploying user experience solutions including graphical user interface as what we see in web applications (HTML, CSS and JavaScript), in addition to mobile application solutions like Dart & Flutter technology.
All of that is for only one purpose: providing the manager/user the eligibility to control and monitor the appliances whatever it is.

They are consisting mainly of six modules:-

1- **Telemetry**: Collects the data (from the API) and load insights to the dashboard webpage.<br/>
2- **System Status Manager**: Showing the states of the services.<br/>
3- **Event and Alert Engine**: System failure detection<br/>
4- **Historical Data Engine**: Previous insights and metrics records to be seen again by the manager<br/>
5- **API & Interfaces Orchestrator**: Fetching the service to get and load the data coming from the service.<br/>
6- **Identity & Access Control**: Enforce Permissions and Privileges for a user, Responsible for the access control levels.

Well-known frontend technology like ReactJS, TypeScript and WebSockets are used to form the external seeing of a webpage.<br/>
It is consisting mainly of two webpages: Login and the Dashboard page itself.
