Put your original images here (JPG, PNG, WebP, GIF), then run:

    npm run img:derive

That writes two WebP versions of each file — img/full/ for the zoomed-in viewer
and img/thumb/ for the cards — and prints the filenames to use in
content/works.json.

Nothing in this folder is served to visitors; only img/full/ and img/thumb/ are.
Keep your originals here so you can re-derive them later at a different size.
