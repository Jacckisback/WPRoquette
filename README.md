# WPRoquette
WP Roquette is an advanced caching and performance optimization plugin for WordPress, inspired by industry-leading solutions like WP Rocket, LSCache, and LightSpeed. WP Roquette is designed to boost your website’s speed and improve its Google PageSpeed score through a comprehensive set of features including page caching, asset optimization, image optimization, object caching support, CDN integration, HTTP/2 push, DNS prefetch, Cloudflare API integration, and more—all accessible via an intuitive admin interface.

Features
Page Caching:
Efficiently caches page outputs for non-logged in users, with support for separate caches for mobile and desktop views.

Object Cache Support:
Integrates with Redis, Memcached, or LSMCD to cache database queries and objects for enhanced performance.

Image Optimization:

Lossless and Lossy compression options
WebP image format support
Lazy-loading for images and iframes
Responsive image placeholders
Asset Optimization:

Minify CSS, JavaScript, and HTML (both inline and external)
Combine CSS and JS files to reduce HTTP requests
Automatically generate Critical CSS
Load CSS asynchronously
Defer or delay JS loading
Browser Cache Support:
Leverage browser caching to improve load times for returning visitors.

Database Cleaner & Optimizer:
Clean and optimize your database by removing revisions, orphaned metadata, and other unnecessary data.

PageSpeed Score Optimization:
Improve Core Web Vitals and overall performance metrics.

Opcode Cache Support:
Enhance PHP performance through compatibility with opcode caching systems.

HTTP/2 Push & HTTP/3/QUIC Support:
Push critical CSS/JS assets to the browser to improve perceived performance (server support required).

DNS Prefetch:
Accelerate external domain resolution with DNS prefetching.

Cloudflare API Integration:
Purge Cloudflare cache directly from the plugin settings.

WP-CLI Commands:
Manage cache operations via WP-CLI for automated control.

Multisite & Single Site Support:
Fully compatible with both WordPress multisite networks and standalone sites.

Import/Export Settings:
Easily backup and migrate your configuration across sites.

LiteSpeed Exclusive Features (Optional)
Automatic Page Caching & Intelligent Purge:
Automatically cache pages and intelligently purge related caches based on specific events.

Private Cache for Logged-in Users:
Maintain a separate cache for logged-in users to deliver personalized content without compromising performance.

REST API Caching:
Cache responses from the WordPress REST API to speed up load times.

Smart Preload Crawler:
Automatically crawl and cache pages using an SEO-friendly sitemap.

Note: LiteSpeed Exclusive features are only available if your hosting environment supports LSCache. They are compatible with the service but not guaranteed to be installed by your service provider.

Requirements
WordPress 5.0 or higher
PHP 7.0 or higher
Redis/Memcached (for Object Cache support, optional)
LSCache compatible environment (for LiteSpeed Exclusive features, optional)

Installation
Clone or Download the Repository:
bash
Copier
git clone https://github.com/yourusername/wp-roquette.git

Upload the Plugin:

Copy the wp-roquette folder into your /wp-content/plugins/ directory.

Activate the Plugin:

Log in to your WordPress admin dashboard, navigate to Plugins, and activate WP Roquette.

Configure Settings:

Access the WP Roquette settings page in your WordPress admin panel to configure CDN URLs, Cloudflare API keys, and other options.

Configuration
After installation, navigate to the WP Roquette menu in your WordPress admin dashboard. Here you can:

Set your CDN URL for asset delivery.
Configure Cloudflare API credentials for cache purging.
Enable or disable specific optimizations.
Manage cache purging rules and advanced settings.
Import/export your plugin settings for easy migration.
Usage
WP Roquette automatically caches pages for non-logged in users and integrates seamlessly with WordPress to enhance site performance. For advanced features such as object caching, Cloudflare integration, and WP-CLI commands, refer to the documentation available on the settings page.

Contributing
Contributions are welcome! If you have suggestions or bug fixes, please fork the repository and submit a pull request. For major changes, open an issue first to discuss your ideas.

License
This project is licensed under the MIT License.

Support
If you encounter any issues or have feature requests, please open an issue in the GitHub repository.

