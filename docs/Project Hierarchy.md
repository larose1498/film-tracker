src/
├── app/
│   ├── core/                        # Singleton services (Universal app setup)
│   │   ├── auth/                    # Atlas user authentication handlers
│   │   ├── guards/                  # Route protection
│   │   └── interceptors/            # Automatically injects headers/tokens into HTTP calls
│   │
│   ├── shared/                      # Global components, pipes, and directives
│   │   ├── components/              # Movie poster cards, custom loading spinners
│   │   └── models/                  # TypeScript interfaces (e.g., tmdb.model.ts, movie.model.ts)
│   │
│   ├── features/                    # Feature-driven modules (Smart views)
│   │   ├── dashboard/               # Main home stream
│   │   ├── search/                  # TMDB discovery engine interface
│   │   └── tracker/                 # Watchlists, Custom Lists, History
│   │
│   ├── app.component.ts
│   └── app.routes.ts                # Declarative routing mapping
│
├── assets/                          # Static icons, fallback imagery
└── environments/                    # Local build configurations (Non-sensitive configuration only!)