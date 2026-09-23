# TypeScript Important Commands

A quick TypeScript command cheat sheet for React, Node.js, and general TypeScript development.

## 1. Install TypeScript

Install TypeScript globally:

```bash
npm install -g typescript
```

Check the installed version:

```bash
tsc --version
```

---

## 2. Create `tsconfig.json`

Initialize TypeScript configuration:

```bash
tsc --init
```

This creates:

```text
tsconfig.json
```

---

## 3. Compile a TypeScript File

Compile a single `.ts` file:

```bash
tsc app.ts
```

This generates:

```text
app.js
```

---

## 4. Compile the Whole Project

If your project contains a `tsconfig.json`:

```bash
tsc
```

---

## 5. Watch Mode ⭐

Automatically compile when files change:

```bash
tsc --watch
```

Short version:

```bash
tsc -w
```

---

## 6. Type Check Without Generating JavaScript

Useful for checking errors only:

```bash
tsc --noEmit
```

---

## 7. Run TypeScript Directly with `tsx`

Install `tsx`:

```bash
npm install -D tsx
```

Run a TypeScript file:

```bash
npx tsx app.ts
```

Watch mode:

```bash
npx tsx watch app.ts
```

---

## 8. Create a Node.js + TypeScript Project

```bash
npm init -y
npm install -D typescript tsx @types/node
tsc --init
```

---

## 9. Important NPM Commands

Install dependencies:

```bash
npm install
```

Install a package:

```bash
npm install package-name
```

Install a development dependency:

```bash
npm install -D package-name
```

Uninstall a package:

```bash
npm uninstall package-name
```

Update packages:

```bash
npm update
```

---

## Quick Cheat Sheet

| Command | Purpose |
|---|---|
| `tsc --version` | Check TypeScript version |
| `tsc --init` | Create `tsconfig.json` |
| `tsc app.ts` | Compile a TypeScript file |
| `tsc` | Compile the project |
| `tsc -w` | Watch and compile |
| `tsc --noEmit` | Type-check without generating JS |
| `npx tsx app.ts` | Run TypeScript directly |
| `npm install` | Install project dependencies |
| `npm install -D typescript` | Install TypeScript locally |
| `npm uninstall package-name` | Remove a package |

## Most Important for Interviews

Focus on these commands:

```bash
tsc
tsc --init
tsc -w
tsc --noEmit
tsc --version
npx tsx app.ts
npm install
npm install -D package-name
```
