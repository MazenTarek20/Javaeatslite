# Javaeatslite
Javeats Lite is a modular food delivery management system built with Spring Boot. It streamlines the entire food delivery process, offering robust backend support for user management, order processing, restaurant management, menu management, and more. Designed for scalability and maintainability.



# Project Structure
Javeats_Lite/
├── docs/
│   ├── ERD.pdf                         # Entity-Relationship Diagram
│   └── README.md                       # Project description and setup instructions
├── scripts/
│   ├── seed_data.sql                   # SQL script to seed initial data
│   └── utility_functions.sql           # SQL script with utility functions
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── javeats/
│   │   │   │   │   ├── JaveatsLiteApplication.java   # Main application entry point
│   │   │   │   │   ├── config/
│   │   │   │   │   ├── entity/
│   │   │   │   │   │   ├── User.java                 # User entity class
│   │   │   │   │   │   ├── UserStatus.java           # UserStatus entity class
│   │   │   │   │   │   ├── UserType.java             # UserType entity class
│   │   │   │   │   │   ├── Role.java                 # Role entity class
│   │   │   │   │   │   ├── ...                       # Other entity classes
│   │   │   │   │   ├── repository/
│   │   │   │   │   │   ├── UserRepository.java       # User repository interface
│   │   │   │   │   │   ├── RoleRepository.java       # Role repository interface
│   │   │   │   │   │   ├── ...                       # Other repository interfaces
│   │   │   │   │   ├── service/
│   │   │   │   │   │   ├── UserService.java          # User service class
│   │   │   │   │   │   ├── RoleService.java          # Role service class
│   │   │   │   │   │   ├── ...                       # Other service classes
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   ├── UserController.java       # User controller class
│   │   │   │   │   │   ├── RoleController.java       # Role controller class
│   │   │   │   │   │   ├── ...                       # Other controller classes
│   │   │   │   │   ├── dto/
│   │   │   │   │   │   ├── UserDTO.java              # User Data Transfer Object
│   │   │   │   │   │   ├── RoleDTO.java              # Role Data Transfer Object
│   │   │   │   │   │   ├── ...                       # Other DTO classes
│   │   │   │   │   └── util/
│   │   │   └── resources/
│   │   │       ├── application.properties            # Application properties file
│   │   │       └── db-scripts/
│   │   │           ├── V1__create_user_status.sql    # SQL script to create UserStatus table
│   │   │           ├── V2__create_user_type.sql      # SQL script to create UserType table
│   │   │           ├── V3__create_role.sql           # SQL script to create Role table
│   │   │           ├── ...                           # Other SQL scripts
│   └── test/
│       ├── java/
│       │   ├── com/
│       │   │   ├── javeats/
│       │   │   │   ├── entity/
│       │   │   │   │   ├── UserTest.java             # User entity unit tests
│       │   │   │   │   ├── ...                       # Other entity test classes
│       │   │   │   ├── repository/
│       │   │   │   │   ├── UserRepositoryTest.java   # User repository unit tests
│       │   │   │   │   ├── ...                       # Other repository test classes
│       │   │   │   ├── service/
│       │   │   │   │   ├── UserServiceTest.java      # User service unit tests
│       │   │   │   │   ├── ...                       # Other service test classes
│       │   │   │   ├── controller/
│       │   │   │   │   ├── UserControllerTest.java   # User controller unit tests
│       │   │   │   │   ├── ...                       # Other controller test classes
│       │   │   │   ├── dto/
│       │   │   │   │   ├── UserDTOTest.java          # UserDTO unit tests
│       │   │   │   │   ├── ...                       # Other DTO test classes
│       │   │   │   ├── util/
│       └── resources/
│           └── application-test.properties           # Test application properties file
└── pom.xml                                           # Maven build file


