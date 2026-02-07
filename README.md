# online-hotel

## ディレクトリ構成
```
online-hotel-monorepo/ (Public)
├── apps/
│   ├── web/               # Remix (React Router v7) / Cloudflare Pages
│   └── api/               # Python FastAPI / Render or Railway
├── packages/
│   ├── schema/            # OpenAPI (openapi.json) や共通ドキュメント
│   └── shared-types/      # 自動生成された TypeScript 型定義
├── docs/                  # アーキテクチャ図、ADR、設計書（AIに書かせる）
├── .github/workflows/     # CI/CD (Lint, Test, Deploy)
└── compose.yml            # Compose YAML（ローカル開発環境一括起動用）
```

