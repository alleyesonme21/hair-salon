# Eau Claire's Salon

Created: 10/9/2020
 By Johnny Duverseau

# Description

This website uses C#, ASP.NET, and MCV (plus, HTML, CSS, and Javascript) to manage the hair stylists and clients for Eau Claire's Salon in a database. The application allows the website user (e.g., salon manager) to see a list of hair stylists, view the clients of each hair stylist, and add new clients to the rdatabase. 

The website is a student project created for Epicodus, a 6-month C#/React programming bootcamp. 

## Specifications

1. When a user loads the web application, he or she will see a link to see the salon's stylists, a link to see the salon's clients, a link to a form to add a new Stylist, and a link to a form to add a new Client. 

2. When a user clicks "See Stylist," they are taken to a page that includes the first and last name of each stylist. 

3. When a user clicks "See Clients," they are taken to a page that includes the first and last name of each client.

4. When a user clicks "Add New Stylist," they are taken to a form where they can add a new Stylist including their first name, last name and the see the name of all of their clients to the Stylist database. 

5. When a user clicks "Add New Client," they are taken to a form where can add a new Client including their first name, last name and see who is their Stylist and add to the Client database. 


## Setup/Installation Requirements

_To set up and install, follow the instructions to clone the repository._

- To clone: 
- Visit GitHub and clone the repository 
- Open your terminal 
- Type “git clone” in the terminal, paste the -  GitHub URL, and press enter
- Type “code .” and the folder will open in your VScode
- Type “dotnet restore” and press enter 
- Type” dotnet  build” and press enter
- Type “dotnet run” in GitBash and your program will run 

### Database Setup
_To set up the database, follow the instructions below._ 
- To set up: 
_Create an appsettings.json file and add the code in the image below; don’t forget to change your password_
```
  {

 "ConnectionStrings": {
   
    "DefaultConnection": "Server=localhost;Port=3306;database=hair_salon;uid=root;pwd=password;"

  }

 }
 ```
 
* Open your terminal and type “dotnet restore” 
* Then, type “dotnet run”

## Support and contact details
- Discord: duverseaujohnny21 #2298
- Email: duverseaujohnny21@gmail.com
## Technologies Used
- Visual Studio Code
- C#
- .NetCore
_ Mvc
- bootstrap
- css
- MySql
## License
Copyright (c) 2020 Johnny Duverseau

This software is licensed under the MIT license.