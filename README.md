# Onlook T3 Template

A T3 stack template for Onlook projects with TypeScript, Next.js, tRPC, Tailwind CSS, and Drizzle ORM.

## Stack

- **Framework:** [Next.js](https://nextjs.org) with App Router
- **Language:** [TypeScript](https://typescriptlang.org)
- **Database:** [SQLite](https://sqlite.org) with [Drizzle ORM](https://orm.drizzle.team)
- **API:** [tRPC](https://trpc.io)
- **Styling:** [Tailwind CSS](https://tailwindcss.com)
- **Package Manager:** [Bun](https://bun.sh)

## Getting Started

1. Install dependencies:
   ```bash
   bun install
   ```

2. Set up the database:
   ```bash
   bun run db:push
   ```

3. Start the development server:
   ```bash
   bun run dev
   ```

## Scripts

- `bun run dev` - Start development server with Turbopack
- `bun run build` - Build for production
- `bun run start` - Start production server
- `bun run preview` - Build and preview production build
- `bun run typecheck` - Run TypeScript type checking
- `bun run lint` - Run ESLint
- `bun run format` - Format code with ESLint
- `bun run db:push` - Push schema changes to database
- `bun run db:generate` - Generate database migrations
- `bun run db:migrate` - Run database migrations
- `bun run db:studio` - Open Drizzle Studio

## Environment Variables

Copy `.env.example` to `.env` and fill in the required values:

```bash
cp .env.example .env
```

## Learn More

To learn more about the [T3 Stack](https://create.t3.gg/), take a look at the following resources:

- [Documentation](https://create.t3.gg/)
- [Learn the T3 Stack](https://create.t3.gg/en/faq#what-learning-resources-are-currently-available)

## License

Apache-2.0
