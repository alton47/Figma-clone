# Figma clone

A minimalistic Figma clone to demonstrate real-world features such as live collaboration with cursor chat, comments, reactions, and drawing designs (shapes, image upload) on the canvas using fabric.js.

# [Live site](https://figma-clone-omega.vercel.app/)

![gh](https://github.com/alton47/Figma-clone/assets/79355369/2e6c98ce-21fa-4bf3-810f-76a2f5a96b90)

This project aims to replicate the core functionalities of Figma, allowing multiple users to collaborate simultaneously on a design canvas. Users can interact with various tools to create shapes, upload images, and communicate in real-time through cursor chat, comments, and reactions.

## Tech Stack

- Next.js
- TypeScript
- Liveblocks
- Fabric.js
- Shadcn
- Tailwind CSS

## Quick Start

To set up the project locally on your machine, follow these steps:

**Prerequisites:**

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository:**
Install the project dependencies using npm:
To install the dependencies, run:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
```

Replace the placeholder values with your actual Liveblocks credentials. You can obtain these credentials by signing up on the [Liveblocks website](https://liveblocks.io).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
