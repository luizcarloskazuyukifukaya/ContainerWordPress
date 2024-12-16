# ContainerWordPress

## Quick Start
- Launch Containers: Run the following command to start the containers in detached mode:
```bash
docker-compose up -d
```
This command will download the necessary images and start the WordPress and MySQL containers.

- Access WordPress: 
Open your web browser and navigate to **http://localhost:8000** (or replace localhost with your server IP) to complete the WordPress setup.

- Configure WordPress: 
Follow the on-screen instructions to set up your WordPress site, including creating an admin account.

## Application Data
The application data will be stored in the following directories that are
created within the project folder:
- ./wordpress - this is where all workpress files are stored.
- ./mysql - this is where the MySQL database files are stored.

