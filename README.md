<p align="center"><a href="https://react-telephone.joris.re/"><img alt="react-telephone - Demo" src="https://github.com/jorisre/react-telephone/raw/main/examples/public/cover.gif"/></a></p>

<p align="center">
  <a href="https://bundlephobia.com/result?p=react-telephone">
    <img src="https://img.shields.io/bundlephobia/minzip/react-telephone?style=for-the-badge" />
  </a>
  <a href="#contributors-">
    <img alt="All Contributors"  src="https://img.shields.io/badge/all_contributors-2-black.svg?style=for-the-badge" />
  </a>
</p>
<br />
<div align="center"><strong>☎️ react-19-telephone</strong></div>
<p align="center">
Tiniest react input phone component (auto formating included)
</p>
<p align="center">
This forked version of <a src="https://github.com/jorisre/react-telephone">react-telephone</a> is compatible with projects using React 19. 
</p>

<br />
<p align="center">
<a href="https://react-telephone.joris.re">Demo</a> 
<span> · </span>
  <a href="https://github.com/jorisre/react-telephone#installation">Documentation</a> 
<span> · </span>
<a href="https://twitter.com/_jorisre">Twitter</a>
  <sub>Created by <a href="https://joris.re">Joris</a></sub>
</p>

## Features

- 🌐 Follows the **[E.164 : The international public telecommunication numbering plan](https://www.itu.int/rec/T-REC-E.164-201011-I/en)**
- 🎨 **Easily Customizable**
- 🪶 **Lightweight** - _less than 6kb_
- 📞 **Native** - _it's just a HMTL input_
- 🔌 **easily integration** - _it works without additional configuration (remix, react-hook-form)_
- [ ] Controlled mode: coming soon
- [ ] Custom render for `Phone.Country` and `Phone.Number`: coming soon

### Examples (<a href="https://react-telephone.joris.re">Demo</a>)

- [Basic](https://github.com/jorisre/react-telephone/blob/main/examples/src/components/samples/Basic.tsx)
- [Tailwind Css](https://github.com/jorisre/react-telephone/blob/main/examples/src/components/samples/Tailwind.tsx)
- [Styled Components](https://github.com/jorisre/react-telephone/blob/main/examples/src/components/samples/StyledComponents.tsx)
- [Css Modules](https://github.com/jorisre/react-telephone/blob/main/examples/src/components/samples/CssModules.tsx)
- [Inline Styles](https://github.com/jorisre/react-telephone/blob/main/examples/src/components/samples/InlineStyles.tsx)
- [React Hook Form](https://github.com/jorisre/react-telephone/blob/main/examples/src/components/samples/ReactHookForm.tsx)

## Installation

```sh
yarn add react-telephone
```

or

```sh
npm i react-telephone
```

## Usage

```tsx
import { Phone } from 'react-telephone';

export default function MyComponent() {
  return (
    <Phone>
      <Phone.Country />
      <Phone.Number />
    </Phone>
  );
}
```

## Props

| Prop             | Description                                        | Default                       |                                                                    Value |
| :--------------- | :------------------------------------------------- | :---------------------------- | -----------------------------------------------------------------------: |
| `defaultCountry` | Default country displayed for the country selector | First country _(Afghanistan)_ | Country [ISO2 code](https://en.wikipedia.org/wiki/ISO_3166-2) _(fr, us)_ |

## Utils

| Name               | Description                                        |
| :----------------- | :------------------------------------------------- |
| `countries`        | List of all countries.                             |
| `getCountryByIso`  | Returns the country object for a given ISO code.   |
| `applyMask`        | Apply the mask to a given phone number.            |
| `splitPhoneNumber` | Split a phone number into country code and number. |
| `replaceDialCode`  | Replace the dial code of a phone number.           |

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://joris.re"><img src="https://avatars.githubusercontent.com/u/7545547?v=4?s=100" width="100px;" alt="Joris"/><br /><sub><b>Joris</b></sub></a><br /><a href="https://github.com/jorisre/react-telephone/commits?author=jorisre" title="Code">💻</a> <a href="https://github.com/jorisre/react-telephone/commits?author=jorisre" title="Documentation">📖</a> <a href="#ideas-jorisre" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/jorisre/react-telephone/pulls?q=is%3Apr+reviewed-by%3Ajorisre" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Kcazer"><img src="https://avatars.githubusercontent.com/u/609420?v=4?s=100" width="100px;" alt="Michaël Rézac"/><br /><sub><b>Michaël Rézac</b></sub></a><br /><a href="#ideas-Kcazer" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/jorisre/react-telephone/commits?author=Kcazer" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://varevarao.dev"><img src="https://avatars.githubusercontent.com/u/3070869?v=4?s=100" width="100px;" alt="Varshneya Rao"/><br /><sub><b>Varshneya Rao</b></sub></a><br /><a href="https://github.com/jorisre/react-telephone/commits?author=varevarao" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
