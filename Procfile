web: bin/rails s
mail: mailcatcher -f --http-port "$PORT"
worker: bin/rails jobs:work
stripe: stripe listen --forward-to localhost:3000/pay/webhooks/stripe