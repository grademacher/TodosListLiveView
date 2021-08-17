To run the project:
mix deps.get
mix ecto.setup
cd assets
npm install
cd ..
mix phx.server

NOTE: may need to change postgres user password before setting up the db
