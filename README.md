# Zotero Better-BibTex to Overleaf Local Sync for Self-Hosted Overleaf-Instance by the Medical University of Graz
*Original idea for adaptation of [vantezzen](https://github.com/vantezzen)'s Firefox extension by [@sorlob](https://github.com/sorlob/).*

This browser extension allows syncing your Zotero library with your MedUni Graz Overleaf project using the local sync feature of [Zotero Better-BibTeX](https://retorque.re/zotero-better-bibtex/).

***Original idea for adaptation of [@vantezzen](https://github.com/vantezzen)'s Firefox extension by [@sorlob](https://github.com/sorlob/).***


## Usage
<details>
  <summary>Prerequesites</summary>
  <ul>
    <li>Zotero</li>
    <li>Better-BibTex Zotero Plugin</li>
    <li>Overleaf project hosted at MedUni Graz</li>
  </ul>
</details>

### Instructions
1. Download latest release or build your own
2. Install the extension via the Firefox Extension Manager or the Chrome 
3. Open your project on overleaf.medunigraz.at
4. Click the "New File" button on the right-hand side of the user interface
5. Select "From Better Bibtex" in the window that has now opened
6. Follow the instructions on screen on how to add your Zotero connection

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

## Development

Run the development server:

```bash
pnpm dev
```

Open your browser and load the appropriate development build.

For further guidance, [visit the Plasmo Documentation](https://docs.plasmo.com/)
