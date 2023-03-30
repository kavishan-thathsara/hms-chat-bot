# Install hSenid Mobile's Multilingual Chat Bot using helm chart !

## About the namespace
All the resources will be created inside the `hms-bot` namespace which create automatically when your are installing the bot.

## Configure a host name

Open the `values.yaml` file.
```bash
vim HMS-Smart-Chat-Bot/values.yaml
```

Then, edit the host name in below section.
```bash
routes:
  hostName: <input_your_host_name>
```

## Install the helm chart

Open the `values.yaml` file.
```bash
helm install hms-chatbot HMS-Smart-Chat-Bot/
```