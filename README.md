# TypeScript for testers

This is the base setup for the **TypeScript for testers** course, proudly crafted by the [<pwts.dev>](https://pwts.dev/) team. It’s designed to help testers get started with TypeScript in the simplest and most effective way possible. Whether you're new to TypeScript or want to strengthen your fundamentals as a tester, this boilerplate will give you a clean and modern starting point.

It includes essential configurations for TypeScript, ESLint, and Prettier to ensure your code is clean, consistent, and up to the latest standards.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org) (v20 or later)
- [npm](https://www.npmjs.com/)

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/pwtsdev/ts-for-testers-base-setup.git
   cd ts-for-testers-base-setup
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Dependencies

The project includes the following **devDependencies** to support your TypeScript journey:

- `@eslint/js`
- `eslint`
- `eslint-config-prettier`
- `prettier`
- `ts-node`
- `typescript`
- `typescript-eslint`

These provide a solid foundation for linting, formatting, and compiling TypeScript smoothly.

## Scripts

The `package.json` includes basic scripts to get you started:

- `ts`: Runs `ts-node` to execute TypeScript files.

Example usage:

```sh
npm run ts src/hello.ts
```

_(Note: You can extend this setup with additional scripts for tests, builds, or other tools as you progress through the course.)_

## Configuration

Here’s what’s included out of the box:

- **TypeScript** (`tsconfig.json`):

  - Strict mode enabled
  - CommonJS modules
  - Outputs to `dist/`
  - Source maps enabled

- **ESLint** (`eslint.config.mjs`):

  - Strict type-checked setup using `typescript-eslint`
  - Best practices enforced for:
    - Naming conventions
    - Consistent type definitions
    - Avoiding unsafe TypeScript behaviors
    - Clean code style with Prettier integration

- **Prettier**:

  - Configured directly in `package.json`
  - Uses 2 spaces, enforces semicolons, single quotes, and 120 character line width

- **VSCode recommended extensions**:
  - ESLint
  - Prettier
  - TypeScript Hero (optional for helpers)

## License

This project is licensed under the ISC License.

---

## Fun Fact

TypeScript is like a safety net for JavaScript… but for testers, it's also a **superpower** 💪. Let’s make your tests type-safe and bulletproof!

Happy coding!  
Created with 💙 by pwts.dev / @bkita
