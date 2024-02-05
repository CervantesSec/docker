![Cervantes logo](https://raw.githubusercontent.com/CervantesSecurity/.github/main/profile/logo-horizontal2.png)

[![GITHUB](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CervantesSec)
[![TWITTER](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Cervantes_Sec)
[![DISCORD](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/BvzNjT3Qzc)
[![DOCS](https://img.shields.io/badge/-DOCS-success?style=for-the-badge&logo=readthedocs&logoColor=white)](https://cervantessec.github.io/docs/)

Cervantes is an opensource collaborative platform for pentesters or red teams who want to save time to manage their projects, clients, vulnerabilities and reports in one place. 

## Technologies

![DOTNET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![CSHARP](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![RIDER](https://img.shields.io/badge/Rider-000000?style=for-the-badge&logo=Rider&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## Features
* OpenSource
* Multiplatform
* Multilanguage
* Team Collaboration
* BuiltIn dashbaords and analytics
* Manage your clients and Offensive Security projects
* One click reports creation
* And more

## Runtime requirements

- Docker
- Docker compose

## How to run it locally with Docker compose

* First you need to clone this repository

```sh
git clone https://github.com/CervantesSec/docker.git
```

* After that you need to start your docker containers:

```sh
docker-compose -p cervantes -f docker-compose.yml up -d
```

* After this, open your browser at http://localhost or https://localhost and you will see the Cervantes login page.

### Default User and Password

When you first launch the Cervantes application, a default user is created for you. The default username is `admin@cervantes.local`.

The password for this user is generated randomly during the creation of the application container and the first launch of the application. This means that the password is unique for each instance of the application and provides an additional layer of security.

<img src="https://raw.githubusercontent.com/CervantesSec/.github/main/profile/password-generation.png"  width="800" height="500">

Please note that it's important to change the default password as soon as possible to ensure the security of your application. You can do this by logging in with the default user and navigating to the user settings page.

Remember, the security of your application is paramount. Always use strong, unique passwords and change them regularly.

## How to contribute

Here are some things you could do to become a contributor:

- **★ Star this project on Github ★**
- Suggest new features or ideas 
- Improve the code of the platform components
- Report security issues

Before you jump to make any changes make sure you have read the [contributing guidelines](CONTRIBUTING.md). This would save us all time. Thanks!

## How to report bugs

If you have bugs to report please use the [issues](https://github.com/CervantesSec/cervantes/issues) tab on Github to submit the details.

## Contributors

[@Lekow](https://github.com/lekow)

