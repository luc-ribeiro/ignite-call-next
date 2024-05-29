<h1 align="center">
Ignite Call 
</h1>

<div align="right">
    Clique <a href="https://github.com/luc-ribeiro/ignite-call-next/blob/main/README-PTBR.md">aqui</a> para ver a versão em Português.
</div>

<h2 align="center">Preview <a href="https://ignite-call-next-phi.vercel.app" target="_blank">Ignite Call</a></h2>

## 📄 Project
Ignite Call is a project developed to facilitate scheduling appointments using a calendar integrated with Google Calendar. 
Users have the convenience of registering in the application through their Google accounts and can then indicate the days of the week and times they are available to schedule appointments.

One of the main advantages of Ignite Call is its automatic synchronization with Google Calendar. This means that any appointment scheduled in the application is immediately reflected in the user's Google calendar. 
This integration significantly simplifies tracking appointments, allowing users to view their consolidated schedules in one place, directly on the Google platform.

For example, suppose an Ignite Call user has a doctor's appointment scheduled for Monday at 10 am. After scheduling the appointment in the application, 
it will automatically be added to their Google calendar. This way, they can easily access all their appointments, whether professional or personal, 
through the familiar and intuitive Google Calendar interface.

## 💻 Technologies

- **React**
- **Next.js**
- **TypeScript**
- **Node.js**
- **Prisma**
- **Google APIs**
- **Google Cloud Platform**
- **Docker**
- **Axios**
- **Next SEO**
- **Nookies**
- **React Hook Form**
- **Zod**
- **Design System**
- **Stitches (CSS-in-JS)**
- **Phosphor Icons**
- **ESLint**
- **date-fns**

## 🔖 Layout
### [Ignite Call - Figma](https://www.figma.com/file/1fBgGauyyzAeE9AA8w7Dzi/Ignite-Call--%E2%80%A2-Projeto-React?type=design&node-id=339-74&mode=design)

<div align="center">
  
![image](https://github.com/luc-ribeiro/ignite-call-next/assets/69688077/780d3506-7e22-4856-b8f2-1d878e44ffb6)

![Screenshot_5](https://github.com/luc-ribeiro/ignite-call-next/assets/69688077/d4fb317b-5876-4017-962e-f648d27d7bc9)

![Screenshot_6](https://github.com/luc-ribeiro/ignite-call-next/assets/69688077/c1a383bc-6b7c-4558-bef1-869e7740a982)
</div>

## 🚀 Running the project

To run the application, you will need to set up a connection to a local database or a Docker container and integrate it with Prisma.io. 
You will also need to create a project in Google Cloud Platform to obtain the essential credentials for login and integration with Google services, as detailed in the ```.env.example``` file. 
This file also includes the connection URL that Prisma will use to connect to the database.

```bash
1. Clone this repository to your machine
$ git clone https://github.com/luc-ribeiro/ignite-call-react.git

2. Install the dependencies
$ npm i

3. Run the project using the command:
$ npm run dev

- The application will be available at `http://localhost:3000`
