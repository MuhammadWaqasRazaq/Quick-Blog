# Blog App

A full-stack blog application with a React + Vite frontend and an Express + MongoDB backend.

## Overview

This project is a blogging platform with:
- Public blog listing and individual blog pages
- Blog comments with admin moderation
- Admin dashboard for blog and comment management
- Blog creation with image upload via ImageKit
- AI-assisted blog content generation using Google Gemini

The app is split into two folders:
- `frontend/` — Vite + React SPA
- `backend/` — Express API server

## Features

### Public user features
- View published blog posts
- Navigate via homepage and blog detail pages
- Submit comments on blog posts
- View approved comments on blog posts

### Admin features
- Secure admin login with JWT authentication
- Create blogs with title, subtitle, category, image, and published/draft status
- Generate blog content using an AI prompt
- Publish or unpublish blogs
- Delete blogs
- Review, approve, or delete comments
- Dashboard summary with blog/comment counts and latest entries

## Tech Stack

### Frontend
- React 19
- Vite
- Tailwind CSS
- react-router-dom
- react-hot-toast
- Quill editor
- Axios
- marked
- moment

### Backend
- Node.js + Express
- MongoDB via Mongoose
- JWT authentication
- Multer image upload middleware
- ImageKit for image hosting
- Google Gemini AI via `@google/genai`
- CORS and dotenv
