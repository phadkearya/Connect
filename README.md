# YourCluster

## Table of Contents
- Introduction
- Features
- Built With
- Database
- Scope for improvement

## Introduction

Create groups and socialize!
Find your topic and discuss your thoughts. And if you don't find your niche, create it!

![1](https://user-images.githubusercontent.com/95274873/178274473-1333a27f-dc6c-4186-9d76-6f2331f21218.png)

![3](https://user-images.githubusercontent.com/95274873/178274556-1a67641a-5375-4a00-b260-d0499c971cfd.png)

![2](https://user-images.githubusercontent.com/95274873/178274564-147a9c20-a001-4c08-b2d5-4682fe1e0e28.png)


## Features

The application is a forum where users can create groups and post on them. Users can lookup the posts of other users and create and delete posts. They can also create groups and join them.

![4](https://user-images.githubusercontent.com/95274873/178274652-d39e2046-9568-4d06-ac49-352aa11991ac.png)

![5](https://user-images.githubusercontent.com/95274873/178274705-ade396c3-7b2b-4ad1-9255-4483be2a32e5.png)

![8](https://user-images.githubusercontent.com/95274873/178274796-cb605979-5d64-4d3a-9b0c-757c138d9bc9.png)

![7](https://user-images.githubusercontent.com/95274873/178274803-1d5c792a-c2aa-48be-9e32-efe7a500b8b1.png)

![6](https://user-images.githubusercontent.com/95274873/178274809-9780c1ff-0e9c-478c-a632-f0e54eeca3da.png)

## Built With

- Frontend: HTML,CSS, Bootstrap
- Backend: Django

## Database

Database is maintained using inbuilt SQLite.

- Users : 
    - Username
    - Email
    - First name
    - Last name

- Groups :
    - Name
    - Slug
    - Description
    - Description_html
    - Members

- GroupMember : 
    - Group
    - User
    
- Post :
    - User
    - Created_at
    - Message
    - Message_html
    - Group
    
    
## Scope for Improvement

- Can add profile picture
- Can add like and dislike button
