# Nhost GraphQL API

Nhost provides an instant, auto-generated GraphQL API powered by Hasura GraphQL Engine running on top of PostgreSQL. Every Nhost project receives a dedicated GraphQL endpoint at `https://{subdomain}.hasura.{region}.nhost.run/v1/graphql`. The schema is derived directly from the project's PostgreSQL database tables, relationships, and views — adding a table instantly exposes corresponding query, mutation, and subscription root fields with built-in filtering (`where`), ordering (`order_by`), pagination (`limit`/`offset`), and aggregate operations.

Authentication uses JWT bearer tokens issued by Nhost Auth (or an admin secret for server-side operations). Role-based access control is enforced at the row and column level via Hasura permissions: the default roles are `public` (unauthenticated) and `user` (authenticated), with support for custom roles. Real-time subscriptions are delivered over WebSocket using the `graphql-ws` or legacy `subscriptions-transport-ws` protocol. The platform also exposes built-in types for the managed auth (`auth.users`, `auth.user_roles`, `auth.user_providers`) and storage (`storage.files`, `storage.buckets`) services that every Nhost project includes automatically.

The management/control-plane GraphQL API (used by the Nhost Dashboard) is served from `https://nhost.run/v1/graphql` and covers resources such as organizations, apps (projects), regions, plans, deployments, and pipeline runs. This API requires a valid Nhost session token.

**Endpoint:** `https://{subdomain}.hasura.{region}.nhost.run/v1/graphql`

**Documentation:** https://docs.nhost.io/products/graphql

**References:**
- Documentation: https://docs.nhost.io/products/graphql
- GettingStarted: https://docs.nhost.io/get-started
