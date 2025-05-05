# OnlyFEUP - Social Network

The main goal of the OnlyFEUP project is the development of a web-based social network with the purpose of creating connections between students and staff, sharing resources about courses and subjects. This is a tool that can be used by anyone from FEUP. After signing up and verifying the user is related to the university (students/teachers), they can start using it for a better experience at FEUP.

## Project Components

* [ER: Requirements Specification](https://github.com/marcwferreira/OnlyFEUP/blob/master/wiki/er.md)
* [EBD: Database Specification](https://github.com/marcwferreira/OnlyFEUP/blob/master/wiki/ebd.md)
* [EAP: Architecture Specification and Prototypes](https://github.com/marcwferreira/OnlyFEUP/blob/master/wiki/eap.md)
* [PA: Product and Presentation](https://github.com/marcwferreira/OnlyFEUP/blob/master/wiki/pa.md) **OBS:** Some images are not working, however the link to the video is working properly (![video](https://github.com/marcwferreira/OnlyFEUP/blob/master/docs/lbaw2255.mp4))

## Product

The final version is available in https://lbaw2255.lbaw.fe.up.pt/

```code
docker run -it -p 8000:80 --name=lbaw2255 -e DB_DATABASE="lbaw2255" -e DB_SCHEMA="lbaw2255" -e DB_USERNAME="lbaw2255" -e DB_PASSWORD="reWisDQE" git.fe.up.pt:5050/lbaw/lbaw2223/lbaw2255
```

### Credentials

- eduardanascimento@gmail.com / eduardalbaw2255 (Administrator)
- laravel@hotmail.com / password (Normal Account)

## Team

* André Correia da Costa (up201905916@fe.up.pt)
* Fábio Araújo de Sá (up202007658@fe.up.pt)
* Lourenço Alexandre Correia Gonçalves (up202004816@fe.up.pt)
* Marcos William Ferreira Pinto (up201800177@fe.up.pt)

---

GROUP lbaw 2255, 25/09/2021 - 02/01/2023
