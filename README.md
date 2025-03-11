# JANO - Modern Note-Taking Application

![Jano Logo](/public/logo-black.png)

## Overview

JANO is a modern note-taking application designed to help users organize their thoughts, tasks, and ideas efficiently. With a clean, intuitive interface and powerful features, JANO makes note management simple and effective.

## Key Features

- **Notebook Organization**: Create and manage multiple notebooks to categorize your notes
- **Kanban-Style Note Management**: Drag and drop notes between different status columns
- **Rich Text Editing**: Format your notes with markdown support
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Dark/Light Mode**: Choose your preferred theme
- **AI-Powered Features**: Smart notebook selection and content processing

## Technical Stack

- **Frontend**: Vite, TypeScript, React, TailwindCSS, Shadcn/UI
- **Backend**: Supabase (PostgreSQL, Authentication, Storage)
- **Deployment**: Vercel

## Project Information

- **Version**: 1.0.0
- **License**: MIT
- **Author**: Ndeto A.

## Logo Files

The following logo files are available in the `public` directory:

- `logo-black.png` - Logo with black color (for light mode)
- `logo-white.png` - Logo with white color (for dark mode)

## Editing and Deploying

### Local Development

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`
4. Open your browser at `http://localhost:8080`

### Supabase Functions

To deploy Supabase Edge Functions:

```bash
cd supabase
npx supabase functions deploy process-natural-language
```

### Building for Production

```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

## Application Overview

JANO is a modern, feature-rich note-taking application designed to help users organize their thoughts, ideas, and tasks efficiently. The application provides a structured approach to note management through notebooks, prioritization, and status tracking.

### Key Features

- **Notebook Organization**: Create and manage multiple notebooks to categorize your notes
- **Kanban-Style Note Management**: Track notes through different statuses (Ideas, Todo, In Progress, Review, Complete)
- **Priority System**: Assign priorities (Urgent, High, Medium, Low) to notes
- **Favorites**: Mark important notes as favorites for quick access
- **Analytics Dashboard**: Visualize your note-taking patterns and productivity
- **User Profiles**: Personalize your experience with custom profiles
- **Settings Management**: Configure application behavior to suit your preferences
- **Responsive Design**: Works seamlessly across desktop and mobile devices

### Technical Stack

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
- Supabase (Authentication and Database)
- React Query for data fetching
- React Router for navigation