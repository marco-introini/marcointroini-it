# Deploy

- clone repo
- npm install
- npm run build
- sudo cp _deploy/nginx.conf /etc/nginx/sites-available/marcointroini.it
- sudo ln -s /etc/nginx/sites-available/marcointroini.it /etc/nginx/sites-enabled/
- sudo service nginx reload
- sudo certbot -nginx
- sudo service nginx reload
