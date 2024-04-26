# Workshop 3 - Solution

In this workshop, we continue the vehicle company software by adding a user system and an easier interface for use.

## Requirements

The requirements for this workshop are presented as follows:
- Strive to reduce the memory usage
- Add a loggin system to authenticate users
- Add the Users with thier corresponding abilities and information
- Add Admin level for regulation and control of the plataform
- Keep a log of all user related actions
- Segregate the app in different subsystems
- Add a simpler and better interface for the users
- Add a performance monitoring system for the app and keep all that information in a log named: _performance__log_
- Keep the last 5 serched vehicles in cache to increase performance
- Verify if Encapsulation can be added to greatter improve security

## Business Rules

- Every vehicle just have chassis of type A or B.
- Gas consumption is based on engine information...
- Gas consumption is based on next equation.
  `1.1 ∗ engine.potency + 0.2 ∗ engine.weight - (0.3 if A or 0.5 if B)`
- User system with a logging capability and additional Admin controls
- Interface sor easy use and conexion with the app components
