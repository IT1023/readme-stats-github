## What's different in this fork

The upstream project appears to be abandoned, so this fork keeps it going with the following additions
(full details in [https://github.com/tuhinpal/readme-stats-github/compare/main...IT1023:readme-stats-github:main](LINK_TO_PR)):

- **Multi-language support:** English (`en`), Chinese (`zh`), Hindi (`hi`), Spanish (`es`), Arabic (`ar`), French (`fr`), Bengali (`bn`), Portuguese (`pr`), Russian (`ru`), Urdu (`ur`), and Japanese (`ja`).
- **Localized number formatting:** numbers are formatted to match the selected language.
- **Easy Vercel deployment:** added `api/index` (outside `src`) so the project can be deployed to Vercel directly.

### Usage

All original parameters still work. The new `lang` parameter selects the language,
and defaults to English if it's missing or unsupported.

[https://readme-stats-github-iota.vercel.app/api?username=it1023&cc=22272e&tc=37BCF6&ic=fff&bc=0000&lang=ja](https://readme-stats-github-iota.vercel.app/api?username=it1023&cc=22272e&tc=37BCF6&ic=fff&bc=0000&lang=ja)

# Readme Stats for Github 📈

👀 Update: Whole project is rewritten with Typescript in 30 minutes on GitHub Codespaces. 💪

## Features 🪶

- Totally accurate result
- Refresh result in 1800 seconds
- Support customization

## API 🚀

1. Cool and Simple 😃

   ```
   https://github-stats-alpha.vercel.app/api?username={your-github-username}
   ```

   [![Example](https://github-stats-alpha.vercel.app/api?username=tuhinpal "Example")](https://github-stats-alpha.vercel.app/api?username=tuhinpal "Example")

2. With Customization 😎

   ```
   https://github-stats-alpha.vercel.app/api?username={your-github-username}&cc=000&tc=fff&ic=fff&bc=000

   Where cc = Card Color
         tc = Text Color
         ic = Icon Color
         bc = Border Color
   ```

   [![Example](https://github-stats-alpha.vercel.app/api?username=tuhinpal&cc=000&tc=fff&ic=fff&bc=000 "Example")](https://github-stats-alpha.vercel.app/api?username=tuhinpal&cc=000&tc=fff&ic=fff&bc=000 "Example")

## Deploy your own 🦉

- Fork this Repo
- Go to [▲ Vercel](https://vercel.com)
- Connect with your Forked Repo
- Add your github token in Env Variables. Any variable starts with `GH_TOKEN` will be used randomly.
- Change root directory to `src`
- Deploy to fly high!

## Credits 🙏

- Idea from [github-readme-stats](https://github.com/anuraghazra/github-readme-stats "github-readme-stats") by [Anurag Hazra](https://github.com/anuraghazra "Anurag Hazra")

## Contribution 💬

Contributors are welcome. Please open an issue or pull request if you have any suggestions.

## License & Copyright 📝

- This Project is [Apache-2.0](https://github.com/tuhinpal/readme-stats-github/blob/main/LICENSE) Licensed
- Copyright 2021 by [Tuhin Kanti Pal](https://github.com/tuhinpal)
