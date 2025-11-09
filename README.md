# Quick Start

- Open in VS Code Dev Container
- Create local storage dir
  - `sudo chown vscode:vscode /files`
- Create .env.local from .env.local.example
- `composer install`
- Run migration
  - `php bin/console doctrine:migrations:migrate`
- Trigger first scrape
  - `php -f bin/console -- messenger:consume -vv scheduler_default`
- `vendor/bin/rr get-binary`
- `./rr -c ./.rr.local.yaml serve`
- `fnm use 22`
- `corepack enable`
- `pnpm i`
- `pnpm build`
