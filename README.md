# scoop-stripe-cli
curl https://api.stripe.com/v1/sources \
  -u sk_test_51HpS0NBOnHIsgz26Y1mQ71loWRCHXud7ZiQ6ce7WuECZmIJQRf6BVY78IIMXJ7Dy5IUtdLv2QwKutAqdrpvR1gIc00CA1yUP1U: \
  -d type=ach_credit_transfer \
  -d currency=usd \
  -d "owner[email]"="jenny.rosen@example.com"
