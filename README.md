# Personal Portfolio

A professional portfolio website for freelancers, developed with pure HTML and CSS, without dependencies on frameworks or JavaScript.

## Features

- Modern and responsive design
- SEO optimized
- Modular and maintainable structure
- Optimized images with WebP format
- Use of modern CSS techniques (variables, flexbox, grid)

## Project Structure

```
/portfolio/
├── index.html
├── /css/
│   ├── base.css        ← resets, variables, typography
│   ├── layout.css      ← grid, containers, media queries
│   ├── components.css  ← buttons, cards, forms
│   ├── sections.css    ← section-specific styles
├── /assets/
│   ├── /img/
│   └── /icons/
├── /components/
│   ├── header.html
│   ├── about.html
│   ├── services.html
│   ├── portfolio.html
│   ├── contact.html
│   └── footer.html
└── README.md
```

## Deployment on Vercel

To deploy this website on Vercel, follow these steps:

1. **Create a Vercel account**
   - Visit [vercel.com](https://vercel.com) and sign up or log in.

2. **Install Vercel CLI** (optional)
   ```bash
   npm install -g vercel
   ```

3. **Connect your GitHub, GitLab, or Bitbucket repository**
   - In the Vercel dashboard, click on "Import Project".
   - Select "Import Git Repository" and connect your account.
   - Select the repository that contains this project.

4. **Configure the deployment**
   - Vercel will automatically detect that it's a static site.
   - In the project settings, establish:
     - Framework Preset: `Other`
     - Build Command: (leave blank, not necessary)
     - Output Directory: `.` (or `portfolio` if the repository includes the root folder)
     - Install Command: (leave blank)

5. **Deploy**
   - Click on "Deploy" and wait for Vercel to build and deploy your site.

6. **Alternative: Manual deployment**
   - If you prefer not to use Git, you can drag and drop the project folder onto the Vercel dashboard.
   - Or use the Vercel CLI by running `vercel` in the project folder.

7. **Custom domain** (optional)
   - In the project settings in Vercel, navigate to "Domains".
   - Add your custom domain and follow the instructions to set up DNS records.

## Customization

To customize this portfolio:

1. Replace all images in `/assets/img/` and `/assets/icons/` with your own images.
2. Update the text in `index.html` to reflect your personal information and projects.
3. Adjust the colors in `css/base.css` by modifying the CSS variables in the root.
4. Add or remove sections according to your needs.

## Image Optimization

It is recommended to optimize images before uploading:

1. Convert your images to WebP format for better performance.
2. Create small versions of each image to use with `srcset`.
3. Make sure all images have the `loading="lazy"` attribute.
4. Include `width` and `height` dimensions in all image tags.

## Contact

If you have any questions or suggestions, feel free to contact me at [your@email.com](mailto:your@email.com). 