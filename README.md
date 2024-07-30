# Javaeatslite
Javeats Lite is a modular food delivery management system built with Spring Boot. It streamlines the entire food delivery process, offering robust backend support for user management, order processing, restaurant management , menu management, and more. Designed for scalability and maintainability.



# Project Structure
Javeats_Lite/
├── docs/
│   ├── ERD.pdf                         
│   └── README.md                      
├── scripts/
│   ├── seed_data.sql                  
│   └── utility_functions.sql          
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com/
│   │   │   │   ├── javeats/
│   │   │   │   │   ├── JaveatsLiteApplication.java   
│   │   │   │   │   ├── config/
│   │   │   │   │   ├── entity/
│   │   │   │   │   │   ├── User.java                
│   │   │   │   │   │   ├── UserStatus.java          
│   │   │   │   │   │   ├── UserType.java            
│   │   │   │   │   │   ├── Role.java                 
│   │   │   │   │   │   ├── ...                       
│   │   │   │   │   ├── repository/
│   │   │   │   │   │   ├── UserRepository.java       
│   │   │   │   │   │   ├── RoleRepository.java       
│   │   │   │   │   │   ├── ...                       
│   │   │   │   │   ├── service/
│   │   │   │   │   │   ├── UserService.java         
│   │   │   │   │   │   ├── RoleService.java        
│   │   │   │   │   │   ├── ...                       
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   ├── UserController.java      
│   │   │   │   │   │   ├── RoleController.java      
│   │   │   │   │   │   ├── ...                       
│   │   │   │   │   ├── dto/
│   │   │   │   │   │   ├── UserDTO.java             
│   │   │   │   │   │   ├── RoleDTO.java             
│   │   │   │   │   │   ├── ...                      
│   │   │   │   │   └── util/
│   │   │   └── resources/
│   │   │       ├── application.properties            
│   │   │       └── db-scripts/
│   │   │           ├── V1__create_user_status.sql   
│   │   │           ├── V2__create_user_type.sql     
│   │   │           ├── V3__create_role.sql          
│   │   │           ├── ...                         
│   └── test/
│       ├── java/
│       │   ├── com/
│       │   │   ├── javeats/
│       │   │   │   ├── entity/
│       │   │   │   │   ├── UserTest.java           
│       │   │   │   │   ├── ...                     
│       │   │   │   ├── repository/
│       │   │   │   │   ├── UserRepositoryTest.java   
│       │   │   │   │   ├── ...                       
│       │   │   │   ├── service/
│       │   │   │   │   ├── UserServiceTest.java      
│       │   │   │   │   ├── ...                       
│       │   │   │   ├── controller/
│       │   │   │   │   ├── UserControllerTest.java   
│       │   │   │   │   ├── ...                      
│       │   │   │   ├── dto/
│       │   │   │   │   ├── UserDTOTest.java      
│       │   │   │   │   ├── ...                     
│       │   │   │   ├── util/
│       └── resources/
│           └── application-test.properties           
└── pom.xml                                           


