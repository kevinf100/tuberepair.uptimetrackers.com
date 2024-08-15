# TubeRepair custom backend, using Flask and Jinja2.
- __A self-hosting solution to edit the backend to your likings.__
- __Fetches API from Invidious with no API authentication needed.__
- Works on 1.0.0 to 1.2.1
- ⚠️ This project is still in beta. You can help or suggest ideas in [bag's discord](https://discord.bag-xml.com) ⚠️

# Features
- Cache API responses
- Customizable config

### Coming soon:
- Profanity filter
- IP blacklist and whitelist
- Rate limit
- Prevent spam via User Agent
- Out of the box experience

# Setup
Make sure you have Python 3 and virtualenv installed.
```bash
# Download
git clone https://github.com/kendoodoo/tuberepair-backend
cd tuberepair-backend

# Preparing virtualenv
virtualenv tuberepair # you can use any name, but for convenience
source tuberepair/bin/activate
pip install -r requirements.txt

# Running
Remember to edit config.py before running set HOST to your server ip (yes i havent think anything better)
python main.py
```

# Contributors

- [ObscureMosquito](https://github.com/ObscureMosquito)
- [SpaceSaver](https://github.com/SpaceSaver)
- (et al.)
