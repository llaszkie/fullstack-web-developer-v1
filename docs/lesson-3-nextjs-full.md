# Lesson 3: Advanced Next.js - App Router, Server Components, and Optimization

## Overview

This lesson explores advanced Next.js features and capabilities with the modern App Router, building on the foundation established in the previous lesson.

## Learning Objectives

- Master Next.js App Router architecture and conventions
- Implement React Server Components and Client Components
- Utilize data fetching patterns with Server Components
- Optimize images, fonts, and assets
- Implement advanced routing patterns

## Key Concepts

### App Router Architecture

- Understanding the App Router directory structure
- Server Components vs. Client Components
- Route groups and layouts
- Parallel routes and intercepting routes
- Loading and error states

### Rendering Patterns

- Server Components (default in App Router)
- Client Components with "use client" directive
- Streaming and Suspense
- Static and Dynamic rendering
- Incremental Static Regeneration (ISR) with revalidation

### Data Fetching

- Server Component data fetching (async/await)
- Route handlers for API endpoints
- React Server Actions for mutations
- Caching and revalidation strategies
- Client-side data fetching with SWR or TanStack Query

### API Development

- Route handlers in the App Router
- Request and response handling
- Middleware implementation
- Error handling and validation
- CORS and security considerations

### Asset Optimization

- Next.js Image component with automatic optimization
- Font optimization with next/font
- Static asset handling
- CSS modules and styling approaches
- Metadata API for SEO

## Exercises

1. Create a blog with Server Components and dynamic routes
2. Implement route handlers and consume them from Server Components
3. Optimize images and implement loading states with Suspense
4. Add client-side data mutations with Server Actions

## Additional Resources

- [Next.js App Router Documentation](https://nextjs.org/docs/app)
- [Server Components and Data Fetching](https://nextjs.org/docs/app/building-your-application/data-fetching)
- [Route Handlers Documentation](https://nextjs.org/docs/app/building-your-application/routing/route-handlers)
- [Image Component and Optimization](https://nextjs.org/docs/app/building-your-application/optimizing/images)
- [Server Actions Documentation](https://nextjs.org/docs/app/building-your-application/data-fetching/server-actions-and-mutations)

## Next Steps

Continue to [Lesson 4: Enterprise React Architecture - Backend for Frontend (BFF) Pattern & Secure Authentication](./lesson-4-enterprise-react-1.md) to learn about providing APIs with Next.js as a Backend for Frontend (BFF) and implementing authentication.