# Lazy Loading Images with Skeleton Placeholder
# [Demo Link](https://waiyanlin71.github.io/lazy-loading-image/)
Lazy loading is a technique used to defer the loading of images that are initially outside the viewport. This improves the initial page load time and overall performance of your web page. Additionally, by using a skeleton placeholder, you can provide a visual representation of the image's position while it is being loaded.

## How It Works

The code snippet demonstrates how to implement lazy loading with a skeleton placeholder using Intersection Observer. The `<meta>` tag with the `description` attribute provides a concise summary of the technique.

The HTML structure includes an `.image-container` that wraps an `<img>` element with a `data-src` attribute pointing to the image source and an `.skeleton` element for the placeholder. The CSS styles can be customized to achieve the desired look and feel.

Using the Intersection Observer, the JavaScript code observes the `.image-container` elements. When an image container enters the viewport, the associated image's `src` attribute is set to the value specified in the `data-src` attribute. The skeleton placeholder is displayed until the image is fully loaded, at which point it is hidden.

This lazy loading approach optimizes bandwidth usage and provides a smoother browsing experience for users. It ensures that images are loaded only when they are visible, improving performance and user experience.

Remember to replace `"path/to/image.jpg"` with the actual path to your image.

## Benefits

- Faster initial page load time
- Improved overall performance
- Bandwidth optimization
- Smoother scrolling and interaction
- Enhances user experience with skeleton placeholders

By implementing lazy loading with a skeleton placeholder, you can optimize your web page's performance, improve bandwidth usage, and provide a better user experience.
