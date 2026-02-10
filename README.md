# Cyber Security

## Information
 - Puttipong Joywong(Mic)
 - 6602041620114
 - s6602041620114@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Running a Service
### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -d db.yaml up #background
```

### Admin
```sh
docker compose -f admin.yaml up #monitoring
docker compose -f admin.yaml up -d #background
```
### App
```sh
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up -d #background
```
