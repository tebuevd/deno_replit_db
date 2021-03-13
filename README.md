# deno-replit-db

Deno port of https://github.com/replit/database-node

# Usage

```
import { Client } from "https://denopkg.com/tebuevd/deno-replit-db/index.ts";

const client = new Client();

await client.set("123", 123);
await client.get("123");

```
