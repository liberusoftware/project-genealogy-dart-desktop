# Genealogy · Dart · Desktop

Family trees, research, evidence and collaboration. Dedicated Dart desktop application with a Flutter host for Linux, macOS and Windows.

This is a presentation skeleton. Product workflows, identity integration and reviewed API adapters must be implemented and verified before production use. Module plans describe intended behavior; they are not installed or published packages.

Based on [project-boilerplate-dart-desktop](https://github.com/liberusoftware/project-boilerplate-dart-desktop) at `c216fb1250e51d4634e96f661fa2bad9ddc8b46b`.

## Start locally

Clone this repository, enter its directory and use the declared toolchain and committed lockfiles:

```bash
flutter pub get
flutter run -d linux
```

Build desktop on its target operating system with `flutter build linux`, `flutter build macos` or `flutter build windows`. Review keyboard navigation, window lifecycle, file access and scoped local storage. The native host is Flutter; application code and reusable contracts are Dart. Public `--dart-define` values cannot hold secrets. Physical-device and signed platform release checks are required before distribution and are not established by widget tests.

## Verify and extend

```bash
flutter analyze
flutter test
```

Read [AGENTS.md](AGENTS.md), [integration responsibilities](docs/INTEGRATION.md), the [presentation runbook](https://github.com/liberusoftware/documentation/blob/main/guides/presentation/DART.md) and the [product scope](https://github.com/liberusoftware/documentation/blob/main/projects/genealogy/README.md). Enable one vertical journey at a time against reviewed contracts. Verify allowed, denied, wrong-tenant, expired-session, validation and concurrency outcomes when implementing protected behavior. A pending operation is not a completed business transition.

## Other projects using Dart · Desktop

Use the same presentation foundation for other domains. These repositories provide starting structures; their availability does not establish feature parity.

| Project | Scope |
| --- | --- |
| [Boilerplate](https://github.com/liberusoftware/project-boilerplate-dart-desktop) | Shared application foundation and module composition |
| [Accounting ERP](https://github.com/liberusoftware/project-accounting-erp-dart-desktop) | Ledgers, tax, reporting and finance workflows |
| [Automation](https://github.com/liberusoftware/project-automation-dart-desktop) | AI gateways, approvals, rules and integrations |
| [Billing](https://github.com/liberusoftware/project-billing-dart-desktop) | Subscriptions, pricing, payments and provisioning |
| [Browser Game](https://github.com/liberusoftware/project-browser-game-dart-desktop) | Game worlds, players and community workflows |
| [CMS](https://github.com/liberusoftware/project-cms-dart-desktop) | Content authoring, publishing and delivery |
| [Control Panel](https://github.com/liberusoftware/project-control-panel-dart-desktop) | Infrastructure and hosting operations |
| [CRM](https://github.com/liberusoftware/project-crm-dart-desktop) | Relationships, sales pipelines and customer service |
| [Ecommerce](https://github.com/liberusoftware/project-ecommerce-dart-desktop) | Catalogs, checkout, orders and fulfillment |
| [Enterprise SAP](https://github.com/liberusoftware/project-enterprise-sap-dart-desktop) | Enterprise workspace and cross-product orchestration |
| [Liberu Platform](https://github.com/liberusoftware/project-liberu-official-dart-desktop) | Official sites, staff applications and platform composition |
| [Maintenance](https://github.com/liberusoftware/project-maintenance-dart-desktop) | Assets, work orders, schedules and field operations |
| [Music DAW](https://github.com/liberusoftware/project-music-daw-dart-desktop) | Composition, recording, sequencing and audio production |
| [Real Estate](https://github.com/liberusoftware/project-real-estate-dart-desktop) | Listings, sales, lettings and agency operations |
| [Social Network](https://github.com/liberusoftware/project-social-network-dart-desktop) | Profiles, feeds, communities and moderation |

## Other presentations for Genealogy

Choose the surface that fits the audience and deployment boundary. The Laravel core remains authoritative across these alternatives.

- [Laravel · Filament](https://github.com/liberusoftware/project-genealogy-laravel-filament): PHP/Composer Laravel host with Filament panels.
- [Laravel · Inertia · Vue](https://github.com/liberusoftware/project-genealogy-laravel-inertia-vue): Laravel routes and sessions with Vue pages over the Inertia protocol.
- [Laravel · Inertia · React](https://github.com/liberusoftware/project-genealogy-laravel-inertia-react): Laravel routes and sessions with React pages over the Inertia protocol.
- [Nuxt · Vue](https://github.com/liberusoftware/project-genealogy-nuxt-vue): Independent Vue application with Nuxt server rendering and reviewed API integration.
- [Next.js · React](https://github.com/liberusoftware/project-genealogy-next-react): Independent React application with explicit Next.js server/client boundaries.
- [React Native · Expo](https://github.com/liberusoftware/project-genealogy-mobile-react): Native iOS/Android application using React Native and Expo.
- [Flutter · Mobile](https://github.com/liberusoftware/project-genealogy-mobile-flutter): Flutter iOS/Android application using Dart and mobile widgets.
- [Dart · Mobile](https://github.com/liberusoftware/project-genealogy-dart-mobile): Separate Dart mobile application with a Flutter host for iOS and Android.

## License and delivery

See the repository license and preserve upstream notices. Review environment configuration, dependencies, backups and rollback before deployment. Publish reusable packages separately from deploying applications. The CI example, where supplied under `docs/`, must be activated with a credential authorized to manage GitHub workflows.
