# HobDrive Dashkit Template

This is a template repository for creating your own custom dashkits for HobDrive.

## Getting Started

1. **Clone this repository:** 
   Clone it via "Fork" button on GitHub.
   Rename the repository in GitHub directly, if you wish.

   Or command line:
   ```bash
   git clone https://github.com/hobdrive/template-dashkits.git my-dashkit
   cd my-dashkit
   ```

2. **Rename the template folder, to your dash desired name**
   ```bash
   cd community
   mv template my-dashkit-name
   cd my-dashkit-name
   ```

3. **Edit the community/my-dashkit-name/info.json file:**
   - Update the `name`, `description`, and `author` fields
   - Set your desired version number

4. **Customize your layout:**
   - Edit `user.layout` to create your custom dashboard design
   - Add any custom images to the `images/` folder

5. **Test your dashkit:**
   - Push your repository to github.
   - In **Hobdrive**, choose "Manage DashKits"
   - Change `Repo name` to your repo id ( `your-login/repo-name`)
   - Change `Branch` if needed.
   - Press `Update` - this will load your repo
   - Press `Install` button on your DashKit.
  
6. **Update your dashkit:**
   - After installed, you can directly Update already installed Dash.

## What's Included

- **community/template/** - A simple working dashkit with a basic layout
- **info.json** - Metadata file for your dashkit
- **user.layout** - The main layout file where you define your dashboard screens
- **images/** - Folder for custom images and graphics

## Creating Your Layout

The `user.layout` file uses HobDrive's XML-based layout language. Key concepts:

## Resources

- **Full Documentation:** See [LAYOUT_SPEC.md](https://github.com/hobdrive/hobdrive-dashkits/LAYOUT_SPEC.md) for complete layout reference
- **Main Repository:** [hobdrive-dashkits](https://github.com/hobdrive/hobdrive-dashkits) for more examples
- **Community:** Share your dashkits with the HobDrive community!

## Tips

1. **Start Simple:** Begin with the included template and gradually add complexity
2. **Test Often:** Test your layout in HobDrive after each change
3. **Use Conditionals:** Use `if` attributes to show items only when sensors are available
4. **Preview First:** The template includes a working example you can modify
5. **Image Optimization:** Keep image files small for better performance
6. **Multiple Sections:** You can create multiple dashboard screens in one layout file

## File Structure

```
my-dashkit/
├── README.md (this file)
├── LAYOUT_SPEC.md (complete syntax reference)
└── community/
    └── your-dashkit-name/
        ├── info.json (dashkit metadata)
        ├── user.layout (your dashboard layout)
        ├── README.md (optional: describe your dashkit)
        └── images/ (optional: custom graphics)
```

## Publishing Your Dashkit

When you're ready to share your dashkit:

1. Update the README in your dashkit folder with screenshots and description
2. Make sure your info.json has accurate information
3. Consider submitting a pull request to the main hobdrive-dashkits repository
4. Share with the community!

## License

This template is provided as-is for creating HobDrive dashkits. Check the HobDrive license for distribution terms.

## Need Help?

- Check LAYOUT_SPEC.md for detailed documentation
- Look at examples in the main hobdrive-dashkits repository
- Join the HobDrive community for support

Happy dashboard creating! 🚗📊
