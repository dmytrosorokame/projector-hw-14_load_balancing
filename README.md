# Projector HSA Home work #14: Load Balancing

## To run the project:

```bash
$ docker-compose up --build
```

## To test cache functionality:

### 1. Run ngrok

```bash
$ ngrok http 80
```

### 2. Open link from Ngrok (example: https://14bc-2a02-a314-84f9-f500-4cf1-be5f-f233-6738.ngrok-free.app) in your browser

### 3. Check link on different IPs (User VPN)

#### From USA – you should see _This is the USA page._

#### From GB – you should see _This is the GB page._

#### From other countries – you should see _This is the general page._

### 4. Try to stop one of nginx containers (for example – nginx-gb)

#### Then – you should see _This is the backup page._
