# StoreIt ➺  Storage and File Sharing Platform

StoreIt is a **⚡ modern Google Drive–like storage solution 💾** built with **▲ Next.js, ⚛️ React 19, and ☁️ Appwrite**. It helps you **⬆️ upload, 🗂️ manage, and 🔗 share files 📁** effortlessly with a **🧼 clean and 📱 responsive UI**.

<br/> 

<h1 align="center"> 

<a href="https://prakhar-drive.vercel.app/"><strong> ➥ Store Your Belongings 🌆📑
</strong></a>

</h1>

<br/>

<h1  align="center" >
  <a href="https://github.com/Prakhar-002/Store-It" target="_blank">
    <img src="https://github.com/user-attachments/assets/a1b987ce-9088-4c8a-87c7-2a84a1faddbd" />
  </a>
</h1>

<br/>

# 💻 Tech Stack ⛅️🏞️
![Next.js Badge](https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=fff&style=for-the-badge) &nbsp; ![React Badge](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000&style=for-the-badge) &nbsp; ![Appwrite Badge](https://img.shields.io/badge/Appwrite-FD366E?logo=appwrite&logoColor=fff&style=for-the-badge) &nbsp; ![Tailwind CSS Badge](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=fff&style=for-the-badge) &nbsp; ![shadcn/ui Badge](https://img.shields.io/badge/shadcn%2Fui-000?logo=shadcnui&logoColor=fff&style=for-the-badge) &nbsp; ![Zod Badge](https://img.shields.io/badge/Zod-408AFF?logo=zod&logoColor=fff&style=for-the-badge) &nbsp; ![npm Badge](https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=fff&style=for-the-badge) &nbsp; ![Node.js Badge](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=fff&style=for-the-badge) &nbsp; ![Vercel Badge](https://img.shields.io/badge/Vercel-000?logo=vercel&logoColor=fff&style=for-the-badge) &nbsp; ![CSS Badge](https://img.shields.io/badge/CSS-639?logo=css&logoColor=fff&style=for-the-badge)

<br/>

# StoreIt Features 📦☁️

## **Authentication & Security 🔐**  

- `Sign Up & Log In` 🔑 Secure user authentication powered by **Appwrite**.  
- `Logout Anytime` 🚪 End your session safely with one click.  
- `Protected Access` 🛡️ Only authorized users can view and manage their data.  

<br/>

## **File Management 📂**  

- `Upload Anything` 📤 Upload documents, images, videos, and audio with ease.  
- `View & Organize` 👀 Open files in a new tab, rename, or delete them.  
- `Instant Downloads` ⬇️ Access your files anytime with quick downloads.  
- `Smart Sharing` 🤝 Share files instantly with friends, teammates, or collaborators.  

<br/>

## **Dashboard & Insights 📊**  

- `Storage Overview` 📦 See total and consumed storage at a glance.  
- `Recent Uploads` 🕒 Quickly track your latest files.  
- `File Breakdown` 📑 Get insights grouped by file type.  

<br/>

## **Search & Sorting 🔍**  

- `Global Search` 🌍 Find files and shared content across the platform instantly.  
- `Smart Sorting` ↕️ Organize by **date, name, or size** for effortless browsing.  

<br/>

## **Design & User Experience 🎨**  

- `Modern Responsive UI` 💻 Sleek, minimalist, and optimized for all devices.  
- `Clean Architecture` ⚡ Scalable codebase with reusable components.  
- `Future-Ready` 🚀 Built with **Next.js 15, React 19, and Appwrite’s latest features**.  

<br/>

# Technologies Used 👩🏻‍💻☁️  

- `next` ⚡ Latest **Next.js 15** for full-stack React applications.  
- `react` ⚛️ Core **UI library** (React 19 RC) for building dynamic interfaces.  
- `react-dom` 🌐 Handles **React rendering** in the browser.  
- `node-appwrite` 🔐 Appwrite SDK for **authentication, storage, and database**.  
- `tailwindcss` 🎨 Utility-first **CSS framework** for modern responsive design.  
- `tailwindcss-animate` 🎭 Prebuilt **animations** to enhance UI interactions.  
- `react-hook-form` 📝 Lightweight library for **form validation and handling**.  
- `@hookform/resolvers` 🔎 Seamless integration with **Zod schema validation**.  
- `zod` ✅ Schema-based **form validation** for strong type safety.  
- `react-dropzone` 📂 Drag-and-drop **file upload support**.  
- `recharts` 📊 Beautiful **charts and data visualization** for the dashboard.  
- `lucide-react` 🎨 Icon library providing **modern SVG icons**.  
- `clsx` & `tailwind-merge` ⚡ Smart **utility class management** for clean styling.  
- `use-debounce` ⏳ Efficient **debouncing** for search and input handling.  
- `radix-ui` Components 🧩 Accessible, unstyled primitives for:  
   - Dialogs, Dropdowns, Toasts, Selects, Labels, Alerts, Separators, and Slots.  

<br/>

# Installation Guide ⚙️  

Follow these steps to set up and run **StoreIt** locally:  

<br/>

## **1. Clone the Repository 📂**  

```bash
https://github.com/Prakhar-002/Store-It.git
cd Store-It
```

<br/>

## 2. Install Dependencies 📦

Make sure you have Node.js (>=18) installed, then run:

```bash
npm install
```

<br/>

## 3. Configure Environment Variables 🔑

Create a .env.local file in the root of the project and add the following variables:

```bash
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""

```

👉 Replace the empty values ("") with your Appwrite project credentials.

<br/>

## 4. Start the Development Server 🚀

Run the app locally with:

```bash
npm run dev

```

Now open 🔗 [http://localhost:3000](http://localhost:3000) in your browser.

<br/>

## 5. Build for Production 🏗️

When you’re ready to deploy:

```bash
npm run build
npm run start
```

<br/>

# Folder Structure 📒🗂️

</br>

        📦 Store-It 
            │  
            ├── 🗂️ app/                       🔸 Next.js App Router (pages & layouts)  
            │   │  
            │   ├── 🗂️ (auth)/                🔸 Authentication routes  
            |   |   |   
            │   │   ├── 🗂️ sign-in/  
            │   │   │   └── 📑 page.tsx        ⚛️ Sign-in page  
            |   |   |
            │   │   ├── 🗂️ sign-up/  
            │   │   │   └── 📑 page.tsx        ⚛️ Sign-up page  
            |   |   |   
            │   │   └── 📑 layout.tsx          🎨 Auth layout wrapper  
            │   │  
            │   ├── 🗂️ (root)/                🔸 Main app routes  
            |   |   |   
            │   │   ├── 🗂️ [type]/            🔸 Dynamic file/folder type route 
            |   |   |   | 
            │   │   │   ├── 📑 page.tsx        ⚛️ File type page  
            │   │   │   └── 📑 layout.tsx      🎨 File type layout  
            |   |   |   
            │   │   ├── 📑 page.tsx            ⚛️ Root dashboard page 
            │   │   └── 📑 layout.tsx          🎨 Root layout  
            │   │  
            │   ├── 🗂️ fonts/                 🔸 Custom project fonts  
            |   |   |   
            │   │   ├── 🎨 GeistMonoVF.woff  
            │   │   ├── 🎨 GeistVF.woff  
            │   │   └── 🎨 favicon.ico  
            │   │  
            │   ├── 🎨 globals.css             🔸 Global styles (Tailwind)  
            │   └── 📑 layout.tsx              🎨 App-wide layout wrapper  
            │  
            ├── 🗂️ components/                🔸 Reusable UI components  
            |   |    
            |   ├──  🗂️ui/                    🔸 ShadCn Reusable UI components
            |   |    |  
            │   |    ├── 📑 alert-dialog.tsx        ⚛️ Alert dialog  
            │   |    ├── 📑 button.tsx              ⚛️ Button  
            │   |    ├── 📑 card.tsx                ⚛️ Card  
            │   |    ├── 📑 chart.tsx               ⚛️ Chart  
            │   |    ├── 📑 dialog.tsx              ⚛️ Dialog  
            │   |    ├── 📑 dropdown-menu.tsx       ⚛️ Dropdown menu  
            │   |    ├── 📑 form.tsx                ⚛️ Form wrapper  
            │   |    ├── 📑 input.tsx               ⚛️ Input field  
            │   |    ├── 📑 input-otp.tsx           ⚛️ OTP input  
            │   |    ├── 📑 label.tsx               ⚛️ Form label  
            │   |    ├── 📑 select.tsx              ⚛️ Select dropdown  
            │   |    ├── 📑 separator.tsx           ⚛️ Separator line  
            │   |    ├── 📑 sheet.tsx               ⚛️ Side sheet modal  
            │   |    ├── 📑 toast.tsx               ⚛️ Toast notification  
            │   |    └── 📑 toaster.tsx             ⚛️ Toast container  
            │   │  
            │   ├── 📑 ActionDropdown.tsx      ⚛️ Action dropdown menu  
            │   ├── 📑 ActionsModalContent.tsx ⚛️ Modal content for actions  
            │   ├── 📑 AuthForm.tsx            ⚛️ Authentication form  
            │   ├── 📑 Card.tsx                ⚛️ File card component  
            │   ├── 📑 Chart.tsx               ⚛️ Data visualization chart  
            │   ├── 📑 FileUploader.tsx        ⚛️ Drag-and-drop file upload  
            │   ├── 📑 FormattedDateTime.tsx   📅 Format and display timestamps  
            │   ├── 📑 Header.tsx              📌 Top header navigation  
            │   ├── 📑 MobileNavigation.tsx    📱 Mobile-friendly nav  
            │   ├── 📑 OTPModal.tsx            🔐 OTP modal dialog  
            │   ├── 📑 Search.tsx              🔎 Global search bar  
            │   ├── 📑 Sidebar.tsx             📂 Sidebar navigation  
            │   ├── 📑 Sort.tsx                ↕️ File sorting component  
            │   └── 📑 Thumbnail.tsx           🖼️ File preview thumbnail  
            │  
            ├── 🗂️ constants/                 🔸 App constants  
            |   |   
            │   └── 📑 index.ts  
            │  
            ├── 🗂️ hooks/                     🔸 Custom React hooks  
            |   |   
            │   └── 📑 use-toast.ts            🔔 Hook for toast notifications  
            │  
            ├── 🗂️ lib/                       🔸 App utilities & API logic  
            |   |   
            │   ├── 🗂️ actions/  
            |   |   |
            │   │   ├── 📑 file.actions.ts     📂 File-related actions  
            │   │   └── 📑 user.actions.ts     👤 User-related actions  
            │   │  
            │   ├── 🗂️ appwrite/               🔸 Appwrite integration 
            |   |   | 
            │   │   ├── 📑 config.ts           ⚙️ Appwrite config  
            │   │   └── 📑 index.ts            📑 SDK exports  
            │   │      
            |   |
            |   └── 📑 utils.ts            🛠️ Helper functions
            │  
            ├── 🗂️ public/                     🔸 Static assets  
            |   |   
            │   └── 🗂️ assets/  
            |       |
            │       ├── 🗂️ icons/  
            │       ├── 🗂️ images/  
            |       |
            │       ├── 🎨 file.svg  
            │       ├── 🌍 globe.svg  
            │       ├── ⚛️ next.svg  
            │       ├── ▲ vercel.svg  
            │       └── 🪟 window.svg  
            │  
            ├── 🗂️ types/                      🔸 TypeScript type definitions  
            |   |   
            │   └── 📑 index.d.ts  
            │  
            ├── ⚙️ .env.local                  🔑 Environment variables  
            ├── ⚙️ .eslintrc.json              📏 ESLint config  
            ├── ⚙️ .gitignore                  🚫 Git ignored files  
            ├── 📑 components.json             🔧 Shadcn component config  
            ├── 📑 next-env.d.ts               📑 Next.js type definitions  
            ├── 📑 next.config.ts              ⚙️ Next.js config  
            ├── 📑 package.json                📦 Project metadata & dependencies  
            ├── 📑 package-lock.json           🔒 Dependency lock file  
            ├── 📑 postcss.config.mjs          🎨 PostCSS config  
            ├── 📑 README.md                   📘 Project documentation  
            ├── 📑 tailwind.config.ts          🎨 Tailwind CSS config  
            └── 📑 tsconfig.json               📝 TypeScript config  
