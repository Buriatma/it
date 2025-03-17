# Changelog

## [1.2.1] - 2025-03-17

### Changed
- Converted hero.html to use Tailwind CSS
- Removed all custom CSS styles and Bootstrap dependencies
- Added custom Tailwind configuration for colors, fonts, and animations
- Implemented auto-sliding image carousel with 5-second intervals
- Centered "Recent Projects" button
- Made slider images larger and full-width
- Improved responsive design using Tailwind breakpoints

## [1.2.0] - 2025-03-17

### Added
- New hero.html component with:
  - Modern, responsive design
  - Dark mode support
  - Animated icons and text
  - Image slider with client statistics
  - Smooth animations and transitions
  - Tailwind CSS styling

## [1.1.1] - 2025-03-17

### Changed
- Set dark mode as default theme
- Updated theme initialization logic to prioritize dark mode

## [1.1.0] - 2025-03-17

### Added
- Dark mode and light mode toggle functionality
- Inline expanding search bar with animations
- Mobile-responsive search functionality
- System theme preference detection

### Changed
- Converted all custom CSS to Tailwind CSS classes
- Updated light mode color scheme:
  - Whitish-grey background (#f5f5f5)
  - Improved text contrast with gray-700
  - White inputs and buttons with light borders
  - Light hover states (#e8e8e8)
- Enhanced button animations:
  - Theme toggle rotation
  - Search button scale effect
  - Smooth transitions

### Removed
- Custom CSS styles in favor of Tailwind
- Modal-based search in favor of inline search
- Login and signup buttons

## [1.1.0] - 2025-03-17

### Added
- New `opening.html` component with:
  - Infinite marquee animation with pause on hover
  - Responsive design using Tailwind CSS
  - Gradient text effects and rotating star icons
  - RTL support for text direction

### Changed
- Updated `hero.html`:
  - Converted to Tailwind CSS
  - Improved slider functionality
  - Added smooth animations and transitions
  - Enhanced responsive design
  - Fixed gradient buttons and text
  - Restored original animations and hover effects

### Fixed
- Text alignment and spacing in opening section
- Line height and letter spacing consistency
- Icon sizing and positioning
- Gradient text display on different browsers

## [1.0.0] - 2025-03-17

### Added
- Created responsive navbar component using Tailwind CSS
- Implemented mobile menu with smooth animations
- Added dropdown menu functionality
- Added gradient separator line
- Added custom cursor using Kursor.js
- Added hover effects with gradients
- Added proper responsive breakpoints
- Added accessibility improvements

### Features
- Responsive design that works on all screen sizes
- Mobile-first approach with hamburger menu
- Smooth animations for menu toggles
- Gradient hover effects
- Dropdown menu with submenu items
- Custom cursor integration
- Proper spacing and alignment
- Accessibility support with ARIA labels

### Technical Details
- Built with Tailwind CSS for styling
- Uses Font Awesome for icons
- Integrates Kursor.js for custom cursor
- Uses CSS Grid for layout
- Implements CSS transitions for animations
- Uses CSS gradients for visual effects

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

### Dependencies
- Tailwind CSS
- Font Awesome 6.0.0
- Kursor.js
- Animate.css

### Known Issues
None currently.

### Future Improvements
- Improve accessibility
- Add more customization options
- Add language switcher
- Add theme switcher

### Breaking Changes
None (initial release)
