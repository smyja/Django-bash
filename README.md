# Django-bash
This is a bash script for setting up django.
For Windows, change the virtual environment from `/venv/bin/activate` to `venv/scripts/activate`

Prefarably use a shortlink and curl to call the file. :)

Bitly shortlink is 
Run `curl -L  > s.sh` then `source s.sh`

### Running it on MacOS(use if source s.sh doesn't work)
Mac OS X uses the BSD version of sed, which treats the -i option slightly differently.
Use gsed instead, install with `brew install gnu-sed`
then run `curl -L  > a.sh` then `source a.sh`
