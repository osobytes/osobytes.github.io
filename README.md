# Osobytes Blog

A minimalistic blog powered by Jekyll, hosted on GitHub Pages, featuring Markdown support, code syntax highlighting, and a sample “Hello World” post.

## Dependencies and Installation

### Runtime Environment

- **Language**: Ruby (version 2.5+ or higher)
- **Command-Line Tools**: `gem install bundler jekyll`

### Dependencies

- **Jekyll (latest)**: Core static site generator.
- **Bundler (latest)**: For Ruby dependency management.

#### Optional Plugins

- `jekyll-feed` (for Atom/RSS feeds).
- `jekyll-sitemap` (for generating a sitemap.xml).

### Installation Steps

1. Install Ruby (version 2.5+ or higher) on your system.
2. Install Jekyll and Bundler using the command `gem install bundler jekyll`.
3. Create a new Jekyll site by running `jekyll new my-blog`.
4. Navigate to the new directory `my-blog` and open the `_config.yml` file.
5. Update the `_config.yml` file to match the specifications:
   - Set the `source` directory to `./`.
   - Set the `destination` directory to `./_site`.
   - Set the `markdown` engine to `kramdown`.
   - Set the `theme` to `minima` or another minimal Jekyll theme.
   - Set the `permalink` style to `/:year/:month/:day/:title/`.
   - Enable syntax highlighting with Jekyll's built-in support.
   - Add the plugins `jekyll-feed` and `jekyll-sitemap` under the `plugins` section.

## Configuration and Customization

### Design Specifications

#### Overall Layout

- **Navigation Bar**:
  - Enabled by default.
  - Example links: Home (/), About (/about).
- **Footer**:
  - Displays copyright: © 2024 My Minimalistic Jekyll Blog.
- **Typography**:
  - Font Family: system-ui, sans-serif.
  - Heading Style: bold.
  - Body Line Height: 1.6.

#### Color Palette

- **Background Color**: #FFFFFF
- **Text Color**: #333333
- **Link Color**: #0066cc
- **Code Block Background**: #f5f2f0 (light gray for highlighting)

### Homepage

- **Title**: “Welcome to My Blog”
- **Excerpt**: “A minimalistic Jekyll blog with code examples and Markdown support.”
- **Display of Recent Posts**: Show up to 5 recent posts.
- **Category/Tags**: Display if available.

### Post Page

- **Metadata Display**: Show author, date, and categories at the top.
- **Markdown Features**: Headings, lists, images, etc.
- **Syntax Highlighting**:
  - Enabled with Jekyll’s built-in highlighter (rouge or similar).
  - Theme: “github” style.
  - Line numbers: true.

## Adding Content and Posts

1. Create a new post by adding a Markdown file in the `_posts` directory.
   - Follow the naming convention `YYYY-MM-DD-title.md`.
   - Include the front matter with metadata such as title, date, author, and categories.
   - Write the content of the post using Markdown syntax.
2. Add images, lists, and other Markdown features to the post content.
3. Use code blocks with syntax highlighting for code examples.
4. Ensure the post page displays the metadata (author, date, categories) at the top.
5. Verify that the homepage displays up to 5 recent posts and includes categories/tags if available.
