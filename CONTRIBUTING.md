## Bugs

Please submit bugs and issues here: https://github.com/inferrinizzard/prettier-sql/issues \
There are issue templates available for FORMATTING or SCRIPT related bugs.

# Development

## Setup

This project uses `yarn` as its package manager, please download it here if you don't already have it:

- yarn: https://yarnpkg.com/getting-started

Once you have `yarn` installed, you can run `yarn` in the root directory to install all dependencies and devDependencies from package.json.

You're now ready to get started !

## Branch Guidelines

New branches: Please branch off of the `develop` branch.

### Naming

Please use one of the following prefixes: (ie. feature/new-feature)

- feature/ - development towards a new feature
- dev/ - misc development not tied to a key feature / refactoring
- issue/ - fix specifically for a issue #
- bug/ - misc bug fixes not tied to a public issue
- repo/ - meta dev related changes (ie. typescript, CI/CD, dependencies)

## Testing

Tests should be run before pushing commits to a remote branch, please do so with the `test` command in package.json \
It can be invoked via:

- `yarn test`
- `npm run test`
- `jest`

## New Tests

Please add new tests for any new features and bug fixes. \
Language-specific tests should be included in their respective Test files, tests that apply to all languages should be in `behavesLikeSqlFormatter.js`

# Contributors

## `prettier-sql`

- Sean Song <mail@seansong.dev>

## `sql-formatter`

- Adrien Pyke <adpyke@gmail.com>
- Andrew
- Benjamin Bellamy
- bingou
- Damon Davison <ddavison@avalere.com>
- Davut Can Abacigil <can@teamsql.io>
- Erik Hirmo <erik.hirmo@roguewave.com>
- George Leslie-Waksman <waksman@gmail.com>
- Ian Campbell <icampbell@immuta.com>
- ivan baktsheev
- João Pimentel Ferreira
- Martin Nowak <code@dawg.eu>
- Matheus Salmi <mathsalmi@gmail.com>
- Matheus Teixeira <matheus.mtxr@gmail.com>
- Nicolas Dermine <nicolas.dermine@gmail.com>
- Offir Baron <ofir@panoply.io>
- Olexandr Sydorchuk <olexandr.syd@gmail.com>
- Rafael Pinto <raprp@posteo.de>
- Rahel Rjadnev-Meristo <rahelini@gmail.com>
- Rene Saarsoo <nene@triin.net>
- Rodrigo Stuchi
- Sasha Aliashkevich <olsender@gmail.com>
- Sergei Egorov <sergei.egorov@zeroturnaround.com>
- Tyler Jones <tyler.jones@txwormhole.com>
- Uku Pattak <ukupat@gmail.com>
