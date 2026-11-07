# Open Studio

An open-source, mobile-friendly starter interface for an AI image/video generation website.

## Current status

This repository currently contains a static frontend only. The page lets you try the interface, select a mode, choose a model family, and pick a local image for image-to-video. It does **not** generate media or upload your prompt/image anywhere.

## Run or publish

- Open `index.html` in a browser to preview it.
- To publish with GitHub Pages, open the repository's **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. GitHub Pages may take a few minutes to publish.

## Next step: connect generation safely

Image and video generation require an inference provider or a GPU server. Add a backend endpoint that holds the provider API key as a secret; do not put API keys in `index.html` or any public JavaScript. Then connect the form to that backend and display the returned media.

Model names such as FLUX, SDXL, and Wan refer to model families, not a guarantee of free hosting or a particular license. Check the exact model version's license and the inference provider's current terms before use.

## License

MIT. See `LICENSE`.
