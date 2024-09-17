<div align="center">
  <br />
    <a href="https://youtu.be/zfAb95tJvZQ" target="_blank">
      <img src="/mdasset/heromd.png" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Typescript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Next_._JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-OpenAI-black?style=for-the-badge&logoColor=white&logo=openai&color=412991" alt="openai" />
  </div>

  <h3 align="center">AI Podcast Platform powered by convex</h3>

   
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Features of Convex Used](#quick-start)
5. 🕸️ [Future](#snippets)

## <a name="introduction">🤖 Introduction</a>
In today’s fast-paced digital world, podcasts have become a powerful medium for sharing stories, ideas, and knowledge. But for many, the journey to create high-quality podcasts feels overwhelming—expensive equipment, complex editing software, and hours of recording can deter even the most passionate creators.

Introducing Podstar, the AI-powered SaaS platform that breaks down these barriers, enabling anyone to create, discover, and enjoy podcasts effortlessly. With just a script and a few clicks, Podstar turns your words into captivating audio content using advanced multi-voice AI technology. No recording equipment? No problem. Podstar's seamless text-to-audio conversion lets you focus on your creativity, while we handle the heavy lifting.

But we didn’t stop at creation. Podstar also features auto-generated podcast thumbnails, a seamless playback experience, and a dynamic discovery system, making it the ultimate platform for creators and listeners alike. Whether you’re a seasoned podcaster or taking your first step, Podstar is your gateway to professional-quality podcasts—crafted effortlessly with the power of AI.

Podstar is designed to break down the barriers that hold creators back, offering a seamless and intuitive platform powered by AI. Here’s how we solve the most common podcasting challenges:

💸 Cost-Effective Podcast Creation: No need to invest in expensive recording gear or software. Podstar lets you turn text into high-quality audio with multi-voice AI, allowing you to produce professional-level podcasts for free.

🛠️ No Technical Skills Required: With Podstar’s advanced AI, users don’t need any audio editing or sound engineering expertise. Simply upload your script, select your voice, and let Podstar do the rest—making the process fast, simple, and accessible to everyone.

⚡ Fast Turnaround Time: Podstar drastically reduces the time it takes to create a podcast. From script to final audio in just a few clicks, what used to take hours or days can now be done in minutes, leaving you more time to focus on content creation.

🔍 Enhanced Discovery Features: Podstar’s built-in discovery tools ensure that your podcast gets the visibility it deserves. Podcasts are featured in the home and discover sections, increasing the chances of reaching a broader audience without relying on external promotion.
## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- Convex
- OpenAI
- Clerk
- ShadCN
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Robust Authentication**: Secure and reliable user login and registration system.

👉 **Modern Home Page**: Showcases trending podcasts with a sticky podcast player for continuous listening.

👉 **Discover Podcasts Page**: Dedicated page for users to explore new and popular podcasts.

👉 **Fully Functional Search**: Allows users to find podcasts easily using various search criteria.

👉 **Create Podcast Page**: Enables podcast creation with text-to-audio conversion, AI image generation, and previews.

👉 **Multi Voice AI Functionality**: Supports multiple AI-generated voices for dynamic podcast creation.

👉 **Profile Page**: View all created podcasts with options to delete them.

👉 **Podcast Details Page**: Displays detailed information about each podcast, including creator details, number of listeners, and transcript.

👉 **Podcast Player**: Features backward/forward controls, as well as mute/unmute functionality for a seamless listening experience.

👉 **Responsive Design**: Fully functional and visually appealing across all devices and screen sizes.

and many more, including code architecture and reusability 


## <a name="quick-start">🤸 Features of Convex Used</a>


1) functions: 
- Queries
- Mutations
- Actions
- HTTP Actions
- Validation
- Error Handling
2) Database:
- Tables & Documents
- Reading Data
- Writing Data
- Document IDs
- Data Types
- Schemas
3) File Storage
- Upload
- Store
- Serve
- Delete
- Metadata
4) Authentication
- Clerk



<details>
<summary><code>Functions/ Queries</code></summary>

```css
Fetch data from the Convex database, such as retrieving podcast information or user profiles.
```
</details>





<details>
<summary><code>Functions/ Mutations</code></summary>

