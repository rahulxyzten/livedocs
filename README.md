<a id="readme-top"></a>

<h1>LiveDocs 🗃️ Real-Time Collaborative Document Editor</h3>

[![Repository Status](https://img.shields.io/badge/Repository%20Status-Active-dark%20green.svg)](https://github.com/rahulxyzten/livedocs)
[![Website Status](https://img.shields.io/badge/Website%20Status-Online-green)](https://livedocs-topaz.vercel.app/)
[![Author](https://img.shields.io/badge/Author-Rahul%20Behera-blue.svg)](https://www.linkedin.com/in/rahul-657euzk/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-25%20January%202025-yellow.svg)](https://github.com/rahulxyzten/livedocs)

<p align='center'>
  <img src = "https://github.com/user-attachments/assets/80595ac9-497c-4b98-95cf-3ddc157057dd" width="700">
<p>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🖼️ [Screenshots](#screenshots)

## <a name="introduction">🤖 Introduction</a>

**LiveDocs** is a powerful real-time collaborative document editor designed to enhance teamwork, communication, and document management. Built with **Next.js** to handle the user interface, **Liveblocks** for real-time features, and styled with **TailwindCSS**, LiveDocs is a clone of **Google Docs**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## <a name="tech-stack">⚙️ Tech Stack</a>

* ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
* ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
* ![Liveblocks](https://img.shields.io/badge/Liveblocks-black?style=for-the-badge&logo=liveblocks&logoColor=white)
* ![Lexical Editor](https://img.shields.io/badge/Lexical%20Editor-%230079CC.svg?style=for-the-badge&logo=lexical&logoColor=white)
* ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
* ![ShadCN](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## <a name="features">🔋 Features</a>

👉 **Authentication**: Secure user authentication and session management with Clerk.

👉 **Collaborative Text Editor**:
   - Real-time multi-user editing.
   - Live cursors to display collaborator presence and activity.

👉 **Documents Management**
   - **Create Documents**: Users can create new documents, which are automatically saved and listed.
   - **Delete Documents**: Users can delete documents they own.
   - **Share Documents**: Users can share documents via email or link with view/edit permissions.
   - **List Documents**: Display all documents owned or shared with the user, with search and sorting functionalities.

👉 **Comments**:
   - Inline and general comments.
   - Threaded discussions with tagging and emojis.

👉 **Floating Comments**: Effortless feedback system with smooth UX.

👉 **Active Collaborators on Text Editor**: Show active collaborators with real-time presence indicators.

👉 **Notifications**: Notify users of document shares, new comments, and collaborator activities.

👉 **Performance Monitoring**: Sentry integration for seamless error detection and performance tracking.

👉 **Responsive**: The application is responsive across all devices.

and many more, including code architecture and reusability 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites** Make sure you have the following installed on your machine:

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)

**Cloning the Repository:**

```bash
git clone https://github.com/rahulxyzten/livedocs.git
cd livedocs
```

**Installation** Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables** Create a new file named `.env` in the root of your project and add the following content:

```env
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk & LiveBlocks credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/) and [Liveblocks](liveblocks.io/) website.

**Running the Project:**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## <a name="screenshots">🖼️ Screenshots</a>

<div align='center'>
  <p align="center">
    <img width="45%"src="https://github.com/user-attachments/assets/55af76c9-fcca-45c3-8a58-9aa74718605e">
    <img width="45%"src="https://github.com/user-attachments/assets/728bc943-28f6-4934-bd08-22a811a2c99b">
    <br/>
    <br/>
    <br/>
    <img width="45%"src="https://github.com/user-attachments/assets/a0bddeca-5c15-48f6-a329-b3ba416d9370">
    <img width="45%"src="https://github.com/user-attachments/assets/e0286a9e-282c-4941-8753-a618c714944c">
  </p>
</div>
 <br/>
 <br/>

<p align="center">Grateful to <strong>JSM (JavaScript Mystery)</strong> for the guidance and tutorial on this project!</p>
<p align="center">
  <a href="#">
    <img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="Built with Love">
  </a>
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
