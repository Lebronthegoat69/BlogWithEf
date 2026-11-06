# Blog With Entity Framework Core

## Description
BlogWithEf is an ASP.NET Core MVC application that allows users to create, view, edit, and delete blog posts. The application uses Entity Framework Core with a SQLite database to store blog post information.

## Features
- Create new blog posts.
- View all blog posts.
- View individual post details.
- Edit existing blog posts.
- Delete blog posts.
- Store blog posts in a SQLite database.
- Display post creation dates.

## Technologies Used
- C#
- ASP.NET Core MVC
- Entity Framework Core
- SQLite
- Razor Views
- Visual Studio 2022

## Database
The application uses Entity Framework Core and SQLite. The database contains a `Posts` table with the following fields:

- `Id`
- `Title`
- `Body`
- `CreatedUtc`

Database migrations are used to create and update the database schema.

## How to Run
1. Clone or download this repository.
2. Open the project in Visual Studio.
3. Restore the NuGet packages.
4. Run the Entity Framework Core database migration using `Update-Database` if needed.
5. Run the application.
6. Navigate to the Posts page to manage blog posts.
<img width="596" height="297" alt="image" src="https://github.com/user-attachments/assets/851a7640-6873-41c8-afb4-602f1b7f243a" />
<img width="774" height="228" alt="image" src="https://github.com/user-attachments/assets/01a05f12-30ec-49e4-85b6-a10eb0617945" />
<img width="975" height="162" alt="image" src="https://github.com/user-attachments/assets/0015695f-4e8b-4d73-992a-8a9f590454fa" />
<img width="853" height="229" alt="image" src="https://github.com/user-attachments/assets/686776be-2593-4c9f-8d02-b2282a037cf8" />
<img width="739" height="248" alt="image" src="https://github.com/user-attachments/assets/8ffcd43a-c9f9-4cb9-9a16-cccb813c51bc" />
<img width="691" height="243" alt="image" src="https://github.com/user-attachments/assets/fae60689-22cd-480e-9649-86ef07309143" />

## Author
Sam
