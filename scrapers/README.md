Requires Python 3.7.0 or above. I personally like [pyenv](https://github.com/pyenv/pyenv#installation) for managing versions.

## Setup
``` shell
pyenv install 3.7.0
pyenv virtualenv 3.7.0 matkonot
pyenv activate matkonot
pip install -r requirements
```

## Run
``` shell
python main.py
```

This will get the party started and launch some parallel scrapers.  
You can follow their progress with `tail -f log`. Once the fetching has ended, a file named `recipes_DD_MM_YYYY.db` will appear at this very directory. It should be placed under `../server/` before launching the server.
