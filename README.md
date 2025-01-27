# Testing environment Wordpress (with Docker)

## Requirements
- Docker
- Docker Compose (optional)

## INSTALLATION
1. Clone the repository
2. Run `docker-compose up -d`
3. Open `http://localhost:8080` in your browser
4. Follow the WordPress installation steps

## USAGE
- Run `docker-compose up -d` to start the containers
- Run `docker-compose down` to stop the containers
- Run `docker-compose down -v` to stop the containers and remove the volumes
- Run `docker-compose exec wordpress bash` to open a bash shell in the WordPress container

## CONTAINERS
- WordPress: `http://localhost:8080`
- MySQL: `http://localhost:3306`
Localhost Adresses are defined in the `docker-compose.yml` file and can be changed.

## Change the WordPress version
- Change the `WORDPRESS_VERSION` in the `docker-compose.yml` file
- Run `docker-compose up -d --build` to rebuild the containers


## Possibilities: 
- Run WordPress with Docker
- Test Themes and Plugins
- Test WordPress Updates
- Test WordPress Multisite
- Test WordPress REST API
- Test Database Migrations
- Test WordPress Cron Jobs
- Test WordPress Translations
- Test WordPress Security
- Test WordPress Performance
- Test WordPress Accessibility
- Test WordPress SEO
- Test WordPress Analytics
- Test WordPress Backup and Restore
- Test WordPress Deployment
- Test WordPress Development
- Test WordPress Staging

## Features

- 

## Prerequisites

-

## Installation

- 

## Usage

-

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

...

## Contact

Florian Zeba - florian@fzeba.com

Project Link: 

---
