https://www.youtube.com/watch?v=Eu-h3iUk45o&ab_channel=productioncoder

npm init -y
npm install --save sequelize
npm install --save pg pg-hstore

//use migration
npm install --save-dev sequelize-cli
npx sequelize-cli init //this will add config, mmigrations, seeders, models,

//every model correlates to a database table

//run it
npx sequelize-cli db:migrate

//if you need to undo what you just did
npx sequelize-cli db:migrate:undo

//make seed
npx sequelize-cli seed:generate --name demo-user

//run seeds
npx sequelize-cli db:seed:all
# sequelize-2
