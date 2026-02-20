# branding-assets

Image assets for Streamers associated with LC85.

## Usage
These assets are provided for use in live streams, recorded content, and official OBS overlays related to LC85.

Streamers may:
- Use these images in OBS as overlays
- Resize them proportionally for layout purposes
- Display them during live or recorded content

## Restrictions
These assets are official branding materials.

They may **not** be:
- Altered
- Edited
- Recolored
- Distorted
- Cropped
- Modified in any way
- Used to create derivative works

The integrity of the artwork and branding must remain unchanged. If you require a variation, alternate format, or specific sizing, please request it directly rather than modifying the original files.
---

## How to Use in OBS (Browser Source)

These assets are intended to be used via URL inside OBS.

1. Copy the provided raw GitHub image URL.
2. In OBS, go to **Sources**.
3. Click the **+** button.
4. Select **Browser**.
5. Name the source and click **OK**.
6. Paste the image URL into the **URL** field.
7. Set width and height as needed.
8. In the **Custom CSS** field, ensure the background is transparent:

```css
body {
    margin: 0;
    background: rgba(0,0,0,0);
}
