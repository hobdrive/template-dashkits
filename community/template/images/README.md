# Images Directory

Place your custom images and graphics here.

## Supported Formats
- PNG (recommended for transparency)
- JPG/JPEG (for photos)
- SVG (vector graphics)

## Usage in Layout

Reference images in your `user.layout` file using decorators:

```xml
<item id="RPM">
  <image zorder="bottom" 
         path="images/gauge-background.png" 
         scale="1.5"/>
  <image zorder="top" 
         path="images/needle.png" 
         rotate='$${ Sensor_Value * 2 }' 
         scale="1.0"/>
</item>
```

## Tips
- Keep images optimized for mobile devices
- Use relative paths starting with "images/"
- Organize images in subdirectories if you have many
- Use descriptive filenames
