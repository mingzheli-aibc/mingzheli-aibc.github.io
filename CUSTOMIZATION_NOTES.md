# Website Customization Notes

## Changes Made (November 5, 2025)

### 1. Content Width Consistency
**Problem**: The first screen (Professional Summary) had wider content than the sections below (Research, Publications, etc.)

**Solution**: 
- Created custom CSS file: `static/css/custom.css`
- Added `wide-content` class to all markdown sections across all pages
- CSS makes all markdown sections match the biography section width (70rem max-width)

### 2. Font Size Alignment
**Problem**: Font sizes were inconsistent across sections

**Solution**:
- Custom CSS sets all main text to 1rem font size with 1.75rem line height
- Matches the Experience section typography
- Overrides the default `prose-xl` scaling on large screens

## Files Modified

### Homepage (content/_index.md)
- Added hidden markdown block at the top to load custom CSS
- Added `css_class: 'wide-content'` to all markdown sections:
  - 📚 My Research
  - 🎓 Open Positions (#hiring)
  - 🗞️ Recent News (#news)
  - 📑 Publications (#papers)

### Projects Page (content/projects/_index.md)
- Added hidden markdown block to load custom CSS
- Added `css_class: 'wide-content'` to Projects section

### Courses Page (content/courses/_index.md)
- Added hidden markdown block to load custom CSS
- Added `css_class: 'wide-content'` to both sections:
  - Teaching
  - Mentorship

### Experience Page (content/experience.md)
- Added hidden markdown block to load custom CSS
- CSS automatically targets `resume-experience` and `resume-awards` blocks

### Custom CSS (static/css/custom.css) - NEW
- Targets `.wide-content` class for markdown sections (70rem max-width)
- Targets `.blox-resume-experience` and `.blox-resume-awards` (70rem max-width)
- Ensures consistent font size (1rem) and line-height (1.75rem) across all sections

### Hugo Hook (layouts/partials/hooks/head-end/custom.html) - NEW
- Backup method for loading custom CSS
- Currently using inline method in content files instead

## How It Works

The custom CSS targets sections with the `wide-content` class and resume blocks:
- Sets `.max-w-prose` to `70rem` (instead of default ~42rem)
- Sets `.max-w-4xl` to `70rem` for resume blocks
- Sets font size to `1rem` and line-height to `1.75rem` for all text
- Overrides the responsive `prose-xl` scaling

## Testing

To test locally:
```bash
hugo server --disableFastRender
```

Then visit these pages and verify consistent width and font sizes:
- http://localhost:1313/ (homepage)
- http://localhost:1313/projects/
- http://localhost:1313/courses/
- http://localhost:1313/experience/
- http://localhost:1313/#hiring
- http://localhost:1313/#news
- http://localhost:1313/#papers

## Summary of Affected Pages

✅ **Homepage** - All sections (Biography, Research, Hiring, News, Publications)  
✅ **Projects** - All project listings  
✅ **Courses** - Teaching and Mentorship sections  
✅ **Experience** - Experience timeline and Awards  

All pages now have:
- **Consistent width**: 70rem max-width across all content sections
- **Consistent typography**: 1rem font size, 1.75rem line height