```css
Modify data in the Convex database, like creating new podcasts, updating user preferences, or deleting audio files.
```
</details>




<details>
<summary><code>Functions/ Actions</code></summary>

```css
Trigger server-side logic, such as processing text-to-audio conversions or sending notifications.
```
</details>


<details>
<summary><code>Functions/ HTTP Action</code></summary>

```css
HTTP actions take in a Request and return a Response following the Fetch API. HTTP actions can manipulate the request and response directly, and interact with data in Convex indirectly by running queries, mutations, and actions. HTTP actions might be used for receiving webhooks from external applications or defining a public HTTP API.
```
</details>



<details>
<summary><code>Functions/ Validation</code></summary>

```css
Ensure data integrity by validating input before it's stored in the database.
```
</details>



<details>
<summary><code>Functions/ Error Handling</code></summary>

```css
Implement error handling mechanisms to gracefully handle unexpected situations and provide informative feedback to users.
```
</details>





<details>
<summary><code>Database/ Tables & Documents</code></summary>

```css
Organize the data using tables and documents to represent different types of entities (e.g., podcasts, users, audio files).
```
</details>


<details>
<summary><code>Database/ Reading Data</code></summary>

```css
Query the database to retrieve specific data based on various criteria.
```
</details>


<details>
<summary><code>Database/ Writing Data</code></summary>

```css
Store new data or update existing data in the database.
```
</details>


<details>
<summary><code>Database/ Document IDs</code></summary>

```css
Uniquely identify individual documents within the database.
```
</details>



<details>
<summary><code>Database/ Data Types</code></summary>

```css
Use appropriate data types (e.g., strings, numbers, booleans) to represent different kinds of information.
```
</details>




<details>
<summary><code>Database/ Schemas</code></summary>

```css
Define the structure of your data to ensure consistency and maintainability.
```
</details>


<details>
<summary><code>Database/ Schemas</code></summary>

```css
Define the structure of your data to ensure consistency and maintainability.
```
</details>





<details>
<summary><code>File Storage/ Upload</code></summary>

```css
Allow users to upload audio files and other assets to the Convex storage.
```
</details>


<details>
<summary><code>File Storage/ Store</code></summary>

```css
Store uploaded files securely and efficiently.
```
</details>




<details>
<summary><code>File Storage/ Serve</code></summary>

```css
Retrieve and serve stored files to users when needed.
```
</details>



<details>
<summary><code>File Storage/ Delete</code></summary>

```css
Remove files from the storage when they are no longer required.
```
</details>



<details>
<summary><code>File Storage/ Metadata</code></summary>

```css
Store additional information about files (e.g., file name, size, upload date).

```
</details>



<details>
<summary><code>Authentication/ Clerk + Convex</code></summary>

```css
Podstar uses Clerk to handle user authentication and authorization. This provides a secure and convenient way for users to sign up, log in, and manage their accounts.
```
</details>



## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/balendu9/podstar.git
cd podstar
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'
```

Replace the placeholder values with your actual Convex & Clerk credentials. You can obtain these credentials by signing up on the [Convex](https://www.convex.dev/) and [Clerk](https://clerk.com/) websites.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.



## <a name="Future">🤸 Future</a>

🛠️ Advanced Editing Tools: Our next goal is to integrate more advanced audio editing tools, allowing users to fine-tune their podcasts after the initial AI-generated audio is produced.

📱 Mobile App: We’re working on launching a mobile app for Podstar to provide seamless podcast creation and listening on the go, making it even more accessible to a broader audience.

🎯 Monetization for Creators: In the future, we aim to offer monetization features that allow creators to earn from their podcasts through ads directly on Podstar.

🔗 Partnerships & Integrations: We’re exploring partnerships with other podcast platforms, AI services, and content creators to integrate Podstar into broader ecosystems and reach new audiences.

🌟 Community & Discovery Features: Building a community of creators and listeners is a priority, and we plan to introduce more discovery tools and community engagement features to help podcasts reach the right audience.

🚀 Scalability: As the platform grows, we’re focused on optimizing Podstar for scalability, ensuring it remains fast, reliable, and easy to use as we onboard more users.
