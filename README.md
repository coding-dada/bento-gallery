# Bento Gallery

A modern, responsive, and interactive media gallery built with Next.js and Framer Motion. This component showcases images and videos in an attractive bento grid layout with smooth animations and drag-and-drop functionality.

![Bento Gallery Screenshot](https://cdn.wallpapersafari.com/37/20/vNdX8i.jpg)

## Features

- 📱 Fully responsive design that works on all screen sizes
- 🖼️ Beautiful bento grid layout for images and videos
- 🎬 Automatic video playback when in viewport
- 🔄 Drag and drop functionality to rearrange items
- 🔍 Modal view for detailed media viewing
- 🌓 Dark mode support with customizable colors
- ✨ Smooth animations and transitions using Framer Motion

## Demo

Check out the live demo: [Bento Gallery Demo](https://bento-gallery-cd.vercel.app/)

## Installation

```bash
# Clone the repository
git clone https://github.com/abhishekabysm/glowing-effect.git
cd glowing-effect

# Install dependencies
npm install
# or
yarn install
# or
pnpm install
```

## Usage

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Customization

### Adding Your Own Media

Edit the `mediaItems` array in `app/page.tsx` to add your own images and videos:

```typescript
const mediaItems = [
  {
    id: 1,
    type: "image", // or "video"
    title: "Your Title",
    desc: "Your description",
    url: "your-image-or-video-url",
    span: "col-span-1 row-span-2 md:col-span-1 md:row-span-3 sm:col-span-1 sm:row-span-2",
  },
  // Add more items...
]
```

### Styling

The component uses Tailwind CSS for styling. You can customize the appearance by:

1. Modifying the CSS variables in `app/globals.css`
2. Adjusting the Tailwind classes in `components/interactive-bento-gallery.tsx`
3. Updating the `tailwind.config.js` file for custom breakpoints and themes

## Component Structure

- `InteractiveBentoGallery`: The main component that renders the gallery
- `MediaItem`: Renders either an image or video based on the item type
- `GalleryModal`: Displays the selected media item in a modal view

## Technologies Used

- [Next.js](https://nextjs.org/) - React framework
- [Framer Motion](https://www.framer.com/motion/) - Animation library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Authors

- Abhishek - [@abhishekabysm](https://github.com/abhishekabysm) (Instagram: [@abhishekabysm](https://instagram.com/abhishekabysm))
- Coding Tutor - [@coding.tutor](https://github.com/coding.tutor) (Instagram: [@coding.tutor](https://instagram.com/coding.tutor))

## Project Link

[https://github.com/abhishekabysm/glowing-effect](https://github.com/abhishekabysm/glowing-effect)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspiration from modern bento grid layouts
- [Unsplash](https://unsplash.com/) for sample images
- [Pixabay](https://pixabay.com/) for sample videos
