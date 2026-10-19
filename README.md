# Banking App

Banking app for Assignment 4. Create `prf-network` first, then run:

```bash
docker build -t bankingapp .
docker run -d --name bankingapp --network prf-network -p 5090:5090 bankingapp
```

Open: http://192.168.56.53:5090

Based on the [course template](https://github.com/Feranmi-A/BankingApp).
