# BetLimit Task 02 - Limit Number Set Interface

A modern React/Next.js interface for managing betting limit templates and provider configurations. This project demonstrates a clean solution for handling multiple providers with different limit templates.

## 📋 Project Overview

This is a **project task** that showcases:
- Clean UI design for limit number set management
- Multi-provider template configuration interface
- Modern React/Next.js implementation with TypeScript
- Tailwind CSS for styling
- Responsive design patterns

## 🎯 Key Features

- **Provider Management**: Clear visualization of multiple providers (dev-joe, SharkGaming)
- **Template Configuration**: Easy-to-understand template assignments per provider
- **Limit Set Interface**: Comprehensive table with search, filtering, and pagination
- **Modern UI**: Clean card-based design with consistent styling
- **Responsive Layout**: Works on desktop and mobile devices

## 🚀 Getting Started

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

### Prerequisites
- Node.js 18+ 
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone https://github.com/NullsCollection/betlimit-task-02.git
cd betlimit-task-02
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🛠️ Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Custom components with Tailwind
- **Icons**: Heroicons (SVG)

## 📁 Project Structure

```
src/
├── app/
│   ├── globals.css          # Global styles and Tailwind imports
│   ├── layout.tsx          # Root layout component
│   └── page.tsx            # Main page component (Limit Number Set interface)
```

## 🎨 UI Components

### Provider Template Cards
- Clean card layout showing provider-template relationships
- Status badges (Standard, Default)
- Action buttons for viewing details

### Limit Number Set Table
- Searchable and filterable data table
- Pagination controls
- Row selection functionality
- Responsive design

## 📝 Task Context

This project was created as a **development task** to demonstrate:
1. Problem-solving for multi-provider template confusion
2. Clean UI/UX design implementation
3. Modern React development practices
4. Responsive web design principles

## 🔧 Development

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🚀 Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

---

**Note**: This is a project task demonstration and not intended for production use.
