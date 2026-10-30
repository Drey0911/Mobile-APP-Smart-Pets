<p align="center">
  <img src="./images/logo.png" alt="Smart Pets logo" width="160"/>
</p>

<h1 align="center">Smart Pets</h1>

<p align="center">
  App móvil para agendar citas veterinarias y gestionar mascotas en tiempo real.<br/>
  <sub>Mobile app to schedule veterinary appointments and manage pets in real time.</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Android%20%7C%20iOS-3DDC84?style=flat&logo=android&logoColor=white" alt="Android | iOS"/>
  <img src="https://img.shields.io/badge/type-Mobile-0EA5E9?style=flat" alt="Mobile"/>
  <img src="https://img.shields.io/badge/year-2024-495057?style=flat" alt="2024"/>
</p>

<p align="center">
  <a href="#español">Español</a> · <a href="#english">English</a>
</p>

## Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-Framework-02569B?style=flat&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-Language-0175C2?style=flat&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Provider-State-0EA5E9?style=flat" alt="Provider"/>
  <br/>
  <img src="https://img.shields.io/badge/Firebase%20Auth-Users-FFCA28?style=flat&logo=firebase&logoColor=black" alt="Firebase Auth"/>
  <img src="https://img.shields.io/badge/Realtime%20Database-NoSQL-F57C00?style=flat&logo=firebase&logoColor=white" alt="Realtime Database"/>
  <img src="https://img.shields.io/badge/Firebase%20Storage-Images-FFCA28?style=flat&logo=firebase&logoColor=black" alt="Firebase Storage"/>
  <img src="https://img.shields.io/badge/Local%20Notifications-Push-495057?style=flat" alt="Local notifications"/>
</p>

## Screenshots

<table>
  <tr>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project4/project4-2.png" alt="Home"/>
      <br/><b>Inicio · Home</b><br/><sub>Servicios: citas, vacunación, limpieza y peluquería</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project4/project4-3.png" alt="Pets"/>
      <br/><b>Mascotas · Pets</b><br/><sub>Registro de mascotas con foto, especie, raza y edad</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project4/project4-5.png" alt="Book appointment"/>
      <br/><b>Agendar cita · Book appointment</b><br/><sub>Fecha, hora, profesional y mascota</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project4/project4-6.png" alt="Profile"/>
      <br/><b>Perfil · Profile</b><br/><sub>Modo claro y oscuro por usuario</sub>
    </td>
  </tr>
</table>

---

## Español

> Smart Pets lleva la agenda de una clínica veterinaria al celular: los usuarios registran sus mascotas, agendan citas y reciben recordatorios, mientras los datos se sincronizan al instante con Firebase.

### Funcionalidades

| Área | Descripción |
|---|---|
| **Cuenta** | Registro e inicio de sesión con Firebase Authentication. |
| **Mascotas** | Perfil de cada mascota con foto (Firebase Storage), especie, raza, sexo y edad. |
| **Citas** | Agenda de citas por servicio, fecha, hora y profesional, con historial de citas. |
| **Notificaciones** | Recordatorios de las citas agendadas. |
| **Administración** | Panel para gestionar mascotas y profesionales veterinarios. |
| **Apariencia** | Modo claro y oscuro independiente por usuario. |

### Cómo ejecutarlo

1. Requisitos: **Flutter SDK** y Android Studio o Xcode.
2. Crea un proyecto en Firebase con **Authentication**, **Realtime Database** y **Storage**, y agrega tu `google-services.json` (Android) o `GoogleService-Info.plist` (iOS).
3. Ejecuta:
   ```bash
   flutter pub get
   flutter run
   ```

---

## English

> Smart Pets brings a veterinary clinic's schedule to your phone: users register their pets, book appointments and get reminders, while data syncs instantly with Firebase.

### Features

| Area | Description |
|---|---|
| **Account** | Sign up and sign in with Firebase Authentication. |
| **Pets** | Profile for each pet with photo (Firebase Storage), species, breed, sex and age. |
| **Appointments** | Booking by service, date, time and professional, with appointment history. |
| **Notifications** | Reminders for booked appointments. |
| **Admin** | Panel to manage pets and veterinary professionals. |
| **Appearance** | Light and dark mode per user. |

### Getting started

1. Requirements: **Flutter SDK** and Android Studio or Xcode.
2. Create a Firebase project with **Authentication**, **Realtime Database** and **Storage**, and add your `google-services.json` (Android) or `GoogleService-Info.plist` (iOS).
3. Run:
   ```bash
   flutter pub get
   flutter run
   ```

---

## Autor · Author

Desarrollado por **Andrey Mantilla Leon** · Ingeniería de Sistemas. Portafolio: [drey.is-a.dev](https://drey.is-a.dev)
