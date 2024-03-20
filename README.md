git clone https://github.com/brunocaldara/whaticket2024.git

#BACKEND
cd whaticket2024/backend
npm install
npm run build
npm run db:migrate
npm run db:seed
npm start

#FRONTEND
cd whaticket2024/frontend
npm install
npm run env-build
npm env-start
