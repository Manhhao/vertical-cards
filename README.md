# Vertical Cards

A lovely card template for Anki that I've made for my Yomitan dictionaries. Grand for studying on any device!

![Header Image Placeholder](header-image-placeholder.png)

## Have a quick look!

*[GIF demonstrating responsive layout and features will go here]*

- **Smart layout that adapts to your screen**: 
  - Flips horizontal when you're on your mobile or have a narrow window open
  
- **Plays nicely with dictionaries**:
  - Definitions are cyclable
  - Styling support for my converted Yomitan dictionaries.
  - Collapsible sections for some dictionareis so you're not overwhelmed with text

## How it looks

### Vertical on desktop
*[Image of vertical layout will go here]*

### Horizontal on mobile
*[Image of horizontal layout will go here]*

### All the dictionary bits working together
*[Image showing dictionary features like collapsible sections will go here]*

## Getting started

1. Pop over to the [releases page](https://github.com/yourusername/vertical-cards/releases) and download the latest version
2. Import it into your Anki
3. Create a new note type or tweak an existing one to use this template
4. **Important for dictionary styling**: If you're using one of my Yomitan dictionaries and want the proper styling, you'll need to copy the CSS files from the `dictionary-css` folder to your Anki media collection folder

### Finding your Anki media collection folder

Your Anki media collection is typically located at:

**Mac**: 
```
/Users/username/Library/Application Support/Anki2/YourProfileName/collection.media/
```

**Windows**: 
```
C:\Users\username\AppData\Roaming\Anki2\YourProfileName\collection.media\
```

**Linux**: 
```
/home/username/.local/share/Anki2/YourProfileName/collection.media/
```

Replace `username` with your system username and `YourProfileName` with the name of your Anki profile (usually "User 1" if you haven't changed it).

### If you're feeling fancy

You can customize the look and feel by tweaking these bits in the card styling section:

```css
/* Make it your own */
:root {
    --background-color: #1e1e1e;
    --content-background-color: #252525;
    --header-border-color: #777;
    /* Add whatever other colours take your fancy */
}
```

## My yomitan dictionaries

- [My Dictionary Collection](https://github.com/yourusername/dictionary-collection) - A wee collection of dictionaries that work brilliantly with this template