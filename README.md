## TODOs
- [X] Remove English-Chinese dictionaries and Japanese dictionaries at `./src/components/dictionaries
  - To recover: copy from `dev` branch, [tutorial](https://stackoverflow.com/questions/307579/how-do-i-copy-a-version-of-a-single-file-from-one-git-branch-to-another)

- [ ] Refer to the [contributing guide](./CONTRIBUTING.md) and add the following dictionaries:
1. Omorfi
  - Consider feeding dictionary form to other dicts?
    - Or a better morphology analyzer/database?
1. FinnWordNet
1. Finnish Wikidictionary
1. Kotus Kielitoimistonsanakirja
1. Sanakirja.fi
1. Sanakirja.org
1. `Cooljugator` or another inflection dictionary
1. Urbaanisanakirja.com
1. ???
- [ ] Modify translation engines
  - [ ] Consider Sanakirja.fi?
- [ ] Add spellchecker support?
  - [ ] Consider Sanakirja.fi?

- [ ] Learn basics of software development including the following from Saladict author
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?maxAge=2592000)](http://commitizen.github.io/cz-cli/)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-brightgreen.svg?maxAge=2592000)](https://conventionalcommits.org)
[![Standard - JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg?maxAge=2592000)](https://standardjs.com/)
[![License](https://img.shields.io/github/license/crimx/ext-saladict.svg?colorB=44cc11?maxAge=2592000)](https://github.com/crimx/ext-saladict/blob/dev/LICENSE)
- [ ] Migrate to [Manifest V3](https://developer.chrome.com/docs/extensions/develop/migrate)

### Optional TODOs
- [ ] Make a Mac version?
  - WHat does `./mac-app' do?
- [ ] i18n: Add Finnish locale?
- [ ] A new logo?

## From Saladict author: build from source

```bash
git clone git@github.com:crimx/ext-saladict.git
cd ext-saladict
yarn install
yarn pdf
```

Add a `.env` file following the `.env.example` format(leave empty if you don't use these dictionaries).

```bash
yarn build
```

Artifacts can be found in `build/`.

## Notes from Saladict author
Saladict 7 is a complete rewrite with sophisticated interaction and buttery smooth experience. Built for speed, stability and customization.

Chrome/Firefox WebExtension. Feature-rich inline translator with PDF support.

Saladict is a free and open-sourced project for study purpose only. Anyone can obtain a copy of Saladict free of charge. If you believe your legal rights have been violated please contact the [author](https://github.com/crimx) immediately.

Saladict is licensed under [MIT](https://github.com/crimx/ext-saladict/blob/dev/LICENSE). You can use the source code freely as long as including a copy of license and copyright notice of Saladict.

DO NOT use Saladict for any illegal or criminal activity. Saladict strongly condemns this behavior and will cooperate to the fullest extent possible in holding it accountable.

As for copy-and-paste clone products Saladict has the responsibility to send corresponding reports and warnings to platforms and users.