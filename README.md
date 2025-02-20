# Zotero Better-BibTex to Overleaf Local Sync for Self-Hosted Overleaf-Instance by the Medical University of Graz
*Original idea for adaptation of [vantezzen](https://github.com/vantezzen)'s Firefox extension by [@sorlob](https://github.com/sorlob/).*

This browser extension allows syncing your Zotero library with your Overleaf project using the local sync feature of [Zotero Better-BibTeX](https://retorque.re/zotero-better-bibtex/).

***Original idea for adaptation of [@vantezzen](https://github.com/vantezzen)'s Firefox extension by [@sorlob](https://github.com/sorlob/).***

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

## Usage
<details>
  <summary>Prerequesites</summary>
  - Zotero
  - Better-BibTex Zotero Plugin
</details>

### Instructions
1. Download latest release or build your own
2. Install the extension via the Firefox Extension Manager or the Chrome 
3. Open your project on overleaf.medunigraz.at or overleaf.com
4. Click the "New File" button on the righthand side of the user interface
5. Select "From Better Bibtex" in the window that has now opened
6. Follow the instructions on screen on how to add your Zotero connection

This should create a production bundle for your extension, ready to be zipped and published to the stores.

## Submit to the webstores

The easiest way to deploy your Plasmo extension is to use the built-in [bpp](https://bpp.browser.market) GitHub action. Prior to using this action however, make sure to build your extension and upload the first version to the store to establish the basic credentials. Then, simply follow [this setup instruction](https://docs.plasmo.com/framework/workflows/submit) and you should be on your way for automated submission!
