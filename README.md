<p align="center"><img alt="ngrok" width="250" src="https://ngrok.com/static/img/ngrok-white.svg"></p>
<h3 align="center">
# localhost on internet
</h3>

<h1 align="center">Add key & Install </h1>

If you downloaded the Ngrok binary, run the following command:

```bash
./ngrok config add-authtoken example_2ErL1H2PiB6x9YjYBwyHg9GMQDJ_7bndicRjHmpPooVDnR1b8
```
Now install:
```bash
curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | \
      sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && \
      echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | \
      sudo tee /etc/apt/sources.list.d/ngrok.list && \
      sudo apt update && sudo apt install ngrok
```

Getting started from dashboard - [here](https://dashboard.ngrok.com/get-started/setup)

Read more about config:
- https://ngrok.com/docs/getting-started


Or You can try:
- https://theboroer.github.io/localtunnel-www/
