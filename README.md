# Vice Type Cover Studio

Vice Type Cover Studio is a browser-based cover maker for creating colorful, GTA-inspired 1080 x 1080 artwork from a photo. It runs entirely in the browser, and no uploaded image is sent to a server.

## Open the app

From the project folder, start the local static server:

```bash
node serve.ts
```

Then open [http://localhost:8080](http://localhost:8080) in a browser.

You can also open `app/index.html` directly in a browser. The app is self-contained and does not need a build step or external packages.

## Make a cover

1. Choose **Photo** and select a PNG, JPG, or WebP image from your device.
2. Edit the **Title** and **Caption** fields to change the text shown on the cover.
3. Choose a **Mood** to apply a sunset, neon, or tropical color treatment.
4. Select one of six layouts: Classic, Split, Ribbon, Frame, Stack, or Minimal.
5. Use the **Text size** and **Photo zoom** sliders for fine adjustments.
6. Preview the result in the 1080 x 1080 canvas.

If no photo is selected, the app uses a built-in illustrated city scene. Use the reset button to restore the original title, caption, mood, layout, and slider values.

## Export PNG

Press **Download PNG** to save the finished 1080 x 1080 cover as `vice-type-cover.png`.
