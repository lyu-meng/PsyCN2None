# PsyCN2None (Second to None)

Currently tested with Hugo v0.150.0

## About Us

PsyCN2None (pronounced "second to none") is a dedicated nonprofit organization comprised of a small but elite team of psychology PhD applicants. We are committed to supporting undergraduate and master's students from resource-scarce backgrounds, in bridging the information gap that creates educational inequalities.

## Our Mission

We believe that students from mainland China should overcome cultural barriers and embrace confidence during their applications and interviews, moving away from traditional modesty to express their true potential. We encourage ambitious Chinese students pursuing advanced degrees in psychology, especially first-generation college students and those from environments lacking relevant information and resources.

## What We Offer

This quarter, we plan to mentor 10-13 students focusing primarily on US psychology PhD program applications. Our comprehensive support includes:

- **Personalized Guidance**: One-on-one mentorship tailored to individual needs
- **Video Conferences**: Regular virtual meetings to discuss progress and challenges  
- **Thematic Workshops**: Covering application processes, tool utilization, application material feedback, and mock interviews
- **Resource Sharing**: Access to insider knowledge and application strategies
- **Cultural Bridge**: Helping students navigate cultural differences in academic applications

## Our Goal

We aim to bridge the information gap and provide personalized advice and resources to help you navigate the US graduate school application process. From preparation to interviews, we're here to support your entire journey toward academic success in psychology.

---

*This website serves as our organization's digital platform, built with Hugo to showcase our mission, resources, and community.*

## Features

- Responsive portfolio
- Easy sections to use
- Hugo image processing for optimization
- PostCSS for autoprefixing
- SCSS for easy styling
- [Hugrid](https://github.com/aerohub/hugrid) based portfolio section
- [Somrat](https://github.com/somratpro/somrat) based design

## Getting Started

To run this website locally:

```bash
# Clone the repository
git clone https://github.com/lyu-meng/PsyCN2None.git
cd PsyCN2None

# Install dependencies
npm install

# Start the development server
npm start
```

The site will be available at `http://localhost:1313/`

## Configuration

The main configuration is in `exampleSite/hugo.toml`. You can customize the content by editing `exampleSite/data/content.yml`.

### Logo support

Images named `logo.svg` and `logo-dark.svg` are meant to be used for the logos. They should be stored in `static/images` as seen in [./exampleSite/static/images](./exampleSite/static/images). If you wish to change this, the code to control the images is in `assets/js/script.js`.

## Credits

I'd like to express gratitude to [somrat](https://github.com/somratpro/somrat) and [hugrid](https://github.com/aerohub/hugrid) for creating wonderful themes that I have used as a jumping off point. You may notice this theme is very similar in design to somrat, however it has distinct differences by using a manipulated version of hugrid for the portfolio section. I have also trimmed down the features of somrat, to only include what I wanted for a simple theme.

## Contributing

Please feel free to post issues or make pull requests at any time. I am always open to collaboration.
