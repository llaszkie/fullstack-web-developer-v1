# Lesson 0: Preparation and Prerequisites

This lesson is designed to help you prepare for the Full-Stack Web Developer course by ensuring you have all the necessary foundational knowledge and tools set up correctly.

## Required Knowledge Check

### TypeScript Fundamentals

To succeed in this course, you should be comfortable with:

- Basic types and interfaces
- Generics
- Type inference and type assertions
- Module system

**Resources to Get Up to Speed:**

- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [TypeScript Exercise Challenges](https://typescript-exercises.github.io/)
- Practice Project: Convert a small JavaScript project to TypeScript

### Web Development Fundamentals

You should understand:

- HTML5 semantic elements
- CSS3 and modern layout techniques (Flexbox, Grid)
- JavaScript ES6+ features
- DOM manipulation
- Async programming (Promises, async/await)
- HTTP protocol basics

**Resources:**

- [MDN Web Development Learning Path](https://developer.mozilla.org/en-US/docs/Learn)
- [JavaScript.info](https://javascript.info/)
- [CSS Grid Garden](https://cssgridgarden.com/)
- [Flexbox Froggy](https://flexboxfroggy.com/)

### Git & GitHub

Essential skills include:

- Basic Git commands (clone, add, commit, push, pull)
- Branch management
- Pull requests
- Resolving conflicts

**Resources:**

- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [Interactive Git Learning](https://learngitbranching.js.org/)
- [GitHub Skills](https://skills.github.com/)

## Environment Setup

### Node.js Setup with nvm

First, we'll set up [Node Version Manager (nvm)](https://github.com/nvm-sh/nvm) to manage our [Node.js](https://nodejs.org/) installation. Using nvm makes it easy to switch between different Node.js versions as needed.

1. Visit the [nvm installation guide](https://github.com/nvm-sh/nvm#installing-and-updating) for the latest installation command. You can install nvm by running the install script:

```bash
# The curl command below will always fetch the latest version
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash
```

2. After installation, restart your terminal or run:

```bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
```

3. Install and use the latest LTS (Long Term Support) version of Node.js:

```bash
nvm install --lts      # Installs the latest LTS version
nvm use --lts         # Uses the installed LTS version
```

4. Verify your installation:

```bash
node --version        # Should show the LTS version number
npm --version         # Should show the npm version that comes with Node.js
```

> 💡 **Tip**: You can list all available Node.js versions with `nvm ls-remote` and install a specific version with `nvm install <version>`. For this course, any recent LTS version (20.x or newer) will work fine.

### Development Environment

Recommended VS Code extensions:

- ESLint
- Prettier
- TypeScript and JavaScript Language Features
- GitLens

## Practice Exercises

### Exercise 1: TypeScript Warm-up

Create a simple TypeScript application that:

- Defines interfaces for a User and a Post
- Implements some functions that use these interfaces
- Uses generics to create a type-safe data container
- Implements async operations with proper error handling

### Exercise 2: Modern JavaScript Features

Write code examples demonstrating:

- Array methods (map, filter, reduce)
- Destructuring
- Spread/rest operators
- Optional chaining
- Nullish coalescing

### Exercise 3: Git Practice

1. Create a new repository on GitHub
2. Clone it locally
3. Create a feature branch
4. Make changes and commit them
5. Create a pull request
6. Resolve an intentionally created merge conflict

## Self-Assessment

Before starting the main course, ensure you can:

- [ ] Write and debug TypeScript code
- [ ] Understand and use modern JavaScript features
- [ ] Create and style responsive web pages
- [ ] Use Git for version control
- [ ] Set up a development environment
- [ ] Handle asynchronous operations
- [ ] Use npm for package management

## Additional Learning Resources

### Video Courses and Tutorials

#### TypeScript

- [Understanding TypeScript (Udemy)](https://www.udemy.com/course/understanding-typescript/) - Comprehensive TypeScript course
- [TypeScript Deep Dive (GitBook)](https://basarat.gitbook.io/typescript/) - Free in-depth TypeScript guide
- [Microsoft's TypeScript Tutorial Series](https://www.youtube.com/playlist?list=PLlrxD0HtieHg7fUUVExY7XBAFRwpSYwwV) - Official TypeScript tutorials

#### Modern JavaScript

- [JavaScript30](https://javascript30.com/) - 30 Day Vanilla JS Coding Challenge
- [You Don't Know JS Yet](https://github.com/getify/You-Dont-Know-JS) - Deep dive into JavaScript
- [Functional Programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) - MPJ's series on functional programming

#### Web Development

- [Full Stack Open](https://fullstackopen.com/) - Modern web development with JavaScript
- [Web.dev by Google](https://web.dev/learn/) - Modern web development practices
- [CSS Tricks](https://css-tricks.com/) - Comprehensive CSS resources and tutorials

#### Git & Version Control

- [Git & GitHub for Beginners (FreeCodeCamp)](https://www.youtube.com/watch?v=RGOj5yH7evk) - Comprehensive Git tutorial
- [Advanced Git Tips and Tricks](https://www.atlassian.com/git/tutorials/advanced-overview) - Atlassian's advanced Git guides
- [Oh Shit, Git!?!](https://ohshitgit.com/) - Practical guide for common Git mistakes

### Interactive Learning Platforms

- [CodeCademy's Web Development Path](https://www.codecademy.com/learn/paths/web-development)
- [Frontend Masters](https://frontendmasters.com/learn/) - In-depth web development courses
- [Exercism's TypeScript Track](https://exercism.io/tracks/typescript)

### Technical Books

- "Clean Code" by Robert C. Martin - Principles of writing maintainable code
- "Eloquent JavaScript" by Marijn Haverbeke - Modern JavaScript programming
- "TypeScript in 50 Lessons" by Stefan Baumgartner - Practical TypeScript patterns

### Developer Blogs and Newsletters

- [DEV Community](https://dev.to/) - Community-driven programming articles
- [JavaScript Weekly](https://javascriptweekly.com/) - Weekly JavaScript news and articles
- [TypeScript Weekly](https://typescript-weekly.com/) - Latest TypeScript updates and tips

### Practice Projects

1. Build a TypeScript-based Task Manager
   - Implement CRUD operations
   - Use local storage
   - Practice type definitions
2. Create a Responsive Portfolio
   - Use modern CSS features
   - Implement accessibility best practices
   - Practice semantic HTML
3. Build a GitHub Repository Explorer
   - Use GitHub's REST API
   - Handle async operations
   - Implement error handling

## Next Steps

Once you're comfortable with all the above topics:

1. Fork the course repository
2. Complete the self-assessment checklist
3. Try the practice exercises
4. Review any weak areas using the provided resources

When ready, proceed to [Lesson 1: React Fundamentals](./lesson-1-react-fundamentals.md)
