# Zotero Better-BibTex to Overleaf Local Sync for Self-Hosted Overleaf-Instance by the Medical University of Graz
*Original idea for adaptation of [vantezzen](https://github.com/vantezzen)'s Firefox extension by [@sorlob](https://github.com/sorlob/).*

This browser extension allows syncing your Zotero library with your Overleaf project using the local sync feature of [Zotero Better-BibTeX](https://retorque.re/zotero-better-bibtex/).

## Development

Run the development server:

```bash
pnpm dev
```

Open your browser and load the appropriate development build.

For further guidance, [visit the Plasmo Documentation](https://docs.plasmo.com/)

## Making production build
### Firefox
Run:

```bash
pnpm build-ff
```
## Chrome
Run:

```bash
pnpm build --zip
```

This should create a production bundle for your extension, ready to be zipped and published to the stores.

## Submit to the webstores

The easiest way to deploy your Plasmo extension is to use the built-in [bpp](https://bpp.browser.market) GitHub action. Prior to using this action however, make sure to build your extension and upload the first version to the store to establish the basic credentials. Then, simply follow [this setup instruction](https://docs.plasmo.com/framework/workflows/submit) and you should be on your way for automated submission!
